---
layout: post
title:  "Web Scraping"
date:   2022-10-21
author: Austin Carter
description: Beginning the process of scraping disc golf stats  
image: /assets/images/BlogImage3.jpg
---
**Introduction**

Sports Science is one of my favorite subjects to study on my own time. During the past eight years I’ve spent countless hours researching how to be the best athlete I can be. I used this information to help myself and others, specifically my wife, have successful athletic careers at the high school and collegiate levels. But now that part of my life is coming to an end. Going into this year I’ve been worried about leaving all of that behind. Luckily, I found a new hobby. Disc Golf! I'm excited to apply my passion for sports science to Disc Golf and to have the oppurtunity to share this process with others. 

**Getting Started**

Most of the time getting started is the hardest part of any project for me, and this is especially true with this one. There are many different aspects of disc golf that I could explore through data. To keep it simple I decided to start out by exploring the difference in the Mixed(MPO) and Female(FO) divisions. This topic will help broaden my understanding of how the professonal scene in Disc Golf works. I'm hoping the knowledge I gain for this project will branch into more insightful future projects. Now that I have an idea, it’s time to get the data. 
  
 **Gathering Data**
 
Gathering Data is going to be different for every project. I can't give a step-by-step process of how to gather data for every project, but I can give insights on how to approach gathering data and show some of my work. First, let’s talk about choosing a source of data. When choosing a source, you are going to want to check for two things. The validity of the data and whether is accessible to you. Luckily for me my source, statmando.com, checks off these boxes. Now that we have a source for the data, we need to figure out how to extract it. Again, this is going to be different for every project, but for mine I am just going to be using pythons BeautifulSoup package to scrape data. Here is a quick rundown of how my process went.
  
![Test Image](https://raw.githubusercontent.com/austinC58/stat386-projects/main/assets/images/WebScraping7.png)

  
**Step 1: Set up Packages and URLs**

![Test Image](https://raw.githubusercontent.com/austinC58/stat386-projects/main/assets/images/WebScraping1.jpg)

**Step 2: Extract Data**

![Test Image](https://raw.githubusercontent.com/austinC58/stat386-projects/main/assets/images/WebScraping2.jpg)

**Step 3: Format Data**

![Test Image](https://raw.githubusercontent.com/austinC58/stat386-projects/main/assets/images/WebScraping3.jpg)
![Test Image](https://raw.githubusercontent.com/austinC58/stat386-projects/main/assets/images/WebScraping4.jpg)
![Test Image](https://raw.githubusercontent.com/austinC58/stat386-projects/main/assets/images/WebScraping5.jpg)

**Step 4: Export Data**

![Test Image](https://raw.githubusercontent.com/austinC58/stat386-projects/main/assets/images/WebScraping6.jpg)

**Ethics of Collecting Data**

A question you may have during this process is how ethical is web scraping? First, web scraping is completely legal if you are scraping publicly available data. So, the legality is pretty clear and simple, but what about the morality of scaping data? This is much more of a grey area and depends on the situation. One way to check if a website is ok with you scraping it is using robots.txt. You can just it to the end of your websites URL. Doing this for Statmando shows that they are ok with me using their data. One final aspect that is worth looking into is how you plan n on using the data. If you are planning to use the data for harm or to undermine the source itself, then it’s probably not the most ethical thing to do. But if your using the data for an ethical analysis, like my Disc Golf project, then you should be more than ok.  
  
**Conclusion and Moving Forward**

Now that I have a dataset, I can look forward to what I want to do with it. I gathered data on both professional division in disc golf which totaled at over 400 rows with 16 columns. This gives a lot of room for future exploration of this data. One of my main goals is to find differences between the two professional divisions in Disc Golf. The variables associated with the money earned by the players is of particular interest to me. It's no secret that there are pay discrepancies in professional sports across genders, and I would like to explore whether that is true for Disc Golf. The next group of variables that is interesting to me is the performance variables. I am excited to try and piece together what aspects of the sport help players win the most. I look forward to sharing my progress moving ahead with the project
