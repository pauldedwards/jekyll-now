---
title: TSB and banking transformation
date: 2018-05-10
tags: agile
published: true
---
I have had experience of a public launch which didn't go to plan. I know that it isn’t a nice experience and it’s very stressful. But, the comments made to the press and on TV by the CEO of TSB are interesting and suggest why their migration went so badly wrong. They show how the organisation’s ways of working may have led to the expensive outage.

I am going to look at some of his quotes in detail and then compare them to some examples of other banks which are going about their digital transformations in a more coherent way. 

### Testing

> “Pester says there was “extensive testing”, with nine cycles of testing before the bank took the plunge..." - The Guardian 24th April 2018

Nine cycles of testing is not enough testing for a small project. For a project of this scale is suggests poor planning and implementation. Not testing the code and implementation exposes the organisation to a high level of risk.

10-15 years ago software testing was a manual task carried out at the end of a waterfall software project. In Modern software tests are written before the code. This is known as (Test Driven Development) or TDD. Features are developed in short cycles which allows quick feedback from the users. Features are then tested end-to-end using automated tests before they are put live. These tests cycles can run many times a day ensuring that any changes to the code do not cause issues.

### User needs

> "It’s very hard to recreate how customers are going to use the platform...” - The Guardian 24th April 2018

The first step in any software project should be to understand the user needs. Only when you understand the outcomes your customers want you can write code that will benefit them.

Delivering small sections of working code into the hands of users as early as possible means you can test your assumptions quickly and gain feedback from the customers you are working with.

Monitoring and measuring the working code will show any unusual behaviour or problems with the design of the application. This will identify where changes need to be made.

### Trust and collaboration

> “If you or I trust IT guys every time they tell us it's all going to work fine then we would be in a different business” - ITV News 24th April 2018

This language suggests a lack of cohesiveness and collaboration across the organisation. It points to an Us (“The Business”) and Them (“IT Guys”) culture and hints at a lack of experience at a senior level of working with technology.

The data migration is the ultimate responsibility of the CEO but responsibility needs to be shared across the organisation.

Delivery of the software should involve multi-disciplinary teams so that decisions aren’t siloed and risks are identified early. Creating cross-discipline teams allows you to design the application more effectively, make decisions more quickly and share knowledge.

Banks are increasingly becoming technology companies. A recent survey by RBS showed that less than 1% of their customers visit a branch regularly [https://stv.tv/news/features/1403526-banks-what-is-behind-the-rising-number-of-branch-closures/].

Having a CEO who is technically literate should be a basic requirement for modern banks. This language wouldn’t be acceptable from a CEO speak about legal, marketing, PR or finance matters so why is it still accepted when speaking about IT?

Compare this to the way ING Barings have approached transformation or the laguage used by the CFO of DBS [https://thefinanser.com/2018/05/challenging-dbs-measure-digital-innovation.html] [https://www.hbs.edu/faculty/Pages/item.aspx?num=53838]

ING ensured that the same way of working was observed across the entire organisation and that delivery wasn’t just an IT responsibility.

### Scaling

> "Pester says that TSB’s website app struggled with a “large number of concurrent users”, who tried to access their accounts on Sunday evening once the migration process was over. We didn’t have enough bandwidth to cope, he says - so we’re addressing that problem now." - The Guardian 24th April 2018

These are very similar comments to the one about not knowing how customers use the application. It is a straightforward task to work out how many people will use the application and cloud based technologies can be set-up to scale much more easily than past infrastructure.

One of the key pieces of information any Product Owner should know about their application is how their application is used and by how many people.

When you know this information you can scale your application to handle the usage patterns. 

### One big launch

I don’t know the exact detail of the TSB migration project however, I have been involved in large, highly visible software launches. I know that there are many ways of reducing the risk of these projects even if complex legacy systems are involved.

One method is to reduce the release of software into frequent, small, highly tested releases. This reduces the risk and increases the availability of feedback so that bugs and issues can be dealt with quickly.

Putting a "must-meet" deadline in place is not necessarily a problem as long as you are willing to descope.

There are typically 3 variables in a project - Time, People and Scope. If any one of these variables is fixed then the other two have to move to cope. In this case a fixed deadline should have meant a reduction in scope to meet that deadline.

### Conclusion

It is clear from the public problems that this was a migration that went very wrong. I understand that the legacy code was old and complex but that doesn’t excuse the trouble it has caused customers. Using a Continuous Delivery approach to software development with a full and comprehensive test strategy would have mitigated against the worst issues that have occured.

Modern CEOs should be capable of understanding the fundamentals of software delivery, at the very least they should be briefed by individuals who are educated in modern technology. The barriers between the “business” and “technology” are breaking down. In this case The bank is technology and for a CEO to be unable to understand this means

### More links

http://www.wired.co.uk/article/tsb-crisis-it-issues-online-banking-problems-ibm-paul-pester-compensation

https://www.theguardian.com/business/live/2018/apr/24/tsb-online-banking-troubles-uk-public-finances-business-live?page=with%3Ablock-5adf6a60e4b0ed4091d25689

http://www.itv.com/news/2018-04-24/tsb-boss-apologises-after-customers-hit-by-it-glitches/

https://twitter.com/chrisapplegate/status/991246555096256512
