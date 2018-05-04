---
layout: page
title: Code
permalink: /code/
---

[github.com/aaronschachter](https://github.com/aaronschachter)

I've been the tech lead of the [DoSomething.org chatbot](https://github.com/dosomething/gambit-conversations) for the past 2+ years, responsible for:

* Architecting and implementing the chatbot CMS and API for integrating with internal DoSomething APIs (users, campaigns, and user campaign activity) and external APIs (Twilio & Slack for sending and receiving user messages, Contentful for chatbot content)

    * Building in Node.js, MongoDB, and [Rivescript](https://www.rivescript.com/)

    * Creating [technical specifications and documentation](#technical-writing) in Google docs, Lucidchart

* Building out an internal [web admin dashboard](https://github.com/dosomething/gambit-admin) in React

In reverse order, here are some other notable work projects I've led engineering for:

* [DoSomething.org iOS app](https://github.com/dosomethingarchive/letsdothis-ios) -- A hybrid Objective C and React Native iOS app for integrating with internal DS user, campaign, and campaign activity API's. Also built a news feed CMS and API with WordPress for mobile app consumption.

    * Note: the DoSomething apps are no longer available in the Apple or Google App Stores.

* [SMART Recovery iOS app](https://itunes.apple.com/us/app/smart-recovery-cost-benefit-analysis/id988593978?mt=8) -- I took a one month sabbatical while at DoSomething.org to volunteer at [SMART Recovery](https://www.smartrecovery.org/), designing and implementing an iOS version of a paper worksheet used for addiction recovery.

* [Phoenix](https://github.com/dosomething/phoenix) - A DoSomething.org PHP/MySQL Drupal 7 application that we now consider "the monolith". I architected and developed the backend for the Campaign and Campaign Activity components of the DoSomething platform from scratch, after reviewing and maintaing the legacy platform inherited from a third-party agency.


## Technical writing

Here some a few links to DoSomething docs I've written:

* [Documentation: Chatbot campaign message templates](https://github.com/dosomething/gambit-admin/wiki/Campaigns) -- Editors' guide to configuring chatbot campaigns to collect various types of user activity (some campaigns require users to submit a photo, others may simply require a text answer to a question)

* [Technical spec: Automating chatbot campaign completion reminders with Customer.io](https://docs.google.com/document/d/1b3WFeH9gcPlnshKEOLgO001emzp-k_kBz7NQ3ivzjtM/edit?usp=sharing) -- Sending automated messages to DoSomething users to remind them to complete volunteer campaigns they have signed up for via chatbot


* [Technical spec: supporting multiple chatbot campaign conversation types](https://docs.google.com/document/d/1VjpgRTeVakbbSr1WwkR4tEjXiiVZ9i1bAEkNInsWQrk/edit) -- Implementing the chatbot campaign templates in Contentful and exposing via chatbot API

### Flowcharts

* [Chatbot API](https://github.com/dosomething/gambit-conversations/wiki) - points of entry for chatbot conversations, with integrations per route

<a href="https://user-images.githubusercontent.com/1236811/39599894-f403295c-4ed1-11e8-8119-cb083eb7aabf.jpeg"><img src="https://user-images.githubusercontent.com/1236811/39599894-f403295c-4ed1-11e8-8119-cb083eb7aabf.jpeg"></a>

* [Chatbot replies](https://github.com/dosomething/gambit-conversations/wiki#member-messages) - how the chatbot replies, with related integrations

<a href="https://user-images.githubusercontent.com/1236811/39645960-bf6256f6-4f8e-11e8-8605-0546cbf740d5.jpeg"><img src="https://user-images.githubusercontent.com/1236811/39645960-bf6256f6-4f8e-11e8-8605-0546cbf740d5.jpeg"></a>

