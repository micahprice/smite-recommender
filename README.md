# smite-recommender

What items go well with/against certain gods in Smite? Let's find out!


A regularized logistic regression supplies a rating for each item as it tries to predict which items lead to a win. Using this information, we suggest useful alternatives to the most popular items used.

You can interact with the different item recommendations using the `smite-recommender-widget` [notebook](https://github.com/micahprice/smite-recommender/blob/master/smite-recommender-widget.ipynb). More information about the recommendations there.

Unfortunately, at the moment, the only way to access it is by having [Jupyter](http://jupyter.org/) installed, downloading the notebook and the [SMITE_recommendations] (https://github.com/micahprice/smite-recommender/tree/master/SMITE_recommendations) folder in the same directory, and running the notebook through Jupyter. You will also need to have [`ipywidgets`] (https://github.com/ipython/ipywidgets#install) installed.



## Examples
-[**Kumbhakarna** w/ **Neith**] (https://rawgit.com/micahprice/smite-recommender/master/smite-recommender-widget-output-example.html)
- More examples can be found at [https://becausewhyexactly.com] (https://becausewhyexactly.com/2016/11/18/can-machine-learning-increase-your-win-rate-in-smite/)


## Prerequisites
- Python 3.5
- Jupyter 4.2
- ipywidgets 6.0


## License
 We use the `smite-python` wrapper created by [Jayden Bailey](http://twitter.com/jaydenkieran) to interact with the Smite API ([GitHub page](http://github.com/jaydenkieran/smite-python)).

Information used for these recommendations is provided by Hi-Rez Studios' `SmiteAPI` and is thus their property. According to Section 11a of the API Terms of Use, you must attribute any data provided as below.

> Data provided by Hi-Rez. © 2015 Hi-Rez Studios, Inc. All rights reserved.
