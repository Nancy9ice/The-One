# The One
_The dataset of this project was analyzed exclusively with Microsoft Excel._

## **Problem Statement**
Roland owns an e-commerce company that sells vacations online via their website. Sales are going down and Roland isn't finding it funny. It's affecting his health too. He thinks something is wrong with the website and he has told the management to figure out what is wrong. 

But...

This website has several webpages where sales of different vacations are carried out. All these webpages can't be improved at once. It will cost so much money. So management wants to know that **one** webpage that needs to start being worked on first and they need it fast!

"Please do your best! The health of our CEO depends on the outcome of your analysis." Those words rang in my head as I collected the dataset containing the performance of their website from them. 

Before I move forward, click this LINK to get enlightened about my thought process in working on this project.

## **All Metrics but one, are in good shape**
Marketing is required to drive traffic to an e-commerce website but if the website isn't tailored to the needs of users, this traffic (no matter how high it is) will be a waste. 

The journey of a potential customer or user starts from this traffic. When this user gets on the website, the appealing visuals, high loading speed, and organized layout could make the user stay longer and move past the first screen. If he doesn't leave because all these are in order, then the only thing that could make him leave the site is a complicated or non-intuitive navigation. Fortunately, this website has minimal bounce rate and even falls within the range of the e-commerce acceptable standard of 20% - 45%. It surpassed the 25% target of the company by 1%.

![](Charts/Overall%20Bounce%20Rate.png)

Since the bounce rate of the website is good enough, the next question to ask is, do these users come back to this website for more? Answering this is more on the marketing side though where the effectiveness of the company's re-targeting strategy is evaluated. But the website user experience is still important in the aspect of new and engaging content, and quality images. This most likely meets these standards because 53.23% of users are returning to the site which is higher than the percentage of new users.

![](Charts/Overall%20Percentage%20Existing%20Users.png)

So far, the bounce rate and percentage returning users have commendable figures, but are these users staying long enough to purchase their product? The answer is Yes. The time that the users are spending on the website is even higher than the target of 3minutes. 

![](Charts/Overall%20Session%20Duration.png)

Staying for a long time on this website could either be for good or for bad. The truth is, knowing if it's for good or for bad can be determined by studying the behavior of users on the website through a recommended tool, Hotjar. If it's for good, then the content is engaging and if it's bad, it means the users can't find what they are looking for on the website.

Hotjar is not the only way to find this out though. Another way is by knowing the conversion rate. A look at the conversion rate shows that it's way below the target. The target is 1.53% and the actual rate is just 0.22%.

![](Charts/Overall%20Conversion%20Rate.png)

This could be a sign that these users are not finding what they are looking for on this website. But we shouldn't jump into conclusions yet because this is a website that sells vacations. Users might actually be wasting time on the website because they are reading details of the vacations. 

If this is true, then they might not be puchasing the vacations because the copy isn't persuasive or the call to action isn't clear enough. 

## **Three Landing Pages have Recurring Poor Metrics**
Now, all the metrics seems encouraging except the conversion rate that is very low. It's either few of the landing pages are performing very terribly or most of the landing pages are performing badly. The sole aim of my analysis though is to pinpoint just one that is performing very badly so it can be improved as soon as possible.

To do this, we should consider the time, money and efforts that will be invested in making these improvements. Hence, the need to only focus on landing pages that have higher traffic. The overall visits on the website is 8228 on the average. Focusing on the 47 landing pages that have visits greater than 8228 will save a lot of time and money.

![](Charts/Landing%20Page%20Count%20by%20Website%20Visits.png)

Out of these 47 landing pages, five landing pages that have the lowest conversion rates, lowest percentage returning users, and highest bounce rates were evaluated, and a pattern was noticed. Three landing pages repetitively appeared in at least two of these three poor metrics. The landing pages were the global, region1, and country12 pages. 

![](Charts/Least%20Five%20Landing%20Pages.png)

But there's a significant observation; global landing page appeared in all three poor metrics. Why did this happen? Before we answer this, we need to evaluate the conversion rate of these three landing pages overtime to pinpoint if the global landing page is the one. 

A close look at the conversion rate overtime shows that the other two actually have a growing conversion rate even though the rates are still way below the target. But there's an alarming reduction in the conversion rate of global landing page which has even gone down to zero.

![](Charts/Selected%20Landing%20Pages%20by%20Conversion%20Rate.png)

**Global landing page is the one**

## **Everything is Wrong with the Global Landing Page**
Just like as it has been said before, the Global landing page is among the five landing pages with the least bounce rate, lowest conversion rate to the extent of reaching zero, and the landing page with the lowest number of returning users. 

Using Hotjar to study the behaviour of users on the website would have been best to make conclusions on the causes. However, Hotjar is not integrated in the website, so experiments will be carried out to know which improvements are most effective. The results of the effectiveness will reveal the actual causes of these poor performance.

## **What Should be Done**
* First of all, integrate Hotjar into the website.
* Get ready for an A/B test.
* Change the visuals of the global landing page and carry out an A/B test with the old version for seven days.
* Choose the one with the higher conversion rate. Call this Landing Page A. Then get ready for another A/B test.
* Make the navigation of Landing Page A more intuitive and carry out an A/B test with the first version of Landing Page A for seven days.
* Choose the one with the higher conversion rate. Call this Landing Page B. Then get ready for another A/B test.
* Make the copy of Landing Page B more persuasive and the CTA clearer. Then carryout an A/B test with the first version of Landing Page B for seven days.

**What Will Happen if Action is Delayed**