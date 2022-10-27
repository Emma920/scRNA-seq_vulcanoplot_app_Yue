# Interactive single-cell RNA-seq vulcano-plot exploration app

I created this app to enable quicker exploration of vulcano-plots between clusters/groups of scRNAseq datasets.

The app is written in python using and [bokeh](https://docs.bokeh.org/en/latest/) (from [pyviz](https://pyviz.org/)). I use [scanpy](https://scanpy.readthedocs.io/en/stable/) to deal with the data. Statistics are mostly done using [pandas](https://pandas.pydata.org/) and [numpy](https://numpy.org/).
The [panel](https://panel.holoviz.org/) (also from pyviz ecosystem) has been updated since I made this app, and it would be significantly easier to use their higher-level api (thats build on top of bokeh) next time.

The code (see the .ipynb notebook) is given without data, since I do not have the right to redistribute it. This means that the code cannot actually run.

<img src="https://github.com/Emma920/scRNA-seq_vulcanoplot_app_Yue/raw/main/Screenshot.png" height="300"/>

# Try the app

Go to: https://204e-130-225-212-4.eu.ngrok.io/app  
If the [ngrok](https://ngrok.com/) link goes down, then just text me on linkedin, and I will fix it :) 
