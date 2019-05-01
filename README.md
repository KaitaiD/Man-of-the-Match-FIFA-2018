# Man-of-the-Match-FIFA-2018
Recently I found this dataset on Kaggle and I am an avid football fan so I decide to create a simple project which predicts the man of the match award.

## Feature description
The dataset is not big, and it contains the following features (typical stats of a football match):
1. Date
2. Team
3. Opponent
4. Goal Scored
5. Ball possesion %
6. Attempts
7. On-Target
8. Off-Target
9. Blocked
10. Corners
11. Offside
12. Pass Accuracy %
13. Saves
14. Passes
15. Distance Covered (Km)
16. Foul Committed
17. Yellow Card
18. Yellow & Red Card
19. Red
20. 1st Goal
21. Round
22. PSO
23. Goals in PSO
24. Own Goals
25. Own Goal time

## Target/Goal of the project
The Target is the Man of the Match award.

Since the given dataset is not large, this project is created to practise feature importance/data visualization tools I learned recently.

## Feature importance using SHAP values

__1. SHAP summary plot__

![alt text](https://github.com/KaitaiD/Man-of-the-Match-FIFA-2018/blob/master/shap1.JPG)

__2. SHAP importance plot__

![alt text](https://github.com/KaitaiD/Man-of-the-Match-FIFA-2018/blob/master/shap2.JPG)

__3. SHAP dependence contribution plot__

![alt text](https://github.com/KaitaiD/Man-of-the-Match-FIFA-2018/blob/master/shap3.JPG)
