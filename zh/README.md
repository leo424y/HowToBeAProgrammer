# How to be a Programmer 中文版
Robert L. Read with Community
[//]: # (Version:1.0.0)
Copyright 2002, 2003, 2016 Robert L. Read

Licensed under [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).

翻譯：[夢裡風林](https://github.com/ahangchen)

原文：[HowToBeAProgrammer](https://github.com/braydie/HowToBeAProgrammer)

如果您希望改進這份中文翻譯，請向這個[分支](https://github.com/ahangchen/HowToBeAProgrammer)提交Pull request。

[可以在gitbook線上閱讀或匯出PDF。](https://braydie.gitbooks.io/how-to-be-a-programmer/content/zh/index.html)

文章中出現的一些詞彙往往有特殊的含義，可以在[4-詞彙表](4-Glossary.md)找到註釋。

## 引言
　　做一個好的程式設計師，困難而高尚。將一個軟體工程集體願景變為現實，最困難的地方在於與你的同事和顧客相處。程式設計很重要，這需要強大的智力和技能。 但在好的程式設計師看來，相比構建一個讓客戶和各種各樣的同事都滿意的軟體系統，（純粹的）程式設計真的只是小孩子的玩意。在這篇文章裡，我嘗試儘可能簡潔地總結那些當我21歲時，希望別人告訴我的事。

　　這可能很主觀的，所以，這篇文章註定不適用於所有人，並且有的內容有點武斷。我儘量寫一些程式設計師在ta的工作中，非常可能會遇到的事情。大部分這些問題以及它們的解決方案在人們的環境中如此普遍，以至於我(說的)可能有點嘮叨。儘管如此，我還是希望這篇文章是有用的。

　　我們在課堂上學習程式設計。 那些著作: The Pragmatic Programmer [Prag99], Code Complete [CodeC93], Rapid Development [RDev96], 以及 Extreme Programming Explained [XP99] 都傳授程式設計（知識），並闡述做一個好的程式設計師這個大話題。 在讀這篇文章之前，或者就是現在，你當然也應該讀一讀Paul Graham [PGSite] 和 Eric Raymond [Hacker] 的文章。 但與那些著作不同，這篇文章強調社交問題並且總結了整套我所知的必須的技能。

　　在這篇文章裡，boss這個詞指的是任何一個交給你工程去做的人。 除了一些語境外，我會同義地使用交易，公司，集體這些詞，比如，交易意味著賺錢，公司意味著現代的工作空間，集體一般是那些你一起工作的人。

　　歡迎來到這個群體。

## 目錄

1. [入門](1-Beginner)
	- 個人技能
		- [學會 Debug](1-Beginner/Personal-Skills/01-Learn To Debug.md)
		- [如何通過分割問題 Debug](1-Beginner/Personal-Skills/02-How to Debug by Splitting the Problem Space.md)
		- [如何移除一個錯誤](1-Beginner/Personal-Skills/03-How to Remove an Error.md)
		- [如何使用日誌偵錯](1-Beginner/Personal-Skills/04-How to Debug Using a Log.md)
		- [如何理解效能問題](1-Beginner/Personal-Skills/05-How to Understand Performance Problems.md)
		- [如何解決效能問題](1-Beginner/Personal-Skills/06-How to Fix Performance Problems.md)
		- [如何優化迴圈](1-Beginner/Personal-Skills/07-How to Optimize Loops.md)
		- [如何處理 I/O 開銷](1-Beginner/Personal-Skills/08-How to Deal with IO Expense.md)
		- [如何管理記憶體](1-Beginner/Personal-Skills/09-How to Manage Memory.md)
		- [如何處理偶現的 Bug](1-Beginner/Personal-Skills/10-How to Deal with Intermittent Bugs.md)
		- [如何學習設計技能](1-Beginner/Personal-Skills/11-How to Learn Design Skills.md)
		- [如何進行實驗](1-Beginner/Personal-Skills/12-How to Conduct Experiments.md)
	- 團隊技能
		- [為什麼預估很重要](1-Beginner/Team-Skills/01-Why Estimation is Important.md)
		- [如何預估程式設計時間](1-Beginner/Team-Skills/02-How to Estimate Programming Time.md)
		- [如何搜尋資訊](1-Beginner/Team-Skills/03-How to Find Out Information.md)
		- [如何把人們作為資訊源](1-Beginner/Team-Skills/04-How to Utilize People as Information Sources.md)
		- [如何優雅地寫文件](1-Beginner/Team-Skills/05-How to Document Wisely.md)
		- [如何在垃圾程式碼上工作](1-Beginner/Team-Skills/06-How to Work with Poor Code.md)
		- [如何使用原始碼控制](1-Beginner/Team-Skills/07-How to Use Source Code Control.md)
		- [如何進行單元測試](1-Beginner/Team-Skills/08-How to Unit Test.md)
		- [毫無頭緒？休息一下](1-Beginner/Team-Skills/09-Take Breaks when Stumped.md)
		- [如何決定下班時間](1-Beginner/Team-Skills/10-How to Recognize When to Go Home.md)
		- [如何與不好相處的人相處](1-Beginner/Team-Skills/11-How to Deal with Difficult People.md)
2. [進階](2-Intermediate)
	- 個人技能
		- [如何保持活力](2-Intermediate/Personal-Skills/01-How to Stay Motivated.md)
		- [如何才能被廣泛信任](2-Intermediate/Personal-Skills/02-How to be Widely Trusted.md)
		- [在時間和空間之間該如何權衡](2-Intermediate/Personal-Skills/03-How to Tradeoff Time vs Space.md)
		- [如何進行壓力測試](2-Intermediate/Personal-Skills/04-How to Stress Test.md)
		- [如何權衡簡潔與抽象](2-Intermediate/Personal-Skills/05-How to Balance Brevity and Abstraction.md)
		- [如何學習新技能](2-Intermediate/Personal-Skills/06-How to Learn New Skills.md)
		- [學會打字](2-Intermediate/Personal-Skills/07-Learn to Type.md)
		- [如何進行整合測試](2-Intermediate/Personal-Skills/08-How to Do Integration Testing.md)
		- [交流語言](2-Intermediate/Personal-Skills/09-Communication Languages.md)
		- [重型工具](2-Intermediate/Personal-Skills/10-Heavy Tools.md)
		- [如何分析資料](2-Intermediate/Personal-Skills/11-How to analyze data.md)
	- 團隊技能
		- [如何管理開發時間](2-Intermediate/Team-Skills/01-How to Manage Development Time.md)
		- [如何管理第三方軟體風險](2-Intermediate/Team-Skills/02-How to Manage Third-Party Software Risks.md)
		- [如何管理諮詢](2-Intermediate/Team-Skills/03-How to Manage Consultants.md)
		- [如何適度交流](2-Intermediate/Team-Skills/04-How to Communicate the Right Amount.md)
		- [如何直言異議以及如何避免](2-Intermediate/Team-Skills/05-How to Disagree Honestly and Get Away with It.md)
	- 評判
		- [如何權衡開發質量與開發時間](2-Intermediate/Judgment/01-How to Tradeoff Quality Against Development Time.md)
		- [如何管理軟體系統依賴](2-Intermediate/Judgment/02-How to Manage Software System Dependence.md)
		- [如何評判軟體是否太不成熟了](2-Intermediate/Judgment/03-How to Decide if Software is Too Immature.md)
		- [如何決定購買還是構建](2-Intermediate/Judgment/04-How to Make a Buy vs Build Decision.md)
		- [如何專業地成長](2-Intermediate/Judgment/05-How to Grow Professionally.md)
		- [如何評估面試者](2-Intermediate/Judgment/06-How to Evaluate Interviewees.md)
		- [如何決定什麼時候使用奇妙的電腦科學](2-Intermediate/Judgment/07-How to Know When to Apply Fancy Computer Science.md)
		- [如何與非工程師交談](2-Intermediate/Judgment/08-How to Talk to Non-Engineers.md)
3. [高階](3-Advanced)
	- 技術評判
        - [如何從不可能中找到困難的部分](3-Advanced/Technical-Judgment/01-How to Tell the Hard From the Impossible.md)
        - [如何使用嵌入型語言](3-Advanced/Technical-Judgment/02-How to Utilize Embedded Languages.md)
        - [選擇語言](3-Advanced/Technical-Judgment/03-Choosing Languages.md)
    - 機智地妥協
        - [如何與時間壓力作鬥爭](3-Advanced/Compromising-Wisely/01-How to Fight Schedule Pressure.md)
        - [如何理解使用者](3-Advanced/Compromising-Wisely/02-How to Understand the User.md)
        - [如何獲得晉升](3-Advanced/Compromising-Wisely/03-How to Get a Promotion.md)
    - 服務你的團隊
        - [如何發展才能](3-Advanced/Serving-Your-Team/01-How to Develop Talent.md)
        - [如何選擇工作內容](3-Advanced/Serving-Your-Team/02-How to Choose What to Work On.md)
        - [如何讓你隊友的價值最大化](3-Advanced/Serving-Your-Team/03-How to Get the Most From Your Teammates.md)
        - [如何劃分問題](3-Advanced/Serving-Your-Team/04-How to Divide Problems Up.md)
        - [如何處理無聊的問題](3-Advanced/Serving-Your-Team/05-How to Handle Boring Tasks.md)
        - [如何為工程獲取支援](3-Advanced/Serving-Your-Team/06-How to Gather Support for a Project.md)
        - [如何發展一個系統](3-Advanced/Serving-Your-Team/07-How to Grow a System.md)
        - [如何有效地溝通](3-Advanced/Serving-Your-Team/08-How to Communicate Well.md)
        - [如何告訴人們他們不想聽的東西](3-Advanced/Serving-Your-Team/09-How to Tell People Things They Don't Want to Hear.md)
        - [如何處理管理神話](3-Advanced/Serving-Your-Team/10-How to Deal with Managerial Myths.md)
        - [如何處理混亂的組織](3-Advanced/Serving-Your-Team/11-How to Deal with Organizational Chaos.md)
4. [詞彙表](4-Glossary.md)
5. [附錄 A - 書籍/網站](5-Bibliography.md)
6. [附錄 B - 歷史 (至2016年1月)](6-History.md)
6. [附錄 C - 貢獻 (至2016年1月)](7-Contributions.md)


<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Text" property="dct:title" rel="dct:type">How To Be A Programmer: Community Version</span> by <span xmlns:cc="http://creativecommons.org/ns#" property="cc:attributionName">Robert L. Read with Community</span> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
