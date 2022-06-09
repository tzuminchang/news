https://charliewuuu.github.io/Cinema_5_aboutTickets/

預計以此頁作為組件基準（頁面內容最單純，比較好設定）

HTML
目前已有的外部連結已加上去
例如購票頁面、IG、FB、YT等

另外，為了好定位，我常常會多加一層container
有些也許最後沒功用，看不懂再問我

SCSS: 分成body(含背景)、navbar、header、main、footer
body中的背景：
　底圖目前用鎖定，滾動不影響呈現範圍
　尾巴用視差效果，讓滾動過程感覺有東西跟著移動
nav高度65px，position:fixed
header的高度有點玄，我要多做幾頁才知道怎麼抓比較好
main資訊框與footer距離為200px
footer設定padding: 40px

JS: 分成navbar、script
nvabar操控navbar的動作，例如下拉框、最愛數量、搜尋bar開合
script含背景的視差效果、資訊框的開合
裡面好像JS、JQuery語法穿插出現，太亂的話還請包涵
