# Homework14
14th Homework

An algo trading example using machine learning to form predicitions.

"In this Challenge, you’ll assume the role of a financial advisor at one of the top five financial advisory firms in the world. Your firm constantly competes with the other major firms to manage and automatically trade assets in a highly dynamic environment. In recent years, your firm has heavily profited by using computer algorithms that can buy and sell faster than human traders.

The speed of these transactions gave your firm a competitive advantage early on. But, people still need to specifically program these systems, which limits their ability to adapt to new data. You’re thus planning to improve the existing algorithmic trading systems and maintain the firm’s competitive advantage in the market. To do so, you’ll enhance the existing trading signals with machine learning algorithms that can adapt to new data."

Baseline Results
![baseline_report](https://github.com/doughj1466/Homework14/assets/145073929/bf9b1926-608c-4946-836e-e3a38876e7c1)
![baseline_results](https://github.com/doughj1466/Homework14/assets/145073929/d831470b-0407-47dd-886e-887d34b96ac2)

18mo training Results
![18mo_report](https://github.com/doughj1466/Homework14/assets/145073929/e77a1b4e-41d3-426d-8928-8b2fb6059430)
![18mo_results](https://github.com/doughj1466/Homework14/assets/145073929/4fdb0e03-939e-4cc0-b844-8a3c7048e0ee)

SMA (10/250) Results
![sma_change_report](https://github.com/doughj1466/Homework14/assets/145073929/37dfb3b6-3653-47ee-9e55-54aa67f4067b)
![sma_change_results](https://github.com/doughj1466/Homework14/assets/145073929/3c50924b-939c-42a7-8605-a4f8d2dde7f7)

AdaBoost Results
![AB_report](https://github.com/doughj1466/Homework14/assets/145073929/6f4ce4dc-c570-4429-b11c-ecce597db0c3)
![AB_results](https://github.com/doughj1466/Homework14/assets/145073929/54fe9b73-7186-4140-bad6-a67ae6070f14)

(Sorry for formatting, I ran out of time to look up how to make this prettier.)

The results are interesting.  None of the results for overall returns are particularly impressive.  If I was a financial advisor or trader I don't think I would endorse any of these.  Maybe the baseline but I would need to do further analysis of the risk/reward trade off first.  The 18mo training change gave the best precision but as you can see in the graph, this does not necessarily translate to better returns.  The SMA changes did worse and so did the AdaBoost classifier.  This assignment sheds light to how much testing is needed prior to finding a successful candidate for production.







