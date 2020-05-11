# FLY2 各國復航評估平台
根據約翰霍普金斯大學所提供的各國即時確診數據，建置台灣與各國復航評估平台FLY2，系統平台以簡易的紅黃綠燈號，標示台灣與各國家間抵達復飛門檻的距離, 提供決策者重啟國際交流及經濟活動的一最新參考指標。
![alt text](https://github.com/c00cjz00/cohack2/blob/master/fly3.jpg "Demo")
![alt text](https://github.com/c00cjz00/cohack2/blob/master/fly2.png "Demo")

## 300個字內的概念說明（包含解決問題標的、技術應用說明、預期擴大應用之成效）。

### 解決問題標的
台灣政府面對COVID-19，為了控制疫情，採取「限縮兩岸航空客運直航航線」及「全面禁止旅客來台轉機」。也因台灣此何時重新開啟通往國際的天空，是廣大民眾近期極為關切的議題。因此團隊合作開發建置台灣與各國復航評估平台FLY2，此平台將複雜的趨勢數據簡化成易懂的紅黃綠燈號。能讓民眾一眼明瞭台灣與國際復航的門檻距離，也能提供決策者重啟國際交流一最新且即時的參考指標。
### 技術應用說明
採用爬蟲技術，針對翰霍普金斯大學所提供的各國即時確診數據，進行資料論證、分群及分析。並分析各國每日確診的增加數據，計算台灣與各國的差異，轉換成台灣與各國家間抵達復飛門檻的距離。
### 預期擴大應用
此平台亦可分析各國間的復飛門檻的距離，並提供簡易的共享資料串流，提供全世界開發者進行任何應用。

## 請說明本提案對於「國際防疫政策」及「社會影響貢獻」的重要性(300字以內)
COVID-19 新型冠狀疫情為世界經濟帶來了前所未有的衝擊，世界各國為了對抗COVID-19，實施了封鎖邊境和社交隔離等一連串的措施，以期穩定市場。而台灣近期在在疫情獲得控制之後，也逐漸在思考何時何地開始適度開放經濟活動的問題。本專題研究與所開發的平台FLY2，利用分析各國即時的COVID-19確診數據，提供一能讓民眾及決策者重啟國際交流及經濟活動的一最新且即時的參考指標。其成果將大幅降低各國之間溝通與各國政府發布決策的人力分析與時間成本。

## 目前掌握了哪些相關資料？(例如資料的時間區間、資料格式、資料欄位、資料筆數、資料蒐集方法等)。
### 各國資料
1. 台灣衛福部疾管署：https://www.cdc.gov.tw/
2. 台灣政府資料開放平台：https://data.gov.tw/
3. 約翰霍普金斯大學 CSSE：https://github.com/CSSEGISandData/COVID-19
4. 美國國家衛生研究院 NIH： https://www.nih.gov/
5. 美國政府開放資料：https://www.data.gov/
6. 歐盟資料平台：https://www.europeandataportal.eu/

## 是解決方案所需之必要資料，但尚未掌握的資料？
大數據分析，其最重要的根本乃是數據資料本身是否正確與精準。本專案根據約翰霍普金斯大學所提供的各國即時確診數據進行爬蟲技術分析，但因其統計數據來自於186個國家的近千位回報人員所提供的即時填報數據，難免會有誤差產生。針對此問題，此專案人員雖有開發演算法，針對數據不合理部分進行自動判讀校正，但此非長久之計。如果可以結合官部門以及民間的feedback作將約翰霍普金斯大學所提供的各國即時確診數據更正確化，便是目前尚未掌握的一個點。

## 本次提案成果之影響或預期效益(300字以內) *
對抗COVID-19，實施了封鎖邊境和社交隔離等一連串的措施，以期穩定市場。而在風雨過後，重新啟動國際交流及經濟活動是一個更重要的議題。團隊合作開發建置台灣與各國復航評估平台FLY2，此平台將複雜的趨勢數據簡化成易懂的紅黃綠燈號。能讓民眾一眼明瞭台灣與國際復航的門檻距離，也能提供決策者重啟國際交流及經濟活動一最新且即時的參考指標。

## 其他關於提案之補充說明(如：提案的Source code，建議提供上傳至GitHub的連結) *
https://github.com/c00cjz00/cohack2

## 提案補充說明URL(如：提案概念影片、簡報等) *
簡報
https://www.youtube.com/watch?v=tgXcOuE13Nc

## 對本次台美防疫松(cohack)是否有其他建議？
徵求題目說明內容太過於先進，無法讓參賽者一眼明顯主辦單位的用意，建議可以採用HACKMD等呈現模式，簡化說明內容。


