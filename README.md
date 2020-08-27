# Quasar App (shop)

## 工作紀錄
1. 註冊TAB PANEL完成，fixed height待設定
2. 想辦法tree shake firebase(太肥)

## bug
1. q-interesection 和 GRID系統衝突而無作用

## 預定開發
1. 成交訂單紀錄上傳DB、管理者介面(?)
2. 語言自動偵測
3. 考慮是否導入SSR

## 已解決Bug
1. 購物車刪除選項無法控制數量
2. Vue Route Gate 無法結合Vuex(進入Checkout前)
3. Q-SELECT 搭配 i18n，綁定值沒有跟著翻譯
4. Filter菜單後，螢幕寬度>sm時要Reset filter
5. 合併相同食物數量(ref by refernce會改變原值數量，造成金額錯誤)

## 已完成功能
1.  TAB PANELS整合
2.  表單驗證
3.  付款表單
4.  MOBILE 下滑顯示回頂端的按鈕
5.  translate
6.  lt.sm的狀態，下拉選單選擇食物分類
7.  金額驗證(不得大於20000)
8.  儲值扣款系統
9.  History分頁
10. 合併訂單
11. 購買紀錄
12. History排序
13. 加入中文字體
14. 統一配色
15. 確認EMAIL是否被註冊過
16. 登入註冊Panel完成

## Install the dependencies
```bash
yarn
```

### Start the app in development mode (hot-code reloading, error reporting, etc.)
```bash
quasar dev
```

### Lint the files
```bash
yarn run lint
```

### Build the app for production
```bash
quasar build
```

### Customize the configuration
See [Configuring quasar.conf.js](https://quasar.dev/quasar-cli/quasar-conf-js).
