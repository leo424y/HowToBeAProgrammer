# 如何進行壓力測試
[//]: # (Version:1.0.0)
壓力測試很有趣，一開始好像壓測的目的是找出系統在負載下能不能工作。現實中，系統在負載下確實能工作，但在負載足夠重的某些情況下不能工作。我把這叫做*碰壁*或*撞響*<sup>[1]</sup>。可能會有例外，但大多數情況下會有這麼一堵“牆”。壓測的目的是為了指出牆在哪裡，然後弄清楚怎麼把牆移得更遠些。

壓測計劃需要在工程的早期就規劃好，因為它經常有助於弄清楚到底什麼是被期望的。兩秒的網頁請求是一個悲傷的失敗還是一個了不起的成功？500個併發使用者是否足夠？這，當然，視情況而定，但一個人在設計系統時就應該知道滿足需求的答案。壓測需要足夠好地為現實建模，使之足夠有用。非常容易地模擬500個不穩定並且不可預測的人並行使用系統不是真的可能的，但我們可以至少創造500個模擬（使用者），然後嘗試模擬他們可能做的部分事情。

在壓測中，從輕負載開始，然後為系統在一些維度上增加複雜 - 比如輸入頻率和輸入規模 - 直到你抵達那堵牆。如果牆太近了以至於不能滿足你的需要，弄明白哪個資源是瓶頸（這通常是那個主要的資源）。它是記憶體？處理器？I/O？網路頻寬？還是資料連線？然後弄明白你可以怎麼移動那堵牆。記錄下移動牆的那個要素，也就是增加了系統可以處理的負載的那個要素，它可能不能真正在低負載系統下產生危害。但通常重負載下的表現比輕負載下更重要。

你必須能夠觀察幾個不同維度，以此來為之構建一個思維模型；單一的技術是不夠的。例如，日誌經常是給出系統中兩個事件間的掛鐘時間的好主意。但除非仔細構建，日誌不會給出記憶體使用的可見性甚至是資料結構的大小。相似的，在現代系統裡，大量電腦和許多軟體系統是合作的。特別是在你碰到那堵牆時（也就是，表現與輸入不成線性比例時），這些軟體系統可能成為瓶頸。對這些系統的透視力，甚至僅僅對所有參與工作的機器的處理器做測量，都可能是非常有幫助的。

意識到牆在哪裡的關鍵不僅是移動這堵牆，而且也是提供對其的預測能力。這樣公司可以得到更高效的管理。

---

<sup>[1]</sup> "撞響"

Next [如何在簡潔與抽象間平衡](05-How to Balance Brevity and Abstraction.md)
