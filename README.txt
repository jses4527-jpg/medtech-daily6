醫檢師 Daily 6｜快取更新修正 v1.3.1

修正：
- 保留「題庫瀏覽／指定題目」功能。
- 修正 GitHub 已更新但 iPhone/iPad 仍顯示舊首頁的問題。
- 首頁 HTML 改成 network-first，優先抓最新版本。
- 新 Service Worker 接管後會自動重新整理一次。
- 首頁新增「版本 v1.3.1」小標示，方便確認是否真的更新成功。
- Service Worker 快取版本升至 v7。

更新方式：
1. GitHub → medtech-daily6 → Add file → Upload files
2. 上傳 index.html 與 sw.js，覆蓋同名檔案
3. Commit changes
4. 等 GitHub Pages 重新部署
5. Safari 開：
   https://jses4527-jpg.github.io/medtech-daily6/?v=131
   這個帶 ?v=131 的網址可以繞過舊首頁快取，適合第一次驗證新版。
6. 看到「版本 v1.3.1」以及「題庫瀏覽／指定題目」後，就代表更新成功。
