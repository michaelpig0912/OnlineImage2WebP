## 前言
WebP 是一種由 Google 開發的圖像檔案格式，使用 WebP 可以減少圖像的檔案大小，同時保留圖像的品質，進而加速網站的載入速度。然而，許多線上的圖片轉換工具都無法支援 WebP 的格式，因此本文將介紹一個自製的線上圖片轉 WebP 的小工具，如果你想要使用 WebP 格式的圖片來優化你的網站，這個小工具絕對值得一試。

## 小工具網站
<font size=4pt>**[點我前往WebP小工具ヾ(•ω•`)o](https://michaelpig0912.github.io/sideProject/image2WebP/image2WebP.html)**</font>

## 如何使用
![使用說明](https://user-images.githubusercontent.com/39875566/229898609-fc89af6a-2705-4900-bbcc-b7046eaf18b0.png)
使用這個小工具非常簡單，只需要依照以下步驟：
1. 先設定圖像轉換後的「解析度」和「壓縮品質」。


        a. 「解析度」越高代表圖像損失會越少，反之亦然。
        b. 「壓縮品質」越大代表圖像損失會越少，反之亦然。
2. 點選「選擇圖片檔案」按鈕，選擇要轉換的圖像檔案，可以選擇**多個檔案**。
3. 點選「下載」按鈕，下載單張圖片內容。
4. 點選「下載轉換完成的檔案」按鈕，下載轉換後的全部圖像檔案。

## 程式碼說明

本程式碼是一個基於 HTML、CSS 和 JavaScript 的網頁應用程式，可以將選擇的圖像檔案轉換成 WebP 的格式。以下是程式碼的一些要點：

1.  使用 HTML 的 input 元素來讓使用者選擇要轉換的圖像檔案。
2.  使用 JavaScript 和 JSZip 函式庫來處理圖像檔案，並將轉換後的圖像添加到 ZIP 檔案中。
3.  使用 HTML 和 CSS 來顯示轉換後的圖像縮略圖，並提供下載的按鈕。
4.  提供使用者可以設定轉換後圖像的解析度和壓縮品質。

## 結論

本篇文章介紹了自製線上圖片轉 WebP 的小工具，此工具除了提供圖片轉換功能外，還具有幾個 SEO 優點。首先，WebP 可以有效地減少圖像檔案的大小，進而提高網站的載入速度，對於使用者的體驗有所幫助；其次，本小工具的程式碼是基於 HTML、CSS 和 JavaScript 撰寫，相容於各種瀏覽器，不需要安裝任何軟體，使用上非常方便。希望本文可以幫助需要將圖片轉換為 WebP 格式的使用者，加速網站的載入速度，提高使用者的體驗。但要注意的是，本工具目前暫不支援 HEIC 格式的圖像檔案，使用者需注意檔案的格式。
