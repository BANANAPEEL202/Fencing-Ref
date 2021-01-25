# Fencing-Ref
<p align="center">
  <img src="https://github.com/BANANAPEEL202/Fencing-Ref/blob/main/Fencing%20Pose.jpeg" width="583" height="328">
</p>
                                   
Fencing isn’t exactly known for being at the leading edge of sports technology. It wasn’t until the 1990s that foil fencing had electric scoring systems. However, fencing presents a unique challenge that should be perfect for artificial intelligence.
The Why
Unlike many other sports, the referee in fencing has a huge influence over the outcome of a bout. The ref has the power to determine who gets the point after a touch. It’s not like in basketball, where if the ball goes in the hoop, you’re guaranteed to score points. There are complex rules of right of way that dictate which fencers score a point in the event they both hit. Many of these rules are up to interpretation by the referee.
Good referees are also hard to come by. The fencing community is already relatively small, and as you can imagine, the refereeing community is even smaller. Referees often work 10 hours a day during tournaments.
This is where artificial intelligence can hopefully step in and help. The obvious advantages being that there is no limit to how many bouts a software algorithm could ref and that algorithms are consistent in their output. Realistically, an artificial intelligence referee just wouldn’t be able to replace a human one and would be only there to assist the human referee. This could be especially useful when a fencer challenges a referee’s call, something that is currently limited to only very high-level fencing where there is more than one ref at hand.
If you want to catch up on how right of way works in fencing, Ninh Ly has a great and simple clip on it.


Our task here is a binary classification problem, either touch left or touch right (we’re excluding simultaneous touches here to make the task much simpler). We’re fortunate to have a vast library of fencing videos on youtube that we can use to train the model. All we need to do is cut the video into smaller clips and label each as touch left or right, which we will cover in the next post. After that, we can treat this as a human action or video classifier.

Blog Posts going into more detail on this project:

https://thejasonmo.medium.com/automated-data-collection-from-youtube-6e433b0e3513
https://thejasonmo.medium.com/pose-estimation-and-preprocessing-for-an-ai-fencing-referee-e63515a55dbd


<img align="left" width="600" height="338" src="https://github.com/BANANAPEEL202/Fencing-Ref/blob/main/graph.gif">
<img align="right" width="600" height="338" src="https://github.com/BANANAPEEL202/Fencing-Ref/blob/main/pose.gif">
