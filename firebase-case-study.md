---
title: Firebase Case Study
keywords: development platforms, Firebase, hosting service, cloud
tags: Development Platforms, Firebase, Hosting service
sidebar: development-platforms
permalink: development-platforms/firebase-case-study.md
folder: development-platforms
---


## Introduction

Google firebase is one of the most popular development platforms, and is an own ecosystem with multiple key features. It can be used in multiple stages of a project, as the backend of an website, or used to analyse you website.

One reason for learning more about this product, is that all the services can be set up with ease. With little setup required to get started.

## Brief History

- Founded in 2012 by James Tamplin and Andrew Lee, with one product: Realtime Database. 

- In 2014 They released the product Firebase Hosting and Firebase Authentication. Firebase Hosting is an Web hosting service for static websites. Firebase Authentication is a service for registering, login and authorizing users trough diffrent third party login options.
Later that year they got bought up by Google. 

- In 2017 they bought two services from twitter, Fabric and Crashlytics. Crashlytics is an tool for reporting crashes in realtime. Fabric is an analytics tool for monitoring stability and user behaviour. Later that year they introduced firestore, a noSql database. 

- By 2023 they are one of three major cloud service / development platforms, with the other being AWS and Microsoft Azure.

## Features

### Firebase Authentication
An authentication service capable of registering users from multiple third-party login methods, as well as email or phone login. Multifactor authentication is also a feature they offer. With this, there is also support for login and a built-in email service for resetting passwords. 
### Firebase Firestore
A Scalable NoSQL database. it's a Realtime database that is set up by multiple documents in a collection, where each document has data. It is easy to set up and use,  Firestore is as with most other firebase services available on multiple Programming SDKs for example Python, Node.js, and C++. For example, in Node.js there is A npm package you can download (that includes the entirety of firebase), this will give you easy access to commands you can integrate with your API.
### Firebase admin panel / console
Most / all services have some kind of usage monitoring for each service, here you can monitor all calls to for example Firestore, and how many reads/writes there are. If you have a website or app, you can integrate the performance service, and an SDK to monitor speed and user experience. Alongside this, you can use firebase analytics(almost the same as google analytics) to monitor user demographic and activity( note that there is a lot of uncertainty around google analytics at this time).
### Firebase Functions
A cloud function for running Backend node.js, can be used to create functions for your application, and communicate directly with the rest of the firebase ecosystem. It can be run easily on node.js express using the onrequest method. (this feature is only available for the paid plan) 
## Strengths

### All in one service
An all-in-one service, capable of giving you most of the features you need, without having to opt for multiple different products that might increase cost and be difficult to integrate.
### Easy to use
Easy to use and set up, with SDK for many different programming languages. The setup usually consists of some small steps.
### Good pricing
Good pricing options, with high limits on the free version, as well as a pay-as-you-go plan that includes the free version. The prices are also competitive against other services, with some features being cheaper than competitors.
## Weaknesses

### SDK Limitations
Although most of the firebase is easy to use, some things are significantly harder to use or setup, you might start using the firebase SDK to build your backend, and everything is going well, but then you find out that there is a need for the admin SDK to some certain things. To give one example: the firebase authentication is very easy to use with the regular firebase SDK, but it is focused on single users, so if you have a website where you can check other’s people profile, you may need to use the admin SDK or store user information in a Firestore database as well.
### Setup Limitations
While Firebase has many different Features, Some of them are not as Customizable as other services offer. Since it is quick and easy to set up most features, it limits the options you can set for them, giving you more work later. using Firebase Authentication as an example again, you can not set password requirements directly in firebase, you have to either use your own validation or a third party, the base firebase Authentication requirement is a 6-letter password.

## Comparison
I will compare Firebase with one of the other big market holders: Amazon Web Services (AWS).

### Products offered
AWS Offers around 200 products, while Firebase have around 20. This means that AWS offers alot more than Firebase.
There is some products that are similar to each others, Firebase Authentication and AWS Cognito, Firebase firestore and AWS dynamodb.
There a lot more database options in AWS, such as relational databases, Something that firebase does not have. 
### price
Firebase only has two pricing categories, free and pay-as-you-go.
Aws has some good free options, free trials, 12 months free, and always free. The free trials differ between use time and trial period, where after the trial is done, you go over to the pay-as-you-go plan. 
12 months free is a new user offer they have, where you can use the products until your trial has ended, and go over to the pay-as-you-go plan. 
    
Comparing Firebase Authentication and AWS Cognito:
| Firebase Authentication  | MAU* |
| :------------ |:---------------:| 
|  0 - 49,999 | 0 |              
| 50,000 - 99,999 | $0.0055 |
| 100,000 - 999,999| $0.0046 |
| 1,000,000 - 9,999,999 | $0.0032 |
| 10,000,000 + | $0.0025 |


| AWS Cognito | MAU* |
| :------------ |:---------------:|
|0 - 50,000 | 0 |
|  50,001 - 100,000 | $0.0055 |
| 100,001 - 1,000,000| $0.0046 |
| 1,000,001 - 10,000,000 | $0.00325 |
| 10,000,000 + | $0.0025 |

*Monthly Active Users

in this example the cost is the same, so for some of their products, there is more reason to look at features and availability instead of pricing, although this does not apply to every feature.

### Usability
I do not have too much experience with AWS, but after looking at the admin panel/console panel it looks a bit more professional than firebase. The firebase console looks clean and modern. When it comes to setup, for firebase the setup is usually a few steps, while on AWS there sometimes were A LOT of steps to finish, although they were useful steps, with much more freedom to configure than in firebase. Making firebase more simple, and AWS more flexible.

Comparing the documentation, AWS looks much more professional, while firebase looks more user-friendly and easy to use. Both have great explanations and examples for their products, and they both have sdks for many different programming languages. 

So if you are wondering which of the services you should pick, it depends on what you want to focus on, if you want an easy-to-use service, firebase might be the one. If you need many different services for your product, AWS has a lot to offer, but demands more setup and learning about how to use it. 

## Summary
Google Firebase is a great service, with easy-to-use services and good documentation. Their SDK makes it easy to 
integrate their service into your app or website, in many ways such as directly through their SDK, or creating your own 
backend service to customize things like error messages.  

Their pricing makes it appealing to try it out, without using any money, and have competitive pricing in the market. 
By using Firebase you can remove the complexity of setting up your databases and login systems for your website, 	giving more time to design. Having all these features on one provider will also minimize the setup of multiple different services. 

### Credits

- Benik kvam (Puggen1)

#### References

- [Firebase Pricing](https://firebase.google.com/pricing)
- [AWS Cognito](https://aws.amazon.com/cognito/pricing/) 
- [Firebase Docs](https://firebase.google.com/docs)
- [Firebase Wikipedia](https://en.wikipedia.org/wiki/Firebase)
