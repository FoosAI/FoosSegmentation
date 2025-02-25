# FoosMetrics
Deep-learning AI for building foosball player metrics from recorded match videos.

This project is for teaching a deep-learning model to extract the following information from video recordings of foosball matches:
* Which rod curently has control of the ball
* What the score of the current game is
* What the score in the set of games is
* Whether the gameplay is active on the table (eg, timeout or pre/post match warmup)

By building a model that can extract this information from videos, we can automatically compute player metrics such as:
* 5-to-3 pass success rate
* Score rate from offense
* Score rate from defense
* Success rates on 2-to-X's
* Block rates
* etc.

The eventual goal is to provide a website for the foosball community so you can view player stats for both pro and amateur players. The website would also allow you to submit your own foosball match recordings to have your stats computed.
