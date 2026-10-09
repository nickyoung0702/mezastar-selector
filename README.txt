Mezastar 對戰選擇器 PWA 安裝說明

這個資料夾是完整網站,全部檔案要放在同一層:
  index.html  manifest.webmanifest  sw.js  icon-192.png  icon-512.png  icon-maskable-512.png

注意:PWA 必須放在 https 網址上才能離線與加到桌面,直接雙擊 index.html 開啟不會啟用離線。

【最快:Netlify Drop】
1. 開啟 https://app.netlify.com/drop
2. 把整個 pwa 資料夾拖進去
3. 取得網址,傳給別人即可

【GitHub Pages】
1. 建立公開儲存庫,上傳這些檔案到根目錄
2. Settings > Pages,Branch 選 main / root
3. 網址為 https://帳號.github.io/儲存庫名/

【手機加到桌面】
iPhone:Safari 開網址 > 分享 > 加入主畫面
Android:Chrome 開網址 > 選單 > 安裝應用程式 / 加到主畫面
第一次連網開啟後,之後可離線使用。

【更新資料】
改 index.html 後,把 sw.js 第一行 mz-v1 改成 mz-v2 再重新上傳,使用者重開兩次即更新。
