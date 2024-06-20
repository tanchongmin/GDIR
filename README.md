# GDIR
Goal-Directed Intrinsic Rewards

This is a paper written prior to Learning, Fast and Slow (https://github.com/tanchongmin/learning-fast-and-slow).
In this paper, we seek to imbue intrinsic rewards that are goal-directed (aka more rewards closer to the goal). We find that agents with such goal-directed intrinsic rewards learn faster as compared to just having the external reward when having reached the goal.

The reviewer comments in ICLR 2023 mentioned that such goal-directed intrinsic rewards necessarily mean that you need to know the goal in mind and is not suitable for arbitrary environments. I agree and this is addressed in Learning, Fast and Slow with a self-supervised way to learn the next action (the probabilities of which are the goal-directed intrinsic rewards).
