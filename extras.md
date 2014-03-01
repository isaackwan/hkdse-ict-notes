# 網際網路通訊協定第6版 (IPv6)
IPv6 是網際網路通訊協定(Internet Protocol) 的第**六**個版本。

它的地址有 128 個位元 (bits)。即總共有 2^128 個地址組合。

一般表達時，由八組的數字組成，每組有四個十六進制 (hexadecimal) 的數字。
注意的是，地址內的0可以被略過。中間的 : 也可以略過。

以下是地址舉例：
* 2001:470:0:76::2
* 2a03:2880:f002:101:face:b00c::1
* ::1

# 網路釣魚 (Phishing)
透過 e-email, SMS 等方法，偽裝成銀行等公司，以騙取用戶個人資料。

## 範例
![Example 1](https://upload.wikimedia.org/wikipedia/commons/d/d0/PhishingTrustedBank.png)
![Example 2](http://i.imgur.com/WpGKycm.png)

## 解決方法
* 安裝阻擋釣魚網站的工具／瀏覽器
* 不要開啟不明來歷的電郵的連結或附件
* 檢查清楚網站的域名
* 查看目標網站的 EV Certificate (見下文)

# 延伸驗證證書 (Extended Validation Certificate)
延伸驗證證書可確保伺服器的擁有人是一家註冊的公司。通常，證書上會寫上公司的所在地，甚至地址。
這可避免網路釣魚的問題。

## 範例
![Effect on Google Chrome](http://i.imgur.com/CtaDe8y.png)
![Effect on iOS Safari](http://i.imgur.com/oLhCdvh.png)

# 雲端運算 (Cloud computing)
雲端運算即在公有互聯網共享的軟硬件及資訊來作運算等。

## 好處
1. 可擴展性 (Scalability)
一般來說，雲端運算可以自動分配更多的資源來面對突如其來的需求，而不會有處理不來的情況。此外，不少雲產品是按小時計費的。
例子：蘋果公司發佈新產品時，科技網站 gdgt 有數以十陪的流量增加。然而雲系統會自動分配更多資源 (RAM, CPU, etc)去確保網站順暢。

2. 高可用性 (High Availability, HA)
不單止會有多重備份，而且也在世界各地有伺服器，就算其中的伺服器出了問題，其他伺服器會自動接手，維持原有伺服器的功能。

## 分類
* 軟件即服務 (Software-as-a-service, SaaS)
軟件服務供應商，以租賃的概念提供客戶服務，而非購買。不少是以線上的型式提供服務。
例子：Google Docs, Microsoft Office 365, Salesforce.com

* 平台即服務 (Platform-as-a-service, PaaS)
由雲平台管理軟件，操作系統，及基建 (網絡，電源等)。客戶只須管理自已的應用程式，特別適合小型公司。

* 基礎架構即服務(Infrastructure-as-a-service, IaaS)
除基建 (網絡，電源等)外，其他由客戶管理。比 PaaS 更大自由度，適合大型公司。

![Cloud service hierarchy By Bikeborg](https://upload.wikimedia.org/wikipedia/commons/3/3c/Cloud_computing_layers.png)