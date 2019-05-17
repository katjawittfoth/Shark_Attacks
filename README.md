Data Visualization Project on Shark Attack Data using Plotly

# How dangerous are sharks and is all the fear people have justified?
Analyzing shark attacks data from [Global Shark Attack File](http://www.sharkattackfile.net/)

Most people are afraid of sharks, and there's a misconception that if you are in the water with them you are in deep trouble. The idea that sharks are killing machines preying on humans is a myth that I learned to overcome after I became an avid scuba diver, but I've only had two encounters with sharks so far. I’m often diving in the murky waters of Northern California, which is famous for its large population of White Sharks, so I wanted to learn more about the attacks and real risks.

### Dataset
I am using shark attack incidents dataset from Kaggle: 
https://www.kaggle.com/teajay/global-shark-attacks. This data was compiled by the Global Shark Attack File. 

#### Scatterplot
Let’s take a look at the general development of shark attacks from 1900 to 2017.
<p align="center"> <img src="plots/scatterplot_attacks_1900-2017.png" align="middle">
</p>
We can see that shark attacks are increasing, though the fatal attacks are staying at the same level throughout the century, at about average of 9.2 number of fatal attacks globally per year. This number doesn’t change much by decade either.
If you look at the shark attacks development, especially non-fatal ones, you can see a peak around 1960. The peak happens in the USA and Australia, driven by surfing starting to get popular in the 60s.

#### Histogram
Sharks hunt at dawn and dusk to benefit from darkness by using not only their highly evolved sense of smell but also detecting electricity and vibrations in the water. The assumption is that if sharks prey on humans, we would see a peak of attacks around dusk and dawn.
<p align="center"> <img src="plots/histogram_attacks_by_time.png" align="middle">
</p>
As you can see that is not true. Obviously, humans are not part of sharks’ diet and the attacks happen when people are enjoying the beach and water time between around 10 am and 5 pm.

#### Heatmap
We have seen a peak in the shark attacks during 60’s and I assumed that it strongly correlates with the increasing popularity of surfing. Let’s analyze if it is true.
<p align="center"> <img src="plots/heatmap_activity.png" align="middle">
</p>
It seems that surfing in the USA and Australia is by far the most dangerous activity. 
Sharks have been known to attack humans when they are confused or curious. Sharks often mistake surfers or humen splashing in the water human for prey. They get curious and may try to investigate.
Another interesting fact is that sharks are getting confused and overwhelmed by a present of dead fish, thus a large number of shark attacks are happening when people are spearfishing, wading or fishing in the sharks’ territories.

...

#### See many more various plots and cool visuals in the Jupyter Notebook.
