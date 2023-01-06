Project 1 submission
Project title: Tests in the Time of Pandemic

Problem Statement:
The transition between 2019 and 2020 can be seen as a turning point, where many aspects of life suddenly took unprecedented turns. Education is one of the fields that had experienced most disruptions during this turning point, with most schools closed and shifted to online learning.

Looking into SAT and ACT data from these two years -2019 and 2020-, this project investigates how the onset of the pandemic had impacted ACT and SAT tests scores and participation rates, and how differently these impacts were seen in different geographical locations in the US.

Stakeholders:
The state governments and policy makers, examination boards' leaderships, and universities' admission officers.

This project aims to answer five questions:
Q1. Are there any drops in test scores when Covid-19 striked in 2020 compared to the year before?

Q2. It is common knowledge that Covid-19 disruptions had different impacts on different groups of students.
    Which margin group of SAT takers - the top five high scorers or the lowest five scorers - has been more impacted when Covid-19 striked?
    How many percentage drop/rise in scores, compared to the year before, have both groups experienced?

Q3. Which of these geographical groups - the east coast, west coast, or interior states - do better in which tests in 2019?
    If a state do well in SAT, does it also do well in ACT? (and vice versa)
    Did the onset of covid-19 in 2020 change this pattern?

Q4. Did participation rates change from the previous year when Covid-19 striked in 2020?

Q5. Which of these geographical groups -the east coast, west coast, or interior states- have higher participation in which tests in 2019?
    If a state participate highly in ACT, is its participation in SAT lower? (and vice versa)
    Did the onset of covid-19 in 2020 change this pattern?

Q6. Are there any correlations between SAT and ACT scores and participation rates?

Organization:
The jupyter notebook for my codes is organised in eight sections as follow:
Section 1. Import and prepare data
Section 2. Answers to Q1
Section 3. Answers to Q2
Section 4. Answers to Q3
Section 5. Answers to Q4
Section 6. Answer to Q5
Section 7. Answer to Q6
Section 8. Conclusion

Conclusion:
Most significant findings emerging from this project are:
1. Average scores for both ACT and SAT have dropped in 2020 compared to 2019. However, the drop is not significant.
    Although the average scores have dropped, ACT highest score has risen from 25.5 to 26. On the other hand, SAT highest score has dropped from close to 1300 in 2019 to close to 1250 in 2020.

2. The onset of Covid-19 in 2020 has bigger impacts on top five SAT high scorers, which experience an average of 0.21% drop in scores, compared to bottom five group with just 0.002% drop.

3. There are correlations between geographical groups (east coast, west coast, and interior states) and test scores. These correlations follow this pattern:
    - West Coast states are doing moderately well on both tests. Between 20 and 23 on ACT and between 1050 and 1150 on SAT.
    - East Coast states are doing low to moderate on SAT (between 950 to 1150) but mostly well on ACT (only 3 states score below 22).
    - Inner states are divided into two patterns:
        (i) about half of them are doing moderately to well on SAT (scoring 1100 and above) but scoring rather low (below 22 points) on ACT;
        (ii) the other half are doing rather poorly on SAT(below 1100), but more than half of this group scores above 22 points on ACT.
    This pattern of geographical score divide stays the same in 2020 despite Covid-19 onset.

4. Participation rates did not change much between 2019 and 2020. This finding can lead to further investigation.
    Consulting findings from Xue Feng's research within my group, it is understood that participation rates only drop in 2021. This demonstrates that there is a delay response to Covid-19 disruption on ACT and SAT tests.

5. The onset of Covid-19 in 2020 has more disruption on participation than scoring patterns.
    This disruption is least noted among West Coast states and most noted among inner states.
    - In both years, West coast states' participation was moderate to high rate (40%-75%) in SAT and lower rate (20%-50%) in ACT.
    - East Coast states, which mostly participated highly in SAT and lower in ACT in 2019, had in 2020 chosen to take mostly SAT (more than half has above 80% SAT participation rate).
    - Inner states, interestingly, had a rather uniform ACT participation rate of 20% in 2019 and most did not take SAT. In 2020, they were divided into 2 groups: one took mostly only ACT and the other took mostly SAT.

6. . There are high correlations between SAT score and ACT participation and vice versa that increased when Covid-19 striked. However, the correlations between ACT and SAT scores are low. These correlations need further investigation that include other relevant data such as how badly covid had impacted each geographical location.

Recommendation:
1. Insights from this projects can be used to inform future decisions on test policies, that takes into account the  different geographical correlations, which are:
    - West Coast prefers SAT, scores moderately on both.
    - East Coast prefers SAT, scores high on ACT.
    - Inner states:
      - two score groups:
        (i) score high on SAT, low on ACT both 2019 and 2020
        (ii) low on ACT, high on SAT both 2019 and 2020
      - Participation before covid: 20% on ACT, many did not take SAT.
        Participation in 2020: either ACT or SAT.
Building upon this knowledge, further research can be done to investigates whether low participation in a certain test means that only those who score high submitted their results (East coast and inner state group (i) results above lead to this hypothesis).

2. Based on this finding, further actions can be done to improve university admission systems by considering geographical statistics and test preferences.

3. It is also recommended that further research into the impacts of pandemic on ACT and SAT takes into account other relevant data such as: different levels of healthcare accessibility in different states and how many percentage of the population believed in the pandemic.

4. Further research is also needed to include data from 2021, considering the delay response of covid impacts on tests.
