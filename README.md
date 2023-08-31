# NoSQL-Challenge

 -[Background](#Background)<br>
 -[Questions](#questions)

# Background
The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. You've been contracted by the editors of a food magazine, Eat Safe, Love, to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles.

e.g.: Import the dataset with `mongoimport --db uk_food --collection establishments --file establishments.json --drop --jsonArray`

# Questions
1) Which establishments have a hygiene score equal to 20?
There are 41 establishments that have a hygiene score that is equal to 20

2) Which establishments in London have a RatingValue greater than or equal to 4?
There are 31,257 different food establishments that have a Rating of four more.

3) What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
There were 87 results but the top 5 establishments with a Rating of 5 and were within 0.01 distance from 'Penang Flavours' were:
    1) TIWA N TIWA African Restaurant Ltd
    2) Fineway Cash & Carry
    3) Lucky Food & Wine
    4) Premier Express
    5) Everest Stores Ltd

4) How many establishments in each Local Authority area have a hygiene score of 0?<br>
![hygiene_of_zero](/Resources/images/LocalAuthority_hygiene_zero.png)

