
# "1699"

made by Jaehyeok Choi

## Welcome to Jaehyeok's github!

## What is the problem?

![button](https://github.com/Choi-JaeHyeok-21500749/1699/blob/main/1699_pro.JPG)

## What Algorithm should I use?

dynamic programming

## What was the key point and the hard part?

To find the min number of how many square number should be used to make some number, it is prefer to used bigger number.

For example, making 5 with square number, we can use 1^2 5 times or use 2^2 one time and use 1^2 one time.

However, using bigger number is not always right way. 

For instance, min number of making 12 with square number is 3 not 4.
(2^2 + 2^2 + 2^2 , not 3^2 + 1^2 +1^2 + 1^2)

Because of this reasons, we should check the all possible cases. Then , we should save the min number in the dp array and use it after.

Because we cannot use number bigger than {sqrt(root) of N} to make N, all we should do is checking 1 to {sqrt(root) of N}.
Let's assume the iteration for this loop is 'j'.

We already save the min number in the dp array. After use j^2 number, all we need to do is find dp[N-j^2] and add it.
Using j^2 to make n number is only taking 1 portion, so add 1 to dp[N-j^2] will be the answer.

## Where can I get more help, if I need it?

You can contact me through email, which is 21500749@handong.edu.
Thank you for visiting this github!

