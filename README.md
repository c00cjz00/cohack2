# FLY2
根據約翰霍普金斯大學所提供的各國即時確診數據，建置台灣與各國復航評估平台FLY2，系統平台以簡易的紅黃綠燈號，標示台灣與各國家間抵達復飛門檻的距離, 提供決策者重啟國際交流的一最新參考指標。

![alt text](https://github.com/c00cjz00/cohack2/blob/master/fly.png "Demo")

## 300個字內的概念說明（包含解決問題標的、技術應用說明、預期擴大應用之成效）。

### 解決問題標的
台灣政府面對COVID-19，為了控制疫情，採取「限縮兩岸航空客運直航航線」及「全面禁止旅客來台轉機」。也因此何時重新開放台灣通往國際的天空，是廣大民眾近期極為關切的議題。因此團隊合作開發建置台灣與各國復航評估平台FLY2，此平台將複雜的趨勢數據簡化成易懂的紅黃綠燈號。讓民眾一眼明瞭台灣與國際復航的門檻距離
，也為了提供決策者重啟國際交流的一最新參考指標。
### 技術應用說明
利用爬蟲針對翰霍普金斯大學所提供的各國即時確診數據，進行資料論證、分群及分析。並利用每日確診的增加數據，計算台灣與各國的差異，轉換成台灣與各國家間抵達復飛門檻的距離。
### 預期擴大應用
此平台可自動掌握世界關注的任何議題，最即時的了解各國對議題看法包含政府政策走向及民意，也可建立一個統一的通知與回報系統，並擁有簡易的共享資料串流，提供全世界開發者進行任何應用。

## 請說明本提案對於「國際防疫政策」及「社會影響貢獻」的重要性(300字以內)
有共同的平台了解各國對疫情的政策與民意，將更有效促進國際防疫合作，有統一個通知與回報系統，將大幅降低各國之間溝通的成本，人民也可以利用這單一窗口，有效地了解各國政府目前的政策與疫情即時情況，這也會降低各國政府發布的人力成本。
此平台如果未來成為媒體或民眾會得到最新消息的窗口之一，將更有效整合政府其他部門的消息發布，未來對於公衛上要如何執行跟規範，世界各國也可以分享自身的經驗，共同度過艱難的時刻。

## 目前掌握了哪些相關資料？(例如資料的時間區間、資料格式、資料欄位、資料筆數、資料蒐集方法等)。
### 各國資料
1. 台灣衛福部疾管署：https://www.cdc.gov.tw/
2. 台灣政府資料開放平台：https://data.gov.tw/
3. 約翰霍普金斯大學 CSSE：https://github.com/CSSEGISandData/COVID-19
4. 美國國家衛生研究院 NIH： https://www.nih.gov/
5. 美國政府開放資料：https://www.data.gov/
6. 歐盟資料平台：https://www.europeandataportal.eu/

## 是解決方案所需之必要資料，但尚未掌握的資料？
想做大數據分析，需要有專業的人士進行資料分類，或是給予正確的label，才有辦法讓數據分析變得精確，這部分需要大量的人力幫忙，部分資料是可以採用unsupervised的方式進行label，但想要有精確且具意義的預測，如果可以結合官部門以及民間的feedback作為資料的label，將會是讓這些大數據資料變得更有意義的事情。
對於疫情想做更深入的資料探勘，需要有更私密的個人資料才有辦法進行分析，通常就需要政府對於資料進行開源。

## 本次提案成果之影響或預期效益(300字以內) *
當各國想共同建立平台時，將會更大有效率的資訊交流與合作，開放資料平台分享與世界重要事項通知，在未來將會是非常重要的一塊，這次的疫情也不會是最後一次，如何有效率的分享各國政府控制疫情的經驗，以及醫療學術上關於疫情的重大發現，都可以大大降低這次新冠病毒對全世界造成的影響，透明的資訊交流，將可以提早的讓疫情或重要事項讓全世界知道，更早進行封鎖以及世界各國聯手合作。

## 其他關於提案之補充說明(如：提案的Source code，建議提供上傳至GitHub的連結) *
https://github.com/c00cjz00/cohack2

## 提案補充說明URL(如：提案概念影片、簡報等) *
簡報
https://docs.google.com/presentation/d/1cOgTHSxBDyDFIOlIUP5qcf1EsIVSQs3f_U7PlpDhcZI/edit#slide=id.p

## 對本次台美防疫松(cohack)是否有其他建議？
徵求題目說明內容太過於先進，無法讓參賽者一眼明顯主辦單位的用意，建議可以採用HACKMD等呈現模式，簡化說明內容。


