# 破解編碼面試 - 中文翻譯 

- 作者： [Gayle Laakmann McDowell](http://www.gayle.com/contact/)
- 原書名稱：[Cracking the Coding Interview: 189 Programming Questions and Solutions](https://www.amazon.com/Cracking-Coding-Interview-6th-Edition/dp/0984782850)
- 譯者：[F8F-1BearCat](https://f8f-1bearcat.github.io/about/) 

<div align=center><img src="img/Cover.jpg"/></div>



## 譯者序

[](譯者摸魚的時候喜歡逛一畝三分地論壇，在 `終身學習>刷題` 板塊里偶然發現了 CtCI 這本書。本書被譽為北美碼農求職面試經典書籍，因書中包含 189 道編碼題，所以也被稱為 CC189，更早的版本為 CC150。)

這本書介紹了 Microsoft、Google 等一線網際網路公司的面試流程，講解了該怎樣準備面試、怎樣回答技術問題，還單獨拿出一些篇幅教你如何評估選擇 Offer 以及如何跟 HR 進行 Negotiation。 當然，有關時間復雜度、空間復雜度以及具體的面試題目才是本書的重點。

本書的 189 道題目以數據機構和演算法為主，其題目及答案占據了本書絕大部分的內容。此外，分別有一個章節涵蓋分佈式系統設計、C/C++、Java、數據庫、多線程等知識性的內容，但是這些內容幾乎都是淺嘗輒止，旨在為讀者提供一個簡略卻系統的知識框架，讓讀者可以根據自己的薄弱環節有目的的去強化訓練。這 189 道題涵蓋了編程面試中你可能遇到的大部分題型，題目有易有難，且所有題目都給出了比較常規的解題思路和答案，其中演算法題目的實現使用了 Java 語言。當然有些解法不是最優，如果你有興趣的話可以在此基礎上自己嘗試給出最優解。

就好比考 GMAT 之前要看 OG 一樣，本書是針對編程面試的入門書籍。如果你工作多年，需要重新將數據結構和演算法撿起來的話，本書很適合你；但如果你是打過 ACM 等演算法比賽的大牛，或者從事與演算法相關的工作，那這本書就可以直接跳過了。由於是面向編碼面試的，本書自然不能避免其功利性，如果純粹是想學習演算法，可以去看一看 Programming Pearls 等書。本書的題目與實際面試相比還是稍簡單的，如果你想進一步提升的話，建議到 Leetcode 上刷題，並自己消化總結。

順便一提，一畝三分地論壇還經常提到另一本書：[Programming Interview Exposed](https://www.amazon.com/Programming-Interviews-Exposed-Secrets-Landing/dp/1118261364/?&_encoding=UTF8&tag=1point3acres-20&linkCode=ur2&linkId=f4a9f284abef2e91bbc0bc39a9cc3967&camp=1789&creative=9325)，這本書更基礎一點，非科班零基礎的小白可以嘗試先從這本書入手。

最後，譯者在此建議，有能力的讀者最好還是去閱讀本書的英文原版。

## 目錄

#### [序](Foreword.md)
#### [引言](Introduction.md)
#### [I. 面試過程](I.The_Interview_Process.md)
#### [II. 幕後](II.Behind_the_Scenes.md)
#### [III. 特殊情況](III.Special_Situations.md)
#### [IV. 面試之前](IV.Before_the_Interview.md)
#### [V. 行為問題](V.Behavioral_Questions.md)
#### [VI. Big O](VI.Big_O.md)
#### [VII. 技術問題](VII.Technical_Questions.md)
#### [VIII. Offer 及其他](VIII.The_Offer_and_Beyond.md)
#### [IX. 面試問題](IX.Interview_Questions.md)

**數據結構**

- [Chapter 1 I 數組和字元串](Chapter_1_Arrays_and_Strings.md)
- [Chapter 2 I 鏈表](Chapter_2_Linked_Lists.md)
- [Chapter 3 I 棧和隊列](Chapter_3_Stacks_and_Queues.md)
- [Chapter 4 I 樹和圖](Chapter_4_Trees_and_Graphs.md)

**概念和演算法**

- [Chapter 5 I 位操作](Chapter_5_Bit_Manipulation.md)
- [Chapter 6 I 數學和邏輯難題](Chapter_6_Math_and_Logic_Puzzles.md)
- [Chapter 7 I 面向對象的設計](Chapter_7_Object-Oriented_Design.md)
- [Chapter 8 I 遞歸和動態規劃](Chapter_8_Recursion_and_Dynamic_Programming.md)
- [Chapter 9 I 系統設計和可擴展性](Chapter_9_System_Design_and_Scalability.md)
- [Chapter 10 I 排序與搜索](Chapter_10_Sorting_and_Searching.md)
- [Chapter 11 I 測試](Chapter_11_Testing.md)

**基礎知識**

- [Chapter 12 I C 和 C++](Chapter_12_C_and_C++.md)
- [Chapter 13 I Java](Chapter_13_Java.md)
- [Chapter 14 I 數據庫](Chapter_14_Databases.md)
- [Chapter 15 I 線程和鎖](Chapter_15_Threads_and_Locks.md)

**附加復習題**

- [Chapter 16 I 中等](Chapter_16_Moderate.md)
- [Chapter 17 I 困難](Chapter_17_Hard.md)

#### [X. 答案](https://github.com/careercup/CtCI-6th-Edition)
#### XI. 進階主題
#### [XII. 代碼庫](XII.Code_Library.md)
#### XIII. 提示
#### [XIV. 關於作者](XIV.About_the_Author.md)

註：本書的 `X. 答案` 部分為編碼答案，本項目中不做翻譯收錄，需要閱讀的同學可以閱讀英文原版，或者 *CareerCup* 的這個項目：https://github.com/careercup/CtCI-6th-Edition 。

## 法律聲明

> 《中華人民共和國著作權法》
> 第四節 權利的限制
> 第二十二條　在下列情況下使用作品，可以不經著作權人許可，不向其支付報酬，但應當指明作者姓名、作品名稱，並且不得侵犯著作權人依照本法享有的其他權利：
> (六)為學校課堂教學或者科學研究，翻譯或者少量復制已經發表的作品，供教學或者科研人員使用，但不得出版發行;

本項目是出於個人興趣及學習目的而建立，僅供交流與學習研究之用，嚴禁公開傳播發行或用於商業用途。有能力閱讀英文書籍者請購買原版支持。

**APPEND**：經 v2ex 網友提醒，本書官方中文版本已出版，中文名為程式員面試金典（譯者在此忍不住吐槽此譯名），第六版發行日期為 19 年 9 月份，難怪譯者當時沒找到。所以在此譯者建議大家有需要的話通過官方渠道購買書籍，本項目可以做譯文對比、溝通交流之用，感謝大家的支持。

## LICENSE

本項目中的文檔是根據 CC BY-NC-SA 4.0 許可協議授權的，該協議鼓勵您共用這些文檔。

詳情見：[署名-非商業性使用-相同方式共用 4.0 國際  (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.zh)