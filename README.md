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

Many students drop out of university before completing their degree. Universities often notice the problem too late. An AI system could identify students who are at risk of dropping out and help the university provide support before it happens.


## How is it used?

The main users would be university advisors, teachers, and student support departments. Students would also benefit indirectly because they could receive help earlier.


![Student performance dashboard](https://www.boldbi.com/wp-content/uploads/2025/12/student-performance-dashboard-v2.webp)


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
The data would come from university information systems and learning platforms. It could include attendance records, course grades, assignment completion rates, and student participation in online courses. Historical data from previous students would be used to train the model and identify patterns associated with dropping out.
[Boldbi](https://www.boldbi.com/dashboard-examples/education/student-profile-dashboard/?utm_source=chatgpt.com)

| Category      | Description |
| ----------- | ----------- |
| Category	Description
Project Name      | Student Dropout Predictor       |
| Problem   | Predict which students are at risk of dropping out.        |
| Users   |  University advisors, teachers, and student support staff  |
| AI Method  |  Logistic Regression  |
| Data Sources |  Attendance records, grades, assignment completion rates, and online learning activity |
| Output | Probability that a student may drop out |
| Benefits | Early intervention, improved student success, and higher graduation rates |
| Challenges | Data privacy, biased data, and prediction accuracy. |
| Future Work | Improve the model with more data and develop a dashboard for advisors |

| Data Sources      |  |
| ----------- | ----------- |
| Data Type | Description |
| Attendance Records | Student attendance in classes |
| Grades | Exam and assignment scores |
| Assignment Completion | Percentage of completed coursework |
| Online Participation | Activity in learning platforms |
| Historical Data | Records of previous students who graduated or dropped out |


## Challenges

The system may produce inaccurate predictions if the data are incomplete or biased. Protecting student privacy and handling sensitive information responsibly are also important challenges. In addition, not all factors affecting student success can be captured by data alone.

## What next?

The next step would be to collect and prepare historical student data, train and test the machine learning model, and evaluate its accuracy. Future improvements could include adding more data sources and developing a dashboard that helps advisors identify and support at-risk students more effectively. 


## Acknowledgments

* list here the sources of inspiration 
* do not use code, images, data etc. from others without permission
* when you have permission to use other people's materials, always mention the original creator and the open source / Creative Commons licence they've used
 [Student performance dashboard](https://www.boldbi.com/dashboard-examples/education/student-performance-dashboard/) /
