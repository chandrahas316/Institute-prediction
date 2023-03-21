# Institute-prediction

## Dataset

### columns - 

- Institute : Refers to the names of the institutes that comes under JoSAA counselling seat selections

- Academic Program Name : Refers to the names of the available engineering courses

- Qouta : Refers to the different categories or groups of seats available such as All India Quota(AL), Home state qouta(HS), Other state Qouta(OS) etc..,

- Seat Type : Refers to the different categories of seats such as OPEN, EWS, OBC-NCL, SC, ST etc..,

- Gender : Refers to the student gender

- Opening Rank - Refers to starting rank to enter into that institute

- Closing Rank - Refers to the last rank to enter into that institute

- Round - Refers to the round number of JoSAA counselling in 2022

## Code implementation 

- Install required libraries before running the code.

- Data Preprocessing - Removed all the ranks in which alphabet 'P' presents to increase efficiency in model.

- Data Preparation - Encoded dataset into 0's and 1's which will be helpful in preparing decision tree.

- Implementing Decision tree using ID3 algorithm.

- Predicting a student's his/her possible institutes they get in that round of JoSAA counselling given their Seat Type, Gender, Rank.
