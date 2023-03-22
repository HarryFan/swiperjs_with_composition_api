##Swiper JS & Composition API
這是一個使用 Swiper JS 和 Composition API 的 Vue 3 範例。

這個範例使用了 Swiper JS 套件來建立一個輪播圖片的效果。而使用 Vue 3 的 Composition API，可以更方便地管理數據和生命週期。

#安裝
這個範例不需要安裝任何套件，只需下載後在瀏覽器打開 index.html 即可。

#使用
這個範例使用了 Mocky API 來模擬從後端獲取圖片數據，因此需要連接到網絡才能正常運行。

在 index.html 中，我們使用了 Vue 3 的 Composition API 來建立一個 App 對象。在 setup 方法中，我們使用了 Vue.reactive() 創建了一個數據對象 images，並使用 Vue.onMounted() 方法在頁面加載完成後從 Mocky API 獲取圖片數據，並將其添加到 images 對象中。

最後，使用 Vue.createApp() 方法將 App 對象掛載到 HTML 文件中的 #app 元素上，使得 Vue 應用程序能夠運行。

#技術棧
Vue 3
Swiper JS
授權
這個範例是根據 MIT 授權條款發布的，詳情請查看 LICENSE 文件。