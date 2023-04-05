## Preface
WebP is an image file format developed by Google. Using WebP can reduce the file size of images while retaining the quality of images, thereby speeding up the loading speed of websites. However, many online image conversion tools cannot support the WebP format, so this article will introduce a self-made online image conversion tool to WebP, if you want to use WebP format images to optimize your website, this small tool is definitely worth it give it a try.

## Site
<font size=4pt>**[Click me to go to the WebP tool ヾ(•ω•`)o](https://michaelpig0912.github.io/sideProject/image2WebP/image2WebP.html)**</font>

## how to use
![Instructions for use](https://user-images.githubusercontent.com/39875566/229898609-fc89af6a-2705-4900-bbcc-b7046eaf18b0.png)
Using this widget is very easy, just follow these steps:
1. First set the "resolution" and "compression quality" after image conversion.


         a. The higher the "解析度", the less image loss, and vice versa.
         b. The larger the "壓縮品質", the less image loss, and vice versa.
2. Click the "選擇圖片檔案" button to select the image file to be converted. **Multiple files** can be selected.
3. Click the "下載" button to download the contents of a single image.
4. Click the "下載轉換完成的檔案" button to download all converted image files.

## code description

This code is an HTML, CSS and JavaScript based web application that converts selected image files to WebP format. Here are some highlights of the code:

1. Use the HTML input element to allow the user to select the image file to convert.
2. Use JavaScript and the JSZip library to process the image archive and add the converted image to the ZIP archive.
3. Use HTML and CSS to display converted image thumbnails and provide a download button.
4. Allow users to set the resolution and compression quality of the converted image.

## in conclusion

This article introduces a self-made small tool for converting online images to WebP. In addition to providing image conversion functions, this tool also has several SEO advantages. First of all, WebP can effectively reduce the size of image files, thereby improving the loading speed of the website, which is helpful to the user experience; secondly, the code of this gadget is written based on HTML, CSS and JavaScript, compatible with Various browsers, no need to install any software, very convenient to use. I hope this article can help users who need to convert images to WebP format, speed up the loading speed of the website, and improve the user experience. However, it should be noted that this tool currently does not support image files in HEIC format, and users should pay attention to the file format.
