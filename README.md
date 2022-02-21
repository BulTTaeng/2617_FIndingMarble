# 2617_FIndingMarble

made by Jaehyeok Choi

## Welcome to Jaehyeok's github!

## What is the problem?

![image](https://github.com/Choi-JaeHyeok-21500749/2617_FIndingMarble/blob/main/2617_pro.PNG)

## What Algorithm should I use?

Graph Algorithm, dfs

## What was the key point and the hard part?

To find marble that cannot be in the middle, we have to count the number of marbles that is heavier or lighter than some marble.

If there is more than half of the marble is heavier than some marble, that marble cannot be in the middle.

Also, if there is more than half of the marble is lighter than some marble, that marble cannot be in the middle.

I have 2 graph to solve this, one is directional graph (heavy to light) and the other one is (light to heavy).

After that I do dfs at every marble and count the heavier and lighter marble.

If the number of haevier marble is bigger than the half that means it cannot be in the middle.

If the number of lighter marble is bigger than the half that means it cannot be in the middle.

## Where can I get more help, if I need it?

You can contact me through email, which is wogur7496@gmail.com.
Thank you for visiting this github!
