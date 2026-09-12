# payment-demo-shop

ezPay 簡單付與藍新金流測試購物網站。

## 目前功能

- 六項虛構測試商品
- 購物車與數量調整
- ezPay／藍新付款方式選擇
- 瀏覽器本機操作紀錄（Local Storage，最多保留 100 筆）
- 後端未設定時阻擋送出交易

## 架構

- 前台：GitHub Pages
- 安全後端：Cloudflare Workers（下一階段建立）
- 金流：僅串接官方測試環境

## 安全提醒

MerchantID、HashKey、HashIV 與其他機密不得寫入本儲存庫。正式金流參數將保存於 Cloudflare Secrets。
