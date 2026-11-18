醫檢師 Daily 6｜圖片與原題頁偵錯修正版 v1.2

本版修正：
1. 純文字題不再因為同頁有圖而誤顯示整頁考卷。
2. PDF 內真正有圖、表格或特殊符號圖片的題目會顯示原題頁。
3. 文字抽取明顯破損、選項空白、頁首頁尾污染的題目會顯示原題頁作為保險。
4. 「承上題」且依賴前題圖片的題目會沿用相關原題頁。
5. 更新 PWA cache 至 v5，避免 Safari 持續讀舊版。

已驗證：
- 5760 題完整保留
- 296 題需要原題頁
- 335 個原題頁面資源
- 所有圖片引用 0 缺檔
- 110-1 生理病理第1題不再顯示錯誤整頁圖
- 真正 ECG 題（如110-1第5、7、8題）仍保留圖

GitHub 更新：
將本 ZIP 解壓後，回 medtech-daily6 repo -> Add file -> Upload files，選取：
- index.html
- sw.js
- images-110-1.js 到 images-115-2.js（共12個）
上傳後 Commit changes。
manifest 與 icon 未變，可不必重傳。

GitHub Pages 部署完成後：
Safari 重新整理；若已加入主畫面，請把 App 完全關閉後重開。必要時可先用 Safari 直接開網址確認新版本。
