# 6-1 訂單出貨流程

系統登入後，顯示畫面在同步功能頁面

![](https://github.com/lifecomService/LifeERP_manuals/tree/c5f5cca33bca11311bde6512cab215b123ef8fd0/.gitbook/assets/image%20%28120%29.png)

狀態說明

訂單轉入後尚未分配的訂單，訂單處理狀態為等待處理 訂單作業狀態為0 未處理

![](https://github.com/lifecomService/LifeERP_manuals/tree/c5f5cca33bca11311bde6512cab215b123ef8fd0/.gitbook/assets/image%20%2889%29.png)

訂單轉入後，被分配的訂單，訂單處理狀態為5,6 預備出貨 訂單作業狀態為0 未處理

![](https://github.com/lifecomService/LifeERP_manuals/tree/c5f5cca33bca11311bde6512cab215b123ef8fd0/.gitbook/assets/image%20%28161%29.png)

訂單分配後，已取得配送編號的訂單，訂單處理狀態為5,6 預備出貨 訂單作業狀態為1 已取得配送編號

![](https://github.com/lifecomService/LifeERP_manuals/tree/c5f5cca33bca11311bde6512cab215b123ef8fd0/.gitbook/assets/image%20%28132%29.png)

訂單分配後，已印完託運單的訂單，訂單處理狀態為5,6 預備出貨 訂單作業狀態為2 已產出託運單

![](https://github.com/lifecomService/LifeERP_manuals/tree/c5f5cca33bca11311bde6512cab215b123ef8fd0/.gitbook/assets/image%20%2845%29.png)

已出貨訂單，訂單處理狀態為22 出貨完成 訂單作業狀態為8 出貨完成

![](https://github.com/lifecomService/LifeERP_manuals/tree/c5f5cca33bca11311bde6512cab215b123ef8fd0/.gitbook/assets/image%20%2874%29.png)

出貨流程

訂單管理→訂單資料轉入→訂單檔上傳\(csv\)→暫存表資料確認→執行轉入→分配庫存→彙總揀貨單列印→\(電子發票取號\)→出貨單據列印→出貨刷讀驗證→訂單結案

1. 訂單資料轉入

![](https://github.com/lifecomService/LifeERP_manuals/tree/c5f5cca33bca11311bde6512cab215b123ef8fd0/.gitbook/assets/image%20%2897%29.png)

![](https://github.com/lifecomService/LifeERP_manuals/tree/c5f5cca33bca11311bde6512cab215b123ef8fd0/.gitbook/assets/image%20%28102%29.png)

＊狀態說明

訂單可接受：代表此訂單無誤

賣場訂單編號重複：代表此筆訂單已有上傳過，避免重複上傳至系統

無此賣場貨號：代表此訂購的品項沒有於系統內建檔，請確認商品資料或訂單檔是否資料有誤

1. 分配/庫存

![](https://github.com/lifecomService/LifeERP_manuals/tree/c5f5cca33bca11311bde6512cab215b123ef8fd0/.gitbook/assets/image%20%28165%29.png)

1. 取得配送編號

![](https://github.com/lifecomService/LifeERP_manuals/tree/c5f5cca33bca11311bde6512cab215b123ef8fd0/.gitbook/assets/image%20%2841%29.png)

1. 彙總揀貨單列印&電子發票取號&出貨單據列印

![](https://github.com/lifecomService/LifeERP_manuals/tree/c5f5cca33bca11311bde6512cab215b123ef8fd0/.gitbook/assets/image%20%2887%29.png)

1. 出貨驗證刷讀

![](https://github.com/lifecomService/LifeERP_manuals/tree/c5f5cca33bca11311bde6512cab215b123ef8fd0/.gitbook/assets/image%20%28107%29.png)

![](https://github.com/lifecomService/LifeERP_manuals/tree/c5f5cca33bca11311bde6512cab215b123ef8fd0/.gitbook/assets/image%20%2850%29.png)

＊若訂單內品項A001購買數量為2件

當A001商品刷讀一件時，會呈現黃色，代表尚未刷讀完成

待刷讀完成後，會呈現藍色

如刷錯品項，系統會以提示聲來警示

1. 訂單結案

![](https://github.com/lifecomService/LifeERP_manuals/tree/c5f5cca33bca11311bde6512cab215b123ef8fd0/.gitbook/assets/image%20%28105%29.png)

1. 出貨總表列印

![](https://github.com/lifecomService/LifeERP_manuals/tree/c5f5cca33bca11311bde6512cab215b123ef8fd0/.gitbook/assets/image%20%281%29.png)

![](https://github.com/lifecomService/LifeERP_manuals/tree/c5f5cca33bca11311bde6512cab215b123ef8fd0/.gitbook/assets/image%20%28131%29.png)
