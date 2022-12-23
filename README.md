# kaggle-competition-spaceship-titanic
Kaggle Spaceship Titanic competition

Results

First results: 0.80079 Rank 923

Second Results: 0.80219 Rank 817

Second iteration changes:
Total expenses added, used, and removed when it was causing the model to favor that column too much.
Children are 12 and under, since expenses only show up at 13 years old.
If someone spent nothing, and they’re an adult (over 13 years old), and they have a nan for cryosleep then we can set them to true because they were likely asleep.

Third Results: 0.80289 Rank 761

Third iteration changes:
Added criterion: ‘entropy’ to clf estimator
Trained estimator on entire training set prior to submission

Fourth Results: 0.80360 Rank 683

Fourth iteration changes:
Further tuned clf parameters
