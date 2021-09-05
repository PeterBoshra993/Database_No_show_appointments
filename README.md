# Database_No_show_appointments

## Conclusions

- From our histograms There's a lot of people Scheduled Day between 2 months That are May 2016 and June 2016

- Appointment Day that has most people was at 1st of june and 4th of june 2016 

- The highest ages was between 0 and 10 Years old

- nearly 10k of patients has Scholarship

- more than 20k have hipertensions

- nearly 5k of people have diabetes

- nearly 3k are Alcoholism

- nearly 1-2k are handcap

- From 30k - 38k of people has received messages either they confirming the Scheduling or  the Appointment Day

- There's 20,2% of people not shown. That means from 100 people there's a posibility that 20 people won't come

- We had to remove outliers like Age == -1 or Ages > 100

- There's 20,2% of people noshown

- Mean Age is 37 yo, 25% of Ages is 18 Yo, 50% are 37 Yo and 57% is 55 Yo

- For males we can see that mean value of Age 34 Yo 25% are 10 Yo, 50% are 33 Yo and 75% are 54 Yo.

- Mean of males that received SMS is 29%


| Gender  | No-show    | SMS_received
| :---    |:---        | :---
| F       | No         | 0.305393
| F       | Yes        | 0.460558
| M       | No         | 0.265358
| M       | Yes        | 0.396634


- As we can see 30% of sent messages to females has shown while 46% not shown and for Males 26.5% of total patients has shown while 39.66% hasn't shown

| Gender  | No-show    | Scholarship(mean)
| :---    |:---        | :---
| F       | No         | 0.117870
| F       | Yes        | 0.144336
| M       | No         | 0.049609
| M       | Yes        | 0.061100


| Gender  | No-show    | Age(mean)
| :-------|:-----------| :-------------
| F       | No         | 39.586311
| F       | Yes        | 36.145980
| M       | No         | 34.461372
| M       | Yes        | 30.833010

As we can see **14%** of **Females** that have scholarships not appeared at appointment Day and There's **6%** of **men** that has Scholarships(enrolled in Brasilian welfare program Bolsa Família) not appeared at appointment Day so We are pretty sure that having scholarship has strong impact on the appearance of patient.Our final shape of our data is there's 110519 rows (values"outliers removed") and 12 columns we removed The first 3 columns (PatientID, Appointment ID) We may need them if we were searching for a specific ID but here we don't want specific IDs we just want to do some Analysis!!!

[Here's a link to a mark down File extended Syntax review](https://www.markdownguide.org/extended-syntax/)

Also I should mention [Stackoverflow](stackoverflow.com/),[geeks for geeks](www.geeksforgeeks.org) and of course [github](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#links) as they helped me alot to remember some syntax besides did some rememorize from course lessons


### Limitation:-

- we may needed to divide dataframe by neighbourhoods and do some further analysis but we couldn't as there's a length of 81 value and it will take much longer time.

- There's also a needed data to specify which Sms-Message type is sent "Is it confirmation or a reminder?"


### Finally

- Maybe we can Predict which one will show and who won't but further data is needed
