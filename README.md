# Robo-Advisor with Python	

<a href="<Packtpub book link>?utm_source=github&utm_medium=repository&utm_campaign=<13-P ISBN>"><img src="https://static.packt-cdn.com/products/<13-P ISBN>/cover/smaller" alt="Robo-Advisor with Python" height="256px" align="right"></a>

This is the code repository for [Robo-Advisor with Python](<Packtpub book link>?utm_source=github&utm_medium=repository&utm_campaign=<13-P ISBN>), published by Packt.

**A hands-on guide to building and operating your own Robo-advisor**

## What is this book about?
Robo-advisors are becoming table stakes for the wealth management industry across all segments, from retail to high-net-worth investors. Robo-advisors enable you to manage your own portfolios and financial institutions to create automated platforms for effective digital wealth management. This book is your hands-on guide to understanding how Robo-advisors work, and how to build one efficiently. The chapters are designed in a way to help you get a comprehensive grasp of what Robo-advisors do and how they are structured with an end-to-end workflow.
You’ll begin by learning about the key decisions that influence the building of a Robo-advisor, along with considerations on building and licensing a platform. As you advance, you’ll find out how to build all the core capabilities of a Robo-advisor using Python, including goals, risk questionnaires, portfolios, and projections. The book also shows you how to create orders, as well as open accounts and perform KYC verification for transacting. Finally, you’ll be able to implement capabilities such as performance reporting and rebalancing for operating a Robo-advisor with ease.
By the end of this book, you’ll have gained a solid understanding of how Robo-advisors work and be well on your way to building one for yourself or your business.

This book covers the following exciting features: 
* Explore what Robo-advisors do and why they exist
* Create a workflow to design and build a Robo-advisor from the bottom up
* Build and license Robo-advisors using different approaches
* Open and fund accounts, complete KYC verification, and manage orders
* Build Robo-advisor features for goals, projections, portfolios, and more
* Operate a Robo-advisor with P&L, rebalancing, and fee management

If you feel this book is for you, get your [copy](https://www.amazon.com/dp/1801819696) today!

<a href="https://www.packtpub.com/?utm_source=github&utm_medium=banner&utm_campaign=GitHubBanner"><img src="https://raw.githubusercontent.com/PacktPublishing/GitHub/master/GitHub.png" alt="https://www.packtpub.com/" border="5" /></a>

## Instructions and Navigations
All of the code is organized into folders.

The code will look like the following:
```
stocks = Allocation("SPY", 0.6)
bonds = Allocation("TLT", 0.4)
myPortfolio = Portfolio("Growth", 4)
myPortfolio.allocations.append(stocks)
myPortfolio.allocations.append(bonds)
df = myPortfolio.getDailyPrices("20y")
```

**Following is what you need for this book:**
If you are a finance professional or a data professional working in wealth management and are curious about how robo-advisors work, this book is for you. It will be helpful to have a basic understanding of Python and investing concepts. This is a great handbook for developers interested in building their own robo-advisor to manage personal investments or build a platform for their business to operate, as well as for product managers and business leaders in financial services looking to lease, buy, or build a robo-advisor.	
With the following software and hardware list you can run all code files present in the book (Chapter 1-16).

### Software and Hardware List

| Chapter  | Software required                                                                    | OS required                        |
| -------- | -------------------------------------------------------------------------------------| -----------------------------------|
|   1-16   |   	Google Colab    	                                      		                  	  | Windows, Mac OS X, and Linux (Any) |
|   1-16   |   	Python																				                                    | Windows, Mac OS X, and Linux (Any) |

### Related products 
* Python for Finance Cookbook - Second Edition [[Packt]](https://www.packtpub.com/product/python-for-finance-cookbook-second-edition/9781803243191) [[Amazon]](https://www.amazon.com/dp/1803243198)

* Developing High-Frequency Trading Systems [[Packt]](https://www.packtpub.com/product/developing-high-frequency-trading-systems/9781803242811?_ga=2.158598970.1649601379.1677480968-1347501151.1654864057) [[Amazon]](https://www.amazon.com/dp/1803242817)

## Get to Know the Author
**Aki Ranin** is the founder of two A.I. startups in Singapore: Bambu in Fintech, and Healthzilla in Healthtech. He serves as Adjunct Lecturer at Singapore Management University on the topic of Machine Learning. His company Bambu has been a pioneer of Robo-advisor platforms since 2016, having built the first Robo-advisor in Singapore and worked with 20+ Enterprise clients across the world to design, build, and launch Robo-advisors
Aki lives in Singapore and holds a Masters Degree in Computer Science from Aalto University in Finland and writes occasionally about startups, philosophy, and technology
