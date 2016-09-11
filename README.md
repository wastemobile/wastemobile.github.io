## Hexo

使用 Hexo 生成網站，也用它的部署功能 `hexo deploy`。

GitHub 的個人靜態網站是這樣：

- 使用 `https://username.github.io` 這個網址
- 使用 `username.github.io` 這樣的倉儲名稱
- 預設是以 `master` 分支為預設

因此 `master` 分支可以直接擺靜態網站的檔案，也就是 hexo 生成後的 `public` 目錄內容。

使用 Jekyll 是 **特例** ，你可以直接推送整個 Jekyll 倉儲到 `master` 分支，不需要事先在本地執行「生成」程序，只有 Jekyll 是這樣。

因此目前 `wastemobile.github.io` 倉儲，同步到各台電腦必須使用 `hexo` 分支，部署時則是設定到 `master` （在 hexo 的 `_config.yml` 檔案中寫入）。