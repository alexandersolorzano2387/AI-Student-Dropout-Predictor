# AI-Student-Dropout-Predictor
This AI system predicts which university students may be at risk of dropping out. By analyzing data such as attendance, grades, and assignment completion, it estimates the likelihood of a student leaving their studies. The goal is to help universities provide early support and improve student success rates.
<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# Project Title

AI Student Dropout Predictor

## Summary

This AI system helps universities identify students who may be at risk of dropping out before completing their studies. It analyzes information such as attendance records, grades, and assignment completion to estimate the likelihood of a student leaving their program. Using machine learning techniques like logistic regression, the system can detect patterns associated with academic difficulties and low engagement.

The predictions can help advisors and support staff intervene early by offering guidance, tutoring, or other resources. The main goal is to improve student success, increase graduation rates, and reduce dropout rates. While the system provides useful insights, final decisions should always involve human judgment, and student privacy must be protected when collecting and using data. 


## Background

Which problems does your idea solve? How common or frequent is this problem? What is your personal motivation? Why is this topic important or interesting?

This is how you make a list, if you need one:
* problem 1
* problem 2
* etc.


## How is it used?

Describe the process of using the solution. In what kind situations is the solution needed (environment, time, etc.)? Who are the users, what kinds of needs should be taken into account?

Images will make your README look nice!
Once you upload an image to your repository, you can link link to it like this (replace the URL with file path, if you've uploaded an image to Github.)
![Cat](https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg)

If you need to resize images, you have to use an HTML tag, like this:
<img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg" width="300">

This is how you create code examples:
```
def main():
   countries = ['Denmark', 'Finland', 'Iceland', 'Norway', 'Sweden']
   pop = [5615000, 5439000, 324000, 5080000, 9609000]   # not actually needed in this exercise...
   fishers = [1891, 2652, 3800, 11611, 1757]

   totPop = sum(pop)
   totFish = sum(fishers)

   # write your solution here

   for i in range(len(countries)):
      print("%s %.2f%%" % (countries[i], 100.0))    # current just prints 100%

main()
```


## Data sources and AI methods
Where does your data come from? Do you collect it yourself or do you use data collected by someone else?
If you need to use links, here's an example:
[Twitter API](https://developer.twitter.com/en/docs)

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

## Challenges

The system may produce inaccurate predictions if the data are incomplete or biased. Protecting student privacy and handling sensitive information responsibly are also important challenges. In addition, not all factors affecting student success can be captured by data alone.

## What next?

The next step would be to collect and prepare historical student data, train and test the machine learning model, and evaluate its accuracy. Future improvements could include adding more data sources and developing a dashboard that helps advisors identify and support at-risk students more effectively. 


## Acknowledgments

* list here the sources of inspiration 
* do not use code, images, data etc. from others without permission
* when you have permission to use other people's materials, always mention the original creator and the open source / Creative Commons licence they've used
  <br>For example: [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
* etc
