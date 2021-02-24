---
layout: post
title: "Programming Advice"
date: 2020-07-18
updated: 2021-02-24
category: mind
---

Below is the transcript of a textversation I had with my brother.

#### Bro
If I wanted to take a course online for app development or similar, what would you recommend? There are so many websites and each website has a billion courses with so many different specialties/languages and such

#### Me
Ha! What are you looking to do? My recommendation would be based on that...

The biggest question is whether you want to do cross-platform. If you just care about iOS then I recommend learning Swift and raywenderlich.com has been the leader in iOS learning for a while. If you want to do Android + iOS it's best to use something like Dart/Flutter or ReactNative so you don't have to duplicate everything in Objective-C/Swift for iOS and Java for Android. I can give you a recommendation but don't want to send too much unnecessary info at once :)

And also note that if you want to make an iOS app, you're going to have to have a Mac of some sort.

#### Bro
Oh dang so even if I would want to do cross-platform I would need a Mac?

#### Me
Yeah, people always accuse Microsoft of monopolies but Apple has the biggest one. You simply cannot make an iOS app without a Mac because no matter what cross-platform system you use, you still need Xcode to compile the actual .ipa file that is the app. There are apparently some services that host macOS Server that will compile your code for you but it's an additional cost, lots of setup, and difficult to debug especially in the beginning. You will also need an Apple Developer License which is $99/year. (A Google Play license is a one-time $25 fee.) I kind of wanted to get a better idea of what you wanted to do because I think apps are on their way out. Most people use ~5 apps most of the time and downloads are way down because mobile sites fulfill the job for the most part. The advantages of an app are: push notifications, contacts access, and camera access so if you need any of those you can't have just a mobile site. Otherwise, I recommend the web. If you're interested, someone on our team recently posted this article which I've only skimmed but have agreed with the headline for years: <https://medium.com/s/story/mobile-apps-will-disappear-soon-4b4e54f46eb8>

#### Bro
Oh this is great stuff to know. I really just wanted to keep up skills and do a project or something to be able to show future employers that I was keeping things up. So I thought an app would be a nice little packaged product to be able to show a potential employer. But definitely not what I was set on so this definitely steers me away from that. I'm thinking then that I might just want to learn more about web development (with more heavy on the front end while still keeping up full stack skills). Any good recommendations for that?

#### Me
Yeah, I actually gave my interns some recommendations so I'll email that to you. React is a super popular frontend framework right now and even though [my System Architecht] & I don't like it, it could be another good skill to have because it seems everyone is using it now.

#### Bro
Great thanks so much! And maybe it would be too long over a text but why don't you guys like react?

#### Me
Just sent the email. React has a lot of bloat and they have their own language called JSX. People have built so many packages on top of it just to deal with its problems, so now it's not just React, it's React + Redux + a bunch of other tools I can't keep up with. Vue.js is similar to react but much simpler so if you're going in that vein, I recommend it instead, even if it's slightly less popular (but growing because of React's bloat). [My System Architect] & I just love Knockout because of it's super simplicity.

#### Bro
Gotcha! Thanks so much this was all so insightful and helpful!

#### Me
I'm so glad! I just emailed a summary of recommendations :)

#### Summary that was emailed:

1. Come up with something useful to make. Nothing motivates you to learn like having a goal. It's better than any tutorial because those are somewhat in the abstract (albeit necessary to begin) but when you have an actual problem to solve that's when you really learn. Also, if the end result is good then the technologies you used to build it are less important. It's better to show you can build something great than use all the in-vogue technologies with a disappointing end-result.

2. Build it out in Node.js or whatever other backend solution you prefer (Python, Ruby, etc.), Bootstrap 4, jQuery, and Vue/React/Knockout. For a database, you can choose what you want but I recommend Postgres (you can run this on AWS RDS; see the next step).

3. Get a basic AWS account and host it there so people can preview it. This will also show you have at least some skills in DevOps. You probably will just need S3 for hosting frontend files, Route 53 for getting a domain/managing DNS, and Elastic Beanstalk (https://aws.amazon.com/elasticbeanstalk) + RDS for something basic on the backend. It shouldn't cost too much.

You could go crazy and set up Docker but that's overkill and I think containerization is stupid anyway. I much prefer a serverless approach like AWS Lambda to containers and if you're interested in that then this project has always been cool to me: https://www.serverless.com. I started building something basic with it + GraphQL but that was before I joined [my current company]. But I highly recommend you don't go down these rabbit holes until you've completed at least one project with the first 3 steps I outlined...this could be for your next project :)
