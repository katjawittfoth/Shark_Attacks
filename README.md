Data Visualization Final Project: Shark Attack Data

# How dangerous are sharks and is all the fear people have justified?
I'm analyzing shark attacks data from [Global Shark Attack File](http://www.sharkattackfile.net/)

Most people are afraid of sharks, and there's a misconception that if you are in the water with them you are in deep trouble. The idea that sharks are killing machines preying on humans is a myth that I learned to overcome after I became an avid scuba diver, but I've only had two encounters with sharks so far. I’m often diving in the murky waters of Northern California, which is famous for its large population of White Sharks, so I wanted to learn more about the attacks and real risks.

<p align="center"> <img src="plots/scatterplot_attacks_1900-2017.png" align="middle">
</p>
Generally, shark attacks are increasing. We can see that shark attacks are increasing, though the fatal attacks are staying at the same level throughout the century, at about average of 9.2 number of fatal attacks globally per year. 
If you look at the shark attacks development, especially non-fatal ones, you can see a peak around 1960. The peak happens in the USA and Australia, driven by surfing starting to get popular in the 60s.

Sharks hunt at dawn and dusk. If sharks prey on humans, we should see a peak of attacks around dusk and dawn.
<p align="center"> <img src="plots/histogram_attacks_by_time.png" align="middle">
</p>
Not true! Obviously, humans are not part of sharks’ diet and the attacks happen when people are enjoying the beach and water.

<p align="center"> <img src="plots/heatmap_activity.png" align="middle">
</p>
It seems that surfing in the USA and Australia is by far the most dangerous activity. 
Sharks have been known to attack humans when they are confused or curious. Sharks often mistake surfers or humans splashing in the water human for prey. 
Another interesting fact is that sharks are getting confused and overwhelmed by a present of dead fish, thus a large number of shark attacks are happening when people are fishing and spearfishing.

...

#### See full story with many more various plots and cool visuals:
* [Notebook with interrective plotly visualizations and code](https://github.com/katjawittfoth/Data_Viz/blob/master/global_shark_attacks.ipynb)

* [Analysis](https://github.com/katjawittfoth/Data_Viz/blob/master/shark_attacks_story.pdf)
