# Swiper JS & Composition API
這是一個使用 Swiper JS 和 Composition API 的 Vue 3 範例。

這個範例使用了 Swiper JS 套件來建立一個輪播圖片的效果。而使用 Vue 3 的 Composition API，可以更方便地管理數據和生命週期。

## 安裝
這個範例不需要安裝任何套件，只需下載後在瀏覽器打開 index.html 即可。

## 使用
這個範例使用了 Mocky API 來模擬從後端獲取圖片數據，因此需要連接到網絡才能正常運行。

在 index.html 中，我們使用了 Vue 3 的 Composition API 來建立一個 App 對象。在 setup 方法中，我們使用了 Vue.reactive() 創建了一個數據對象 images，並使用 Vue.onMounted() 方法在頁面加載完成後從 Mocky API 獲取圖片數據，並將其添加到 images 對象中。

最後，使用 Vue.createApp() 方法將 App 對象掛載到 HTML 文件中的 #app 元素上，使得 Vue 應用程序能夠運行。

## 技術棧
Vue 3
Swiper JS
授權
這個範例是根據 MIT 授權條款發布的，詳情請查看 LICENSE 文件。






# 標題：Swiper JS & Composition API 實現圖片輪播

## 摘要：
本文將介紹如何利用 Swiper JS 和 Vue 3 的 Composition API 實現一個簡單的圖片輪播功能。

## 技術概述：

使用 Swiper JS 作為輪播的底層庫
利用 Vue 3 的 Composition API 進行開發

# 應用結構：

引入 Swiper JS 和 Vue 3 的 CDN 連結
使用 Vue 3 的 setup 函數定義元件邏輯
在 mounted 階段，使用 fetch 獲取圖片資料並初始化 Swiper 實例
利用 v-for 指令渲染圖片列表

## 實現步驟：

在 head 標籤內引入 Swiper JS 和 Vue 3 的 CDN 連結。

在 style 標籤內定義 Swiper 相關的樣式。

在 body 標籤內建立一個 div 容器作為 Vue 應用的掛載點，並將 Swiper 相關的結構放入該容器。

在 script 標籤內，使用 Vue 3 的 Composition API 定義一個名為 App 的元件。

a. 使用 setup 函數定義元件邏輯。
b. 定義一個名為 images 的陣列，用於存放圖片資料。
c. 使用 onMounted 函數，在元件掛載完成後執行以下操作：
i. 使用 fetch 函數獲取圖片資料。
ii. 將圖片資料存入 images 陣列。
iii. 初始化 Swiper 實例，並設定相應的配置。

最後，將 App 元件掛載到容器 div。

完成以上步驟後，您將成功實現一個基於 Swiper JS 和 Vue 3 Composition API 的圖片輪播功能。


