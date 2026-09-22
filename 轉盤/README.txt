Lucky Spin - GitHub Pages JSON 版本

將 index.html 與 options.json 放在 GitHub Repository 同一資料夾。

永久修改：
直接修改 options.json，Commit / Push 後，所有電腦重新開啟網頁即可取得新名單。

臨時修改：
網頁內仍可新增、刪除、修改選項，但不會寫回 GitHub。
重新整理頁面後會重新載入 options.json。

最多讀取 20 個選項。
程式已使用 no-store 與時間參數降低 JSON 快取影響。

注意：
直接雙擊 index.html 以 file:// 開啟時，瀏覽器可能禁止讀取本機 JSON。
部署到 GitHub Pages 後即可正常讀取。

轉盤文字：中文直排；連續英文字母與數字以橫向字組顯示。每一直行最多 8 個排版單位，超過後由右向左換至第二行。
