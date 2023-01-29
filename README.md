# Laravel 9 Livewire 簡單廣告、橫幅、額外資訊管理工具

引入 5balloons 的 laravel-smart-ads 套件來擴增簡單廣告、橫幅、額外資訊管理工具，可以建立廣告以及追蹤活動點擊成效來瞭解廣告活動吸引潛在客戶的效果，並據此調整廣告來提升宣傳效益。

## 使用方式
- 把整個專案複製一份到你的電腦裡，這裡指的「內容」不是只有檔案，而是指所有整個專案的歷史紀錄、分支、標籤等內容都會複製一份下來。
```sh
$ git clone
```
- 將 __.env.example__ 檔案重新命名成 __.env__，如果應用程式金鑰沒有被設定的話，你的使用者 sessions 和其他加密的資料都是不安全的！
- 當你的專案中已經有 composer.lock，可以直接執行指令以讓 Composer 安裝 composer.lock 中指定的套件及版本。
```sh
$ composer install
```
- 產生 Laravel 要使用的一組 32 字元長度的隨機字串 APP_KEY 並存在 .env 內。
```sh
$ php artisan key:generate
```
- 執行 __Artisan__ 指令的 __migrate__ 來執行所有未完成的遷移。
```sh
$ php artisan migrate
```
- 在瀏覽器中輸入已定義的路由 URL 來訪問，例如：http://127.0.0.1:8000。
- 你可以經由 `/smart-ad-manager` 來進行廣告管理。

----

## 畫面截圖
![](https://i.imgur.com/p6bLfiU.png)
> 廣告與客戶搜尋標的的關聯性越高，對客戶的吸引力就越大，更有可能帶來理想成效