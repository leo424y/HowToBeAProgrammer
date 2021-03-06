# 如何在開發質量與開發時間權衡
[//]: # (Version:1.0.0)
軟體開發總是在工程該做什麼與完成工程間妥協。但你可能被要求以犧牲你的工程適用性或商業適用性的方式，去交換工程的開發速度。例如，你可能被要求做一些糟糕的軟體工程實踐，但這將會導致大量維護問題。

如果這發生了，你的首要任務是通知你的團隊，然後清楚地解釋降低質量的代價。在這之後，你對這個問題的理解會比你的 boss 的理解還要更清晰。明白將會失去什麼以及將要得到什麼，以及在這次失去的東西，能在下一輪中得到什麼。在這個過程中，由一個好工程提供的可見性應該會很有用。如果用質量換時間影響了質量保證工作，(向你的 boss 和質量保證人員)指出這個問題。如果用質量換時間會導致在之後的質量保證週期中出現更多的 bug，指出來。

如果她仍然堅持，你應該把劣質部分隔離到特殊的你可以在下一個開發週期計劃重寫或優化的元件中。向你的團隊解釋這個問題，這樣他們可以為此做些計劃。

忍者程式設計師在 Slashdot 寫下了這樣的格言：

> 記住，一個好的設計會被糟糕的程式碼實現彈回。如果好的介面和抽象在程式碼中到處存在，最後的重寫會更加痛苦。如果寫難以修復的清晰程式碼很困難，考慮是什麼與核心設計衝突的東西導致了這個問題。

Next [如何管理軟體依賴](02-How to Manage Software System Dependence.md)
