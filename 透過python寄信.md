###### tags: `python`

# 透過python寄信

## 申請google應用程式密碼
- 針對特定服務建立新密碼，除了可以限定該密碼可以使用的google權限之外，也不用讓自己google曝光在程式碼當中
- 就算啟用兩段式驗證的google帳號也可以申請

1. 連到 https://myaccount.google.com/security

2. 點「應用程式密碼」
![](https://i.imgur.com/FCSc54T.png)
3. 點「選取應用程式」，選取「郵件」
![](https://i.imgur.com/GMUWfbn.png)
4. 點「選取裝置/其他（自訂名稱）」
5. 輸入專案名稱，點「產生」
6. 產生該專案使用的密碼（帳號同原本google帳號）
![](https://i.imgur.com/dK1Be32.png)
7. 在專案的config.py中輸入google帳號及應用程式密碼
![](https://i.imgur.com/oeMGQIb.png)

該密碼只能用於收發該google帳號的郵件服務，其他雲端硬碟等服務都不能使用

## python寄信範例請參考flast_init中的webapp/blueprint/contact/controller.py第16行
之後再補python寄信功能的解說影片


## 參考資料
- [Flask實作_ext_09_Flask-Mail_郵件發送](https://hackmd.io/@shaoeChen/BytvGKs4M?type=view)