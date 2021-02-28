---
layout: post
title: More Sign-ups!
date: 2019-06-25
author: tiara
beforetoc: Register process and behind the UX
duration: [1 week]
image: assets/images/signup_tobe.png
tag: [ux design, ux stratgy, ui design]
---

The moneystation team was building SNS service specialized in investment. In order to activate the community, we need more users. But many users just watching feed and not want to upload or share tips about their investments. We need influencers and audiences. The first step to increase the number of users, the team agree to work on signup process.

<!--more-->

1. Overview
2. What was the problem?
3. How I solved it?
4. What I’ve learned?

## 1. Overview

**Goal**

People barely know the service 'Moneystation'. I wanted to increase the number of registered users first. I insisted the team should work on the registration process before its too late. 

> I looked deeply into the registration process to make people can easily register and improve security at the same time. 

## 2. What was the problem?

Facebook account polish was changed and we were having issues with using facebook account login to the service from time to time. Plus, the user of the service doesn't use facebook. The most used SNS service among the user is 'Naver' which is the famous Korean portal service. But we couldn't use Naver login because of the clecification of the service in certificate. What if facebook or google don't have a business anymore in Korea like yahoo stops their service? Well obviously using Google or facebook for sign-in is really easy for users. So here our concerns started.

> We put Facebook and Google connection to enhance the registration process for the user but it was not that helpful for them. 

In addition, there are few more issues it may arise.

![As-is screen of 'Sign-up'](/assets/images/signup_asis.png) 

1) The contrast of the text and the background was less than 1:4.5.

2) There were no clues of validity. 

---

## 3. How I solved it? 

### 1) Benchmarks


![Signup for other services](/assets/images/signup_reference.png)

I did sign-up for Linkedin, Twitter, Facebook, Instagram, Reddit, Quora, Naver, Kakao, Pinterest, Weheartit and more.  Many of them use an email address and some Korean services are using phone numbers for the primary information they keep.  Even they don't link to the major SNS services at the beginning, users of Linkedin, Instagram and others can connect with Google or Facebook account after they signed-up.

The service should ask the least information of the users by the law. However, service providers want to know as many information about their users as possible. With the information they gathered, we can make a new feature, use their personal contact information for marketing purposes and make a profit. Because of that security issues are becoming issues these days. 

At this stage of the service, we can't put resources on security or data handling. So we decided to erase the connection of facebook or google and just collect the email address and a name for the users. 



### 2) Questions

1. How many steps of the process; Single-step or multi-step process, has the highest conversion rate?
2. Do we have to open the service for the none registered users as well?
3. Do we need a verification process?
4. What are the best practices for the passwords?
5. How can we achieve the easiness and high security at the same time?



![wireframes: Left one for a single-step, Right one for multi-steps](/assets/images/signup_wireframes.png)

Left one is for a single step one and the right one is for multi-steps one.



### 3) Decisions

1. **How many steps of the process- Single-step or multi-step process has the highest conversion rate?**  

   [Single step form VS. Multi step form which one is the best and why] https://wpmanageninja.com/single-step-form-vs-multi-step-form-which-one-is-the-best-and-why/

   > According to the findings of these researches, we decided to change our process into a multi-step process.

2. **Do we have to open the service for the none registered users as well?**

   This is based on the direction we would like to take. We chose it to be open, anonymous.

   Our team members had a long discussion about this. I wanted to be closed with good quality of information so that makes people join the service like LinkedIn or facebook. However, I couldn't find any evidence for that premise. 

   Other team members believed that we are a challenger and people need to know our name and the service. If we keep our service solely for the members, it would be hard to gather users. 

   > We decided to keep the service open for anyone and reduced the modal windows reminding users to sign-in. 

3. **Do we need a verification process?**

   With the help of the verification process, we can ask less to the users. Not just ask less but also improve security. The boss was too anxious to do that. Cause it means one more huddle in the registration process. He worried that during that verification, many users will not return. At that point, I understood that high conversion rate is the most priority and security is the second. 

   > We agreed that we need many users as possible. So at this stage, we are not working on a verification process. Maybe we will have it when the service has good enough users...

4. **What are the best practices for the passwords?**

   This is regarding the minimum number of the characters you need to sign-in for the service. Besides, there were so many options we could make. Do we need Special characters? Do we need numbers in the passwords? What about Capital letters? Will you allow it? Will you make it as compulsory? 

   I researched many articles about passwords and security and find out that two or more combination is good enough and the strength of security is depending on its length. The longer, the stronger passwords.

   The thing is when the passwords are getting longer, it is easier to forget. It is known as a golden rule for UX designers that the magic number is Seven. This idea was put forward by Miller(1956). [1^:https://www.simplypsychology.org/short-term-memory.html]

   > "The magical number Seven, Plus or Minus two: Some Limits on our capacity for processing information." is one of the most highly vited papers in psychology.

5. **How can we achieve the easiness and high security at the same time?**

   At first, I didn't mention it and after the development process was done and checked for Quality Assurance, I was speechless. The developer blocked the function. He said that the function can lead to a high risk of leaking personal information. Because people easily forget to sign out after using the service and they are using the service everywhere. He was right but we can fix that issue by using verification email or encourage users to change their passwords every six months. Our passwords policy encourage users to make their passwords long and it is easy to forget. If they use the device they can trust, we can make it easier by providing the options to remember the account information. In that way, we can achieve security and usability at the same time. 

   > Thanks to the chrome browser and others. I convinced the deveoloper to allow 'password manager' to remember account information. 

![Tobe](/assets/images/signup_tobe.png)

![signup_ tobe_multistep](/assets/images/signup_multi-steptobe.png)


## 4. What I've learned.

I didn't know that this is a huge project. There are so many things to consider. Register process was related to every aspect of the service. 

The characteristic of the service is decided by the accounts policy. Make it easy as possible but you need to take care of the security at the same time was not an easy thing to do.

If the sign-up process is too hard to do, people leave the service.  The information you ask should be related to the service. We can use the information for better marketing and curation of the service.

The length of the User ID depends on the UI you chose. It can be shown from on the Card which recommends other users to an account page of users'.  It was a quite challenging but fun project for me. It was possible because the service is at its early stage. I appreciate that I could have a chance to be involved.
