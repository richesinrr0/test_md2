# HR Survey Report Analysis

Analysis of the scanned paper results from the DIP, maintenance, manufacturing, melting, and steel pipe divisions.

1. Survey Ratings
    - Distribution of data
    - Ratings by deparment
    - Satisfaction scores
    - Best and worst rated questions 
2. Written Responses
    Question 23
    - Most frequent topics  

    Question 24
    - Sentiment analysis
    - Sample of responses

    Question 25
    - List of most frequent words    
    - Most frequent topics
***
## 1. Survey Ratings

#### Distribution of data

A total of 681 employees filled out a paper survey. With a majority being from DIP.

![Distribution bar graph](/graphs/categoryDistribution.png)

***
#### Ratings by department (Questions 1 - 22)
###### Graph showing the total numbers of each response for each division:
![Category Bar PLot](/graphs/categoryCountplot.png)
>Dip has a proportionally larger amount of  5 (Strongly Agree) responses, which in turn gives it the highest satisfaction score. Maintenance has a large number of average ratings, as well as a proportionately high number of low (1 and 2) ratings, giving it the lowest satisfaction score.

![satisfaction df](/graphs/hr_project_satisfaction_df3.png)

The satisfaction score is a measure of how close each division was to a perfect satisfaction score, all (5)'s. The larger the satisfaction score, the better the ratings were for each division.

***

#### Best and lowest rated questions

How employees responded to the questions.
> **The questions with the best overall ratings:**
> 1. ***Question 20*** (I see myself working here in a year.)
> 2. ***Question 22*** (I understand the importance of my job in producing a quality product.)
> 3. ***Question 2*** (I enjoy working with my team.)
> 4. ***Question 1*** (I would recommend ACIPCO to my friends as an employer.)
> 5. ***Question 15*** (I am proud to work for ACIPCO.)

> **The questions with the lowest overall ratings:**
> 1. ***Question 4*** (I know who buys our products.)
> 2. ***Question 8*** (The company communicates well with employees.)
> 3. ***Question 14*** (My job provides the right work-life balance.)
> 4. ***Question 9*** (I feel informed about company happenings.)
> 5. ***Question 12*** (I feel the company is open to change.)

**Graph for the top rated questions per category:**

![Category Top Questions](/graphs/qHighestWordsLong.png)


**Graph for the lowest rated questions per category:**

![Category Top Questions](/graphs/qlowestLong.png)

***
# 2. Written Responses
## Question 23:
*What can be improved to make ACIPCO a better place to work?*

**Question 23 common themes:**

*Communication:*
There are **45** responses that reference improving communication.

> "Better communication between leadership Positions and employees. More appreciation For good work that has been done. And just over all morale in the shops need to Change they are low."

> "Clear communication between management and the workforce, go back to work culture of 2005."

> "Better communication HR/upper management with shop management. "




*Improve restrooms:*

> "Cleaner Restrooms."

> "New bathrooms everywhere."

> "The bathrooms could be improved some."


*Improve medical insurance:*

> "Better prescription coverage certain medicine our insurance doesn't cover."

> "Benefits like more Vacation and pension, lower Co-pays with insurance."

> "Put more of an value on family time away from here and make insurance affordable again!"


*Work life balance with family:*
> "Management needs to understand Money is Not everything Family is important Not every one wants To Live out here."

> "A better work-life balance would be nice, but the demands of the industry need to be met. Who better to meet them then American!"

> "Time available to take kids of other family member to the doctor or other appointments without filing for FMLA or taking vacation."

> "Acipco was founded on the "Golden Rule" but we as a company have gotten away from that. We as employees need more balance of off days to spend with family!"

*Equipment maintenance*

> "Better equitment and saftey."

> "REINSTATE PENSION BETTER MAINTENANCE OF EQUIPMENT AND REPAIR, (NO BAND-AIDING). BETTER MATERIALS."

> "Better more modern equipment."



***

## Question 24:
*How do you feel our Golden Rule values are shown at work?*

**Question 24 sentiment analysis:**
Using a machine learning model, each written response to survey question 23 was labeled as expressing negative, neutral, or positive sentiment.

![Category Top Questions](/graphs/responseToQ23.png)

Sample of responses:
> `"They was great when I started, but they have slowly diminished over the years."`  

> `"ACIPCO respects and treats there employee's equally in my opinion. Same as I would do to other people. You can tell they're doing the best they can for their employee's. The effort is apparent."`

> `"I believe that it has completely gone out the window. And upper management does not have any respect for our hourly guys."`

>`"I feel like its only about the product, which there would be no product with out the employee At the end of the day a quality employee puts out quality products."`

>`"Eagan's legacy through profit sharing exhibits the golden rule. Employees who live by The golden rule use it at work. Others are here just for a pay check."`

***

## Question 25 :
*Question 25: Anything else you would like to share about your experience here at ACIPCO?*

A List of the most common words found in responses after removing stop words:

![Category Top Questions](/graphs/Q25TopWords.png)


**Question 25 common themes:**

*Work life balance:*

> "Lots of Room to move up. The money is good but work life balance is the down fall."

> "Need more work/personal life balance. I know we need to work but working too much affects the employee." 

> "A better work-life balance."


*Worker Safety:*

> "I would like for acipco to take job training more seriously in the respect of choosing people who are known to have bad safty habits and pass on bad practice to newer employees who need a more strict training for better work quality and personal health."

> "The culture here is terrible, management thinks and looks at the hourly employee as a piece of trash. We are treated like prisoners and kids. Management is always looking for ways to screw us. Quality is a joke. Safety is also a joke."

> "Safety here need to be hard on employees that wear they rags over their ears... knowing (if) they have (their) earbuds (in), need more focus on that. Dress code not being inforced. Employee parks any kind way. Employee said high up supervision dont acknowledge lower employee."

*Communication:*
>Better communication from higher ups.

> "The job is rewarding as long as you remember why youre doing it. There is no teamwork or communication between departments. W eall work for the same company with the same goal or so you would think. Everyone is against each other and if youre not a part of the clique you will be terminated..."

> "I honestly love the opportunity to work here at ACIPCO, but Sometimes when a worker is under fire, they do not get a fair chance at a non-bias ear to hear that worker."


