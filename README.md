# Road Safety Data Anaylsis from Survey Results

One Paragraph of project description goes here

## Using Jupyter Notebook or Google Colab

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Libraries Used 

Here are all of the libraries use to do the full analysis

```
import pandas as pd    # creating and formating dataframe
import numpy as np     #don't entirely need this but is helpful for calculations
from roughviz.charts import Bar, Barh    # third party library, helps create nice looking graphs
import matplotlib.pyplot as plt          # another library for graph visualization
from matplotlib import lines
from matplotlib import patches
from matplotlib.patheffects import withStroke
import seaborn as sns    # For graphic visualization
import os
import tqdm
import imageio      # helps wrap graphs into image filees or gifs
from textblob import TextBlob      # sentiment analyzer for comments

from PIL import Image
from matplotlib import font_manager
from matplotlib.offsetbox import OffsetImage, AnnotationBbox, OffsetBox
```

## Final Paper

A step by step series of examples that tell you how to get a development env running

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

