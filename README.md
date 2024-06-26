# Road Safety Data Anaylsis from Survey Results

Our Road Safety project for Salisbury University’s Presidential Citizen Scholars Program aims to intensely research and enhance road safety on Salisbury's West Side through collaboration with the City of Salisbury and the City’s Transportation and Infrastructure team such William White (Transportation Manager, City of Salisbury), and Jon Wilson (Transportation Project Manager Infrastructure & Development, City of Salisbury). The initiative involves translating IRB-approved survey feedback into accessible infrastructure improvements funded by the "Vision Zero" grant, with a focus on benefiting the marginalized community on the West Side of Salisbury, Maryland. This work includes data calculations, quantitative and qualitative data analysis, and graphic visualizations based on the raw survey results collected from the local community. To protect privacy and confidentiality, the original CSV file will not be uploaded to this repository. Instead, a pseudo CSV file was used to display the code's functionality.


## Using Jupyter Notebook or Google Colab

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Libraries Used 

Here are all of the libraries used to do the full analysis

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

This project was done under the direction of the Presidential Citizens Scholars program. The in-depth final analysis on this research work can be read off the paper published on the Salisbury University's website, under the PCS section. The name of the paper is called "Road Safety & Transportation Equity on Salisbury’s west side Whitepaper" and can be found here:

          https://www.salisbury.edu/academic-offices/liberal-arts/pace/presidential-citizen-scholars/pres-scholar-projects.aspx

Download the PDF to read more about our journey and the aftermath of this amazing research and it's contribution to the greater good of Salisbury!
