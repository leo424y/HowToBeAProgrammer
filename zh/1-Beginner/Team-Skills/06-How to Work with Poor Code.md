# 如何在糟糕的程式碼上工作
[//]: # (Version:1.0.0)
工作在別人寫的糟糕的程式碼上是常有的事。不要把他們想得太糟，直到你用他們的鞋子走路時。他們可能被要求非常自覺地快速完成一些東西來滿足時間表的壓力。不管之前發生了什麼，為了在不清晰的程式碼上工作，你必須理解它。理解它需要花費一些學習時間，你必須堅持從時間表中某些部分劃出一部分時間來做這件事。為了理解它們，你必須讀原始碼，你可能需要在上面做一些實驗。

即使是為你自己，編寫文件也是一個好的時機，因為嘗試為你的程式碼編寫文件會強迫你從你可能沒有考慮過的角度思考，並且完成的文件可能會有用。當你在做這個時，考慮重寫部分或所有程式碼會消耗你什麼東西。是否重寫一部分程式碼事實上真的會節省時間？你重寫程式碼後你會更信任它嗎？在這裡小心你的傲慢。如果你重寫它，你處理它會更容易，但下一個必須閱讀它的人是否真的更加容易？如果你重寫了，測試的負擔在哪裡？重新測試的需要是否大於可能獲得的好處？

在任何對你沒有編寫的程式碼的評估中，程式碼的質量會影響你對風險問題的認識以及一些未知的事情。

銘記抽象和封裝是很重要的，這兩個程式設計師最好的工具，對糟糕的程式碼是特別好用的。你可能不能夠重新設計一大塊程式碼，但如果你可以為它增加一定量的抽象，你不用重新在這整團迷霧上工作就可以獲一些好的設計所帶來的好處。特別的，你可以嘗試去隔離尤其糟糕的程式碼，這樣他們就可以被獨立重構。

Next [如何使用原始碼控制](07-How to Use Source Code Control.md)
