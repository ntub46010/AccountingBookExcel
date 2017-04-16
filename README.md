# 自動化會計帳簿
## 簡介
本帳簿可自動化地實現基本的會計流程。<br>
首先建立會計科目，並填寫開帳時的初始餘額。<br>
在日記簿中可做分錄，列數不足時按下按鈕會增加列數。分作12個區塊，相當於12個月。<br>
分類帳內有一區塊填寫欲查詢的科目及月份，按下按鈕即可查閱該科目的餘額增減狀況。<br>
工作底稿與現實的會計報表不同，內含試算表、綜合損益表、資產負債表。程式將從日記簿抓取資料，依科目歸納後列示。<br>
本計帳簿起初是用以本人日常記帳使用，因此不需製作大量財務報表。

<br>

## 功能
* 會計科目表
* 日記簿
* 分類帳
* 總額式試算表
* 餘額式試算表
* 綜合損益表
* 資產負債表

<br>

## 實作方式
* 資料驗證：避免使用者輸入不符合格式的內容
* VBA巨集：增刪會計科目、在日記簿增加列數、在分類帳查詢紀錄、在工作底稿產生簡易報表
