---
layout: post
title: "What the Facebook Disinformation Scandal Means for Your Company"
metatitle: "Facebook Disinformation Scandal - Apply Identity Management Tools"
description: "Implement identity management tools for all of your users as you scale."
metadescription: "Learn how implementing identity management tools from Auth0 can help your company avoid data breach incidents and disinformation scandals like Facebook."
date: 2018-09-14 14:38
category: Hot Topics, Security, Breaches
post_length: 1
is_non-tech: true
author:
  name: Diego Poza
  url: https://twitter.com/diegopoza
  avatar: https://avatars3.githubusercontent.com/u/604869?v=3&s=200
  mail: diego.poza@auth0.com
design:
  bg_color: "#29335c"
  image: https://cdn.auth0.com/blog/data-security/logo.png
tags:
  - security
  - data
  - breach
  - data-breach
  - facebook
  - enterprise
  - mfa
  - two-factor
  - authentication
  - identity
  - 2fa
related:
- 2018-08-03-what-data-did-facebook-really-give-cambridge-analytica
- 2018-09-07-3-critical-lessons-from-the-t-mobile-data-breach
- 2018-06-18-how-two-factor-authentication-can-help-financial-institutions-reduce-data-breaches
---

On August 21, Facebook took down over 600 accounts, pages, and groups that originated in Iran. These accounts were disseminating political disinformation, largely targeted at users in Latin America and the Middle East.

Cybersecurity firm FireEye initially tipped Facebook off about a network of pages called Liberty Front Press. Their reach was 74 Facebook pages, 70 accounts, and 3 groups, as well as 76 Instagram accounts.

The tip also led Facebook to discover an array of other networks, pages, and accounts that were disseminating false information — and engaging in cybersecurity attacks.

With these issues so widespread on the platform, how could Facebook not have figured it out sooner?

Coupled with numerous other [data breaches](https://auth0.com/blog/what-companies-can-learn-from-the-reddit-data-breach/) across multiple companies this year, the most recent Facebook incident highlights how important it is for companies to continually update their user-management practices as they scale — before bad activity gets out of control.

## Facebook's Disinformation Incident Reveals the Challenge of Monitoring All of Your Users

The number of daily active users on Facebook has nearly tripled since 2011. Today, it boasts 1.47 billion users worldwide.

![Facebook daily user statistics](https://cdn.auth0.com/blog/facebook-scandal:daily-users.png)
 
In addition, as of Q2 2018, the company had over 25,000 employees, and it shares its data with numerous third parties. 

Although it recently ended this practice, following the [Cambridge Analytica scandal](https://auth0.com/blog/what-data-did-facebook-really-give-cambridge-analytica/), Facebook historically shared user information with major online and offline data brokers through its Partner Categories program. This included what the company had collected itself (e.g., page likes) and information from its advertisers.

{% include tweet_quote.html quote_text="With so many stakeholders accessing different parts of the Facebook platform at different times, it's clearly too much for Facebook to keep track of Fake news, and accounts are rampant." %}

These providers helped other businesses understand and optimize their marketing campaigns. As an example, [according to Facebook](https://www.facebook.com/help/494750870625830):

"An auto dealer may want to customize an offer to people who are likely to be in the market for a new car. The dealer also might want to send offers, like discounts for service, to customers that have purchased a car from them. To do this, the auto dealer works with a third-party company to identify and reach those customers with the right offer. The third-party partner provides Facebook with information that helps Facebook connect those customers with the offers." 

With so many stakeholders accessing different parts of the Facebook platform at different times, it's clearly too much for Facebook to keep track of [Fake news](https://www.zuora.com/2017/05/26/social-platforms-channel-fake-news-next-revolution-journalism-2/) and accounts are rampant.

How can your team do better?

## Avoid Your Own Disinformation Scandal with Strong Identity Management Tools

Even if you’re not as large as Facebook, there are key steps you can take as your company scales to be sure you are keeping track of who your users are (customers, employees, and third parties) and what behaviors they display in order to root out fake accounts and nefarious activities.

### Identity management for your employees

As your team expands on multiple levels, across new geographies and time zones, following everyone working within your system can be a headache.

Pushing certain [Rules](https://auth0.com/learn/cloud-identity-access-management/) in the cloud, like blocking people or even entire groups from logging in on particular devices or at certain times, can help cut down on inefficient DIY tactics and organize access in a streamlined way.

If using Auth0's solutions, you can quickly pull [user-profile details](https://auth0.com/docs/user-profile/user-profile-details), including

* first name and last name;
* email address; and
* specific company identifiers, such as an employee number or a listed department name.

Given the range of data sources that this information could come from, including custom databases, an Active Directory, or even a social provider like LinkedIn, Auth0 will normalize this and return a basic set of data, with attributes like  `user_id`, `name`, `nickname`, and `picture`, to allow admins and programs to retrieve the information they need when double-checking employees.

Giving admins the control to rapidly parse an employee user base will help them notice any suspicious behaviors — like repeated failed login attempts in real-time — mitigating the risk of false accounts or system breaches.

### Identity management tools for third parties

For third parties such as consultants or auditors (or, in Facebook's case, purchase-data providers like Datalogix, Epsilon, Acxiom, and BlueKai) that you allow into your system but that are not regular employees, providing them with a single sign-on (SSO) feature through [Auth0 Universal Login](https://auth0.com/universal-login) will not only make things cleaner and more efficient on their end but also help consolidate all of their credentials into a single location for vetting purposes.

Auth0 Universal Login provides a secure login infrastructure to authenticate users to your apps.

![Auth0 Universal login page](https://cdn.auth0.com/blog/resources/auth0-centralized-login.jpg)

On the back end, after the authentication event occurs, admins can call the `getUserInfo` method to acquire all of the user's profile information (as needed).

Keeping track of external users is critical in maintaining order and privacy within your system as needed (as Facebook's canceled Partner Categories program highlighted). Because these users aren't formal employees, you want to be sure that they still adhere to your company's standards and practices and aren't straying or creating unwanted programs.

### Customer identity management tools

Knowing your customers is key to growing your company. Strong customer-identity and customer-access tools can make onboarding quick and fun, up your daily active-user base, reduce churn, and [drive conversions](https://blog.nomnominsights.com/turning-customer-feedback-into-research-hypotheses/).

It also helps you ensure that no one is masquerading as someone they're not.

This year, British shipping company Clarksons revealed that a single fake account was to blame for [stealing confidential information](https://www.zdnet.com/article/clarkson-says-single-user-account-to-blame-for-data-breach/). The account accessed corporate databases and made off with highly sensitive data, such as Social Security numbers, criminal convictions, medical information, tax and insurance details, signatures, and login credentials  — along with even more personal details, like ethnicity and religion.

To get out of the mess, Clarksons had to hire outside forensic help to find and disable the problematic account.

Implementing social integrations can help you avoid this by immediately double-checking that all users are who they say they are. A social login feature relies on existing login information from a social network provider like Google to verify a users identity.

![Log into a Wordpress site using social login provider](https://cdn.auth0.com/blog/facebook-scandal:auth0-wordpress.png)

A customer can sign into a third-party website like WordPress through Google instead of creating an entirely new account. Since the provider (Google) has already authenticated the user, it provides an extra layer of security.

Any further support you can get to vet users — even your loyal and trusted customers — can go a long way toward avoiding a costly data breach.

{% include tweet_quote.html quote_text="Creating or outsourcing tools like Auth0 Universal Login for rapidly pulling and storing current user data, and features like social login will help secure your company at its foundation so that you can grow." %}

## Use Identity Management Tools to Stop Bad Behavior at the Source 

As your company grows, it's a blessing to bring on more users — whether new customers, freelancers, consultants or employees. But it can quickly become a curse if you don't implement strong practices for monitoring them.

As the Facebook disinformation scandal clearly shows, without proper tracking, small issues can balloon out of control. Ideally, you'd stop any fake accounts at the login source so they don't snowball at all.

Creating or outsourcing tools like [Auth0 Universal Login](https://auth0.com/universal-login), [Rules for rapidly pulling and storing current user data](https://auth0.com/docs/rules/current), and features like [social login](https://auth0.com/learn/social-login/) will help secure your company at its foundation so that you can grow.
