# Fraud

Nearly everyone has been here. You're at the mall, decide to splurge, maybe on some concert tickets, a fresh new pair of shoes, some designer jeans, whatever. You get to the register all set to make your purchase and, whoops, CARD DECLINED. You try your card again, and still, declined. You panic, frantically checking your account to make sure that you haven't been hacked, search for other cards in your wallet that don't exist. The cashier stares at you, awkwardly, before nodding to the person behind you in line to take your place. That is, until you get a text from the bank: "Did you try to make this purchase?" Releived you select yes, hop back in line, swipe your card and all is well. 

It's annoying in the moment, but this techonology saves consumers and businessees millions of dollars each year. Further, the Machine Learning behind the technology is designed so that so that it must not miss fraud, for obvious reasons, which that it may flag purchases needlessly. But what if we could build a model, that was just as good at detecting fraud, while not embarassing innocent folks in the mall. This is what I sought out to do. 






I acquired all of my data from Vesta via Kaggle. Vesta Corporation is an fraud detection firm that specializes in Ecommerce and guarantees more than 18 billion dollars in online transactions each yea.r They released the datasets as part of a Kaggle competition that they sponsored. 



Though four datasets were provided by Vesta, I only chose to use two: the transaction training set as well as the transaction test set. As far as feature engineering , I removed the 334 "Vesta engineered feature" columns since, all of them had more than 400,000 null values, and it was never articulated exactly what each feature represented. 