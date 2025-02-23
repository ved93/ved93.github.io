---
toc: true
# hide: true
layout: post
description:  
tags: [career, learning]
title: The role of engineering skills in data science
date:   2023-08-29 14:21:36 +0530
---

I still remember the day when an interviewer was interacting with candidates in the college before the interview process.
He asked, "Why do you want to do data science"?
One candidate replied, "Because it doesn't require programming".

The interviewer paused for a moment, and then replied, "If you think you don't need to code, then you should not apply".

In data science, people come from different disciplines. Some are from computer science, some are from statistics, some are from mathematics, some are from economics, some are from business, and some are from other fields.
Most data scientists do not have a programming background. So, data scientists have a reputation for writing bad codes. I have committed this crime. I always wanted to write good code, but I did not know what is the good code. I used to discuss with my friend how could I organize my data-science workflow effectively. I started exploring the GitHub repos. Then I worked on a production system and there was never looking back. I started investing more in learning the software engineering part. I still remember the first PR I submitted for production code, I had to do 3-4 iterations as the quality of the code was not up to the mark and was not adhering to the repo standard. Since then, I improved a lot and always thinking about how can we make it better and manageable.

Now I have come to believe,  
*"To be an efficient data scientist you need to have good software engineering skills"*

Writing quality code and having a software engineering mindset enables you to work efficiently. I am not sayiing that People who just do .fit and .predict are not going to be great data scientists, but surely you are going to be highly inefficient. If you know how to build machine learning-powered systems, you will be in a great position.

I have seen places where the data science team depends on engineering teams to productionize their models. IMO, This is not a good scalable practice.

Why is it not a good practice?

## 1. Slow down the iteration speed

The data science team is not able to iterate fast. You will always be dependent on the engineering team to productionize your models. This will slow down your iteration speed. I have experienced this and other data scientists echo this. I worked in a search team where we had complete authority on productionazing our models. We were able to iterate fast and productionize our models. We were able to do A/B testing and see the results. It became easier to convince the stakeholders on whatever we were doing. 
I also worked in another setup where we had a dependency on the engineering team to productionize anything. Countless hours were spent on prioritizing and communicating with the production team. We were not able to iterate fast. The engineering team spent days understanding the code and then productionize it. Then they also recommend the changes to accommodate the production system. This was a very slow process.

## 2. Lack of a complete picture of the system

As a data scientist, you will never understand the production systems. You will never know how your model is being used. If they are using the wrong way then your project will not yield the desired results. Many a time, it will happen that due to a bug in the production system, your model is not working as expected. The engineering team might not debug deeply as their success does not depend on your success. Understanding the production system will help you debug the issues and make your model more robust. i.e. once I worked on search systems where I was expecting a variable to be boolean, but it was a string. People blamed the model as predictions are not good. I debugged the production system end to end and found the issue. I was able to fix it and my model started working as expected. If I was dependent on the engineering system for deployment, I would have never been able to debug the issue. The model would have been declared as bad model.

## 3. Lack of ownership

If you rely on the engineering team for productionizing your models, then it also means that your team doesn't have ownership of that product or system. i.e. product and engineering teams are usually coupled. The product team will decide what to build, and the engineering team will build it. Here engineering team will have ownership of the product. If the product team has to build something they have to convince and work along with the engineering team. Now, data science teams are different. They first need to convince the product team or business team to use their model. Then they need to convince the engineering team to productionize their model. IMO, this model can work if the data science team is placed strategically. i.e. product team understands the importance of data science teams in their work and their success depends on the data science. i.e. search teams, personalization teams etc are good examples. These product teams can't function well without data science elements. If this is not the case, then you will depend on the product or business team to use your model. If you convince them, then the product team has to align with the engineering team to productionize your model. This is a very slow process. Unless you are changing the way things work, it will be a hard journey. 
Now the other way, you know how to productionize models, build a quick prototype and show it to the product team or business team. If they like it, then you can productionize it without depending on the engineering team.


## Engineering skills are not only about the productionizing models

I have highlighted the problems if you don't have software engineering skills. 
The way the industry is moving, data science is becoming commoditized. It has become easy to build models. The software engineers are in a great position to leverage it. As hiring good ML engineers is becoming expensive, software engineers are learning ML skills. They are able to build ML-powered systems. They are also in the best place to use ML as they already have a system running in production. They can easily integrate ML to improve their system. i.e. a backend team that owns the onboarding flow of customers can integrate ML to process documents faster. Another backend team that owns the customer support ticket system can integrate prioritizing tickets using ML. The list is endless.

As a data scientist, you are working on problems that have uncertain outcomes.
Your model is useless if it is not used by the end users. If you think your job is just not building models but machine learning-powered systems, then you will have better visibility in the company. You will have a tangible output. Deploying something is very deterministic problem. Any failed experiment is better than no experiment. 
Although, I emphasized on production systems, learning software engineering skills goes beyond than that. It will help you in your day-to-day work. It will help in making your data science workflow more automd robust. You will start seeing the changes once you start learning it. You will become more productive in your work.

## Final thoughts

Although I highlighted that data scientists should be self-sufficient but it does not mean that they should do everything unnecessarily. It would be better if you have better tools for stuff like infra for deployment, monitoring, etc. You should not be spending time on these things. Just like engineering teams need these tools, data scientists should also depend on these tools for better productivity.

From a career perspective, learning software engineering skills are worth it. It will open more doors of opportunities.
To be honest, its not really that hard to learn software engineering skills. A data scientist is a software engineer first. Start from this perspective. You will be able to learn it faster. Start learning about how to create APIs and then deploy them on the cloud. Once you do that, you will get confidence. With time, you will get better and better. You will start seeing the changes in your work. Finally, you will be able to build machine learning-powered systems not just ML models. I hope I made a good case for learning software engineering skills. 
