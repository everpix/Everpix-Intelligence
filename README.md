About Everpix
-------------

Everpix was started in 2011 with the goal of solving the Photo Mess, an increasingly real pain point in people's life photo collections, through ambitious engineering and user experience.

After 2 years of research and product development, and although having a very enthousiastic user base of early adopters, we didn't succeed in raising our Series A in the highly competitive VC funding market. Unable to continue operating our business, we had to announce our upcoming shutdown on November 5th, 2013.

High-Level Metrics
------------------

At the time of the Everpix shutdown announcement, the Everpix platform had 50,000 signed up users and 400 millions photos while generating subscription sales of $40,000 / month during the last 3 months (i.e. enough money to cover variable costs, but not the fixed costs of the business).

The following high-level metrics are from September 2012, when we started selling subscriptions, to October 2013, the last month before our shutdown announcement:

![Users](https://raw2.github.com/everpix/Everpix-Intelligence/master/_graphs/users.png)

![Photos](https://raw2.github.com/everpix/Everpix-Intelligence/master/_graphs/photos.png)

![Subscribers](https://raw2.github.com/everpix/Everpix-Intelligence/master/_graphs/subscribers.png)

![Sales](https://raw2.github.com/everpix/Everpix-Intelligence/master/_graphs/sales.png)

![Retention](https://raw2.github.com/everpix/Everpix-Intelligence/master/_graphs/retention.png)

*Retained users: users who used the Web, iOS, Mac, Windows Everpix apps or opened a Flashback email.*

Complete Dataset
----------------

Building a startup is about taking on a challenge and working countless hours on solving it. Most startups do not make it but rarely do they reveal the story behind, leaving their users often frustrated. Because we wanted the Everpix community to understand some of the dynamics in the startup world and why we had to come to such a painful ending, we worked closely with a reporter from The Verge who chronicled our last couple weeks. The [resulting article](http://www.theverge.com/2013/11/5/5039216/everpix-life-and-death-inside-the-worlds-best-photo-startup) generated extensive coverage and also some healthy discussions around some of our high-level metrics and financials. There was a lot more internal data we wanted to share but it wasn't the right time or place.

With the Everpix shutdown behind us, we had the chance to put together a significant dataset covering our business from fundraising to metrics. We hope this rare and uncensored inside look at the internals of a startup will benefit the startup community.

Here are some example of common startup questions this dataset helps answering:
* What are investment terms for consecutive convertible notes and an equity seed round? What does the end cap table look like? (see [here](Financials.md))
* How does a Silicon Valley startup spend its raised money during 2 years? (see [here](Financials.md))
* What does a VC pitch deck look like? (see [here](Presentation Slides/Everpix VC Pitch Deck.pdf))
* What reasons do VCs give when they pass? (see [here](Anonymized VC Feedback.md))
* What are the open rate and click rate of transactional and marketing emails? (see [here](Internal Metrics/Sendgrid %28Emails to Everpix Users%29.csv))
* What web traffic do various news websites generate? (see [here](Public Feedback/Press Coverage.csv) and [here](External Metrics/Daily Website Traffic.csv))
* What are the conversion rate from product landing page to sign up for new visitors? (see [here](Internal Metrics/System Users %28First Time Visitors to Web Invites Ratio - Weekly%29.csv))
* How fast do people purchase a subscription after signing up to a freemium service? (see [here](Internal Metrics/Latencies %28Monthly Subscription Latency in Days - Since March 1st%29.csv) and [here](Internal Metrics/Latencies %28Yearly Subscription Latency in Days - Since March 1st%29.csv))
* Which countries have higher suscription rates? (see [here](Internal Metrics/User Countries %28Free Users Countries%29.csv) and [here](Internal Metrics/User Countries %28Subscribed Users Countries%29.csv))

The dataset is organized as follow:
* **[Anonymized VC Feedback.md](Anonymized VC Feedback.md):** Unedited feedback from VCs who passed on Everpix
* **[External Metrics](External Metrics):** Raw metrics retrieved from external systems like Google Analytics or AWS billing
* **[Financials.md](Financials.md):** High-level financials with fundraising and final P&L
* **[Internal Metrics](Internal Metrics):** Raw and computed metrics from our service from photos imported to subscription sales
* **[Presentation Slides](Presentation Slides):** The slides used to introduce Everpix to press and investors along with the latest version of our more extensive VC pitch deck
* **[Public Feedback](Public Feedback):** Press articles covering Everpix and user reviews on App Stores
* **[Timeline & Numbers.md](Timeline & Numbers.md):** Everpix product timeline and numbers

The metrics in the dataset were "frozen" as of November 6th, 2013 (the day following the announcement of Everpix's shutdown) and represent more than 90% of all available Everpix metrics. Only metrics covered by NDAs with partners or metrics exposing identifiable Everpix users information have been omitted.

*To maximize reusability, metrics are formatted as [CSV files](https://en.wikipedia.org/wiki/Comma-separated_values) (using UTF-8 text encoding) and with the first row being the column names.*
