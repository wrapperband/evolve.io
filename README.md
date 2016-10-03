# evolve.io
evolution simulator written by Carykh  AKA Cary Huang


From Youtube Evolv.io is now open source! 

https://www.youtube.com/watch?v=OLnv8QaEDL0


Cary Huang is a student that has written some very interesting and visually impressive evolution demonstrations in "open processing"

His latest experiment is evolvio.io where Gary has tried to include features such that the "artificial creatures" have some personalities. His initial version had the idea that tiles would change colour with the creatures that died leaving their remains, which would be "poisonous" to other species. This turned out to be over complicated and very slow as each tile had to be recalculated for it's food content over time.

The second commit is a more "realistic" simpler version. From my experience with other learning systems (Critterdings, Javascript evolution experiment). I believe it would be interesting to be run for longer periods and new skills would develop.

In the experiments with https://github.com/wrapperband/JavascriptEvolutionExperiment and creating larger brains, I found that it took longer to evolve skills.

Here is and example skills and evolve time for a large brain 6 neurons 7 layers.

The first skill learned was go forward  ( repeated starts (20) until some creatures move)
Find Food 5 hours
Wait while no food is available 5 hours
Turn Right and left 100 hours
Find "lines of food" 150 hours
Deliberately target centre of food - 150 hours
Move away from other creatures if food scarce - not found
Move towards larger food when 2 are available.
scan for food - not found
Look behind them selves - not found

DrWrapper


The initial commit is the original files, the second is the refined files.

Cary Hang says : 

Published on 1 Oct 2016

Hi people! I just hit 50,000 subscribers after recording this video, so I didn't have a chance to say thank you in the video. Why not say it here? THANKS FOR 50K

WARNING: The source files below don't have the best style. That's what happens when you try to rush together a project in 3 days without the intent of sharing it with others! It's definitely better than the original though.

ULTRA WARNING: It looks like it only works in Processing 2. So sorry for not mentioning that in the video. (However, if you just copy the raw text of the files into Processing 3, I think it should work...)

SUPER WARNING: You have to move all the .pde files and the data folder INTO a folder called "evolvioColor" for it to work correctly. Then, run Processing 2, select "Open", and double click on any of the .pde files.

HYPER WARNING: The first source files linked create very small creatures, which means more of them can exist, meaning MUCH MORE LAG (when running 1x). If you don't want lag, go with the second link, which has the source files from the last Evolv.io video. (But these older files don't have tile optimization, so they'll lag when you have play speed set really high)

Other simulators by Cary

Carykh
Evolution Simulator
https://www.youtube.com/watch?v=GOFws_hhZs8
http://www.openprocessing.org/sketch/377698