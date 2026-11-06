# 宏道獎報名系統

## 本機預覽

直接開啟 `index.html` 即可預覽。報名資料目前儲存在瀏覽器 localStorage。

## Firebase Hosting 部署

1. 安裝 Firebase CLI：`npm install -g firebase-tools`
2. 登入：`firebase login`
3. 在專案根目錄執行：`firebase use <你的 Firebase project ID>`
4. 部署：`firebase deploy --only hosting`

不需要把帳號密碼提供給任何人；請在 Firebase 官方登入頁面自行完成登入。

## GitHub

設定 remote 後執行：

```bash
git push -u origin master
```
