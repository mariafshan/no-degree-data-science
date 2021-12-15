# Week 2: Data Science Topics
https://www.coursera.org/learn/what-is-datascience/home/week/2

In this module, you will hear from Norman White, the Faculty Director of the Stern Centre for Research Computing at New York University, as he talks about data science and the skills required for anyone interested in pursuing a career in this field. He also advises those looking to start a career in data science. Finally, you will complete reading assignments to learn about the process of mining a given dataset and about regression analysis.

### Learning Objectives
1. Define Big Data and its distinguishing characteristics, such as, Velocity, Volume, Veracity, and Value.
2. Describe how Hadoop and other big data tools, combined with distributed computing power, are triggering digital transformation.
3. List some of the skills required to be a data scientist and analyze big data.
4. Explain what data mining is and the steps required to mine a given a dataset.
5. Explain the difference between common data science terms, including deep learning and machine learning.
6. Describe regression and some of its applications.
7. Describe how to apply the Data Understanding and Data Preparation stages of the methodology to a data science problem.

# Big Data and Data Mining
# 2.1. Foundations of Big Data
https://www.coursera.org/learn/what-is-datascience/lecture/dxcNH/foundations-of-big-data

In this digital world, everyone leaves a trace. From our travel habits to our workouts and entertainment, the increasing number of internet connected devices that we interact with on a daily basis record vast amounts of data about us.

There’s even a name for it: **Big Data**.

#### Ernst and Young Definition
> Big Data refers to the dynamic, large and disparate volumes of data being created by people, tools, and machines. It requires new, innovative, and scalable technology to collect, host, and analytically process the vast amount of data gathered in order to derive real-time business insights that relate to consumers, risk, profit, performance, productivity management, and enhanced shareholder value.

### The V's of Big Data
There is no one definition of Big Data, but there are certain elements that are common across the different definitions, such as:
1. Velocity
2. Volume
3. Variety
4. Veracity
5. Value 

#### Velocity
Velocity is the **speed** at which data accumulates. Data is being generated extremely fast, in a process that never stops. Near or real-time streaming, local, and cloud-based technologies can process information very quickly.

#### Volume
Volume is the **scale** of the data, or the increase in the amount of data stored.

Drivers:
1. The increase in data sources
2. Higher resolution sensors
3. Scalable infrastructure

#### Variety
Variety is the **diversity** of the data.

Structured data fits neatly into rows and columns. In relational databases while unstructured data is not organized in a pre-defined way, like Tweets, blog posts, pictures, numbers, and video, variety also reflects that data comes from different sources, machines, people, and processes, both internal and external to organizations.

Drivers:
1. Mobile technologies
2. Social media
3. Wearable technologies
4. Geo technologies
5. Video
6. Etc.

#### Veracity
Veracity is the **quality** and **origin** of data, and its conformity to **facts** and **accuracy**.

Attributes:
1. Consistency
2. Completeness
3. Integrity
4. Ambiguity

Drivers:
1. Cost
2. The need for traceability

With the large amount of data available, the debate rages on about the accuracy of data in the digital age. Is the information real, or is it false?

#### Value
Value is our ability and need to turn data into value.

Value isn't just profit. It may have medical or social benefits, as well as customer, employee, or personal satisfaction. The main reason that people invest time to understand Big Data is to derive value from it.

### The V's in Action.
#### Velocity
Every 60 seconds, hours of footage are uploaded to YouTube which is generating data. Think about how quickly data accumulates over hours, days, and years.

#### Volume
The world population is approximately seven billion people and the vast majority are now using digital devices; mobile phones, desktop and laptop computers, wearable devices, and so on. These devices all generate, capture, and store data -- approximately 2.5 quintillion bytes every day. That's the equivalent of 10 million Blu-ray DVD's.

#### Variety
Let's think about the different types of data; text, pictures, film, sound, health data from wearable devices, and many different types of data from devices connected to the Internet of Things.

#### Veracity
80% of data is considered to be unstructured and we must devise ways to produce **reliable** and **accurate** insights. The data must be **categorized**, **analyzed**, and **visualized**.

### Data Analysis Tools
Data Scientists today derive insights from Big Data and cope with the challenges that these massive data sets present. The scale of the data being collected means that it’s not feasible to use conventional data analysis tools.

However, alternative tools that leverage distributed computing power can overcome this problem. Tools such as **Apache Spark**, **Hadoop** and its ecosystem provide ways to **extract**, **load**, **analyze**, and **process** the data across distributed compute resources, providing **new insights** and **knowledge**. This gives organizations more ways to connect with their customers and enrich the services they offer.

So next time you strap on your smartwatch, unlock your smartphone, or track your workout, remember your data is starting a journey that might take it all the way around the world, through big data analysis, and back to you.

# 2.2. What is Hadoop?
https://www.coursera.org/learn/what-is-datascience/lecture/kbyiw/what-is-hadoop

#### Norman White, Clinical Professor of CMS, Faculty Director, Ressearch Computing, New York University, Stern

According to Dr. White, most of the components of data science, such as probability, statistics, linear algebra, and programming, have been around for many decades but now we have the computational capabilities to apply combine them and come up with new techniques and learning algorithms.

### What is Hadooop?
> Traditionally in computation and processing data we would bring the data to the computer. You'd wanna program and you'd bring the data into the program. In a big data cluster what Larry Page and Sergey Brin came up with is very pretty simple is they took the data and they sliced it into pieces and they distributed each and they replicated each piece or triplicated each piece and they would send it the pieces of these files to thousands of computers first it was hundreds but then now it's thousands now it's tens of thousands. And then they would send the same program to all these computers in the cluster. And each computer would run the program on its little piece of the file and send the results back. The results would then be sorted and those results would
then be redistributed back to another process.

> The first process is called a map or a mapper process and the second one was called a reduce process. Fairly simple concepts but turned out that you could do lots and lots of different kinds of handle lots and lots of different kinds of problems and very, very, very large data sets.

> So the one thing that's nice about these big data clusters is they scale linearly. You had twice as many servers and you get twice the performance and you can handle twice the amount of data. So this was just broke a bottleneck for all the major social media companies.

> Yahoo then got on board. Yahoo hired someone named Doug Cutting who had been working on a clone or a copy of the Google big data architecture and now that's called Hadoop. And if you google Hadoop you'll see that it's now a very popular term and there are many, many, many if you look at the big data ecology there are hundreds of thousands of companies out there that have some kind of footprint in the big data world.

### How does data science differ from traditional subjects like statistics?
> Most of the components of data science have been around for many, many, many, many decades. But they're all coming together now with some new nuances I guess.

Fundamentals of data science:
1. Probability
2. Statistics
3. Algebra
4. Linear algebra
5. Programming
6. Databases.

> They've all been here. But what's happened now is we now have the computational capabilities to apply some new techniques - **machine learning**. Where now we can take **really large data sets** and instead of taking a sample and trying to test some hypothesis we can take really, really large data sets and look for patterns.

> So back off one level from hypothesis testing to finding patterns that maybe will generate hypotheses.

> Now this can bother some very traditional statisticians and gets them really annoyed sometimes that you know you're supposed to have a hypothesis that is not that is independent of the data and then you test it.

> So, once some of these machine learning techniques started were really the only thing the only way you can analyze some of these really large social media data sets. So what we've seen is that the combination of traditional [technique] areas computer science probability, statistics, mathematics all coming together in this thing that we call **Decision Sciences**.

> Our department at Stern I'll give a little plug here we happen to have been very well situated among business schools because we're one of the few business schools that has a real statistics department with real PhD level statisticians in it. We have an operations management department and an information systems department. So we have a wide range of computer scientists to statisticians, to operations researchers. And so we were like perfectly positioned as a couple of other business schools were to jump on this bandwagon and say; okay this is Decision Sciences. And Foster Provost who's in my department was the first director of the NYU Center for Data Science.

### Do you recal a time when no one spoke about data science?
> Four years ago maybe five years ago.

> I mean, I feel this is one of those cases where you can just to Google and search for data science and see how often it occurred and you'll see almost nothing and then just a spike. The same thing you would see with big data about seven or eight years ago. So data science is a term I haven't heard of probably five years ago.

### What did you think when you first heard the term 'data science'?
> The first question is what is it? And I think faculty and everybody is still trying to get their hands around exactly what is business analytics and what is data science. We certainly know the components of it. But it's morphing and changing and growing. I mean the last three years deep learning has just been added into the mix. Neural networks have been around for 20 or 30 years. 20 years ago, I would teach neural networks in a class and you really couldn't do very much with them. And now some researchers have come up with multi-layer neural networks in Toronto in particular the University of Toronto. And that technology is now rapidly expanding it's being used by Google, by Facebook, by lots of companies.


# Deep Learning and Machine Learning


# Hands-on Exercise: Data Science Exploration

# Lesson Summary
https://www.coursera.org/learn/what-is-datascience/supplement/aixTi/lesson-summary

https://www.coursera.org/learn/what-is-datascience/supplement/AVdmh/lesson-summary

In this lesson, you have learned:
1. Data science is the study of large quantities of data, which can reveal insights that help organizations make strategic choices.
2. There are  many paths to a career in data science; most, but not all, involve a little math, a little science, and a lot of curiosity about data.
3. New data scientists need to be curious, judgemental and argumentative.
4. Why data science is considered the sexiest job in the 21st century, paying high salaries for skilled workers.
5. The typical work day for a Data Scientist varies depending on what type of project they are working on.
6. Many algorithms are used to bring out insights from data. 
7. Accessing algorithms, tools, and data through the Cloud enables Data Scientists to stay up-to-date and collaborate easily.
