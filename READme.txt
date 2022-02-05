# 02-DataVis-5ways
Sarah J. Weintraub
Assignment 2 - Data Visualization, 5 Ways  
===

For this project, I used R-ggplot, R-lattice, Python-matplotlib, Python-plotly, and d3 to create the charts based on the cars dataset. 

# R
The charts made in R can be found in an RMarkdown, r_charts.Rmd.
https://github.com/sjtrauber/a2-DataVis-5ways/blob/main/r_charts.Rmd

I started with ggplot and quickly met requirements due to the libraries vast documentation and user troubleshooting.
![r_ggplot](img/r_ggplot.png)

Next, I tried the library plotly and while I did learn tricks along the way (see r_charts.Rmd), I noticed it does not allow multiple legends. I did like that the plot was interactive so that you could mouse over each point and learn a little bit more about it.
![r_plotly](img/r_plotly.png)

For a technical challenge, I wanted to test a few more libraries so I moved on to test plot, a base R library, however it was not very flexible and all the user boards kept pointing me back to ggplot as it is more functional. 
![r_plot](img/r_plot.png)

I still wanted to try some more libraries so I found lattice, while I still prefer ggplot, I was able to do everything I wanted to do with this library. I did have to drastically adjust the size of the circles which I found interesting as I did not need to do that with any other library.
![r_lattice](img/r_lattice.png)

To expand my technical and design achievment, I wanted to explore the dataset and play with some more visualizations so I created some more interesting charts including a donut scatter plot, pie chart, and a heatmap.
![r_ggplot_play](img/r_ggplot_play.png)
![r_pie_play](img/r_pie_play.png)
![r_pheatmap_play](img/r_pheatmap_play.png)

I really enjoyed exploring all the extra options I had not been able to use previously with ggplot.



# Python
For python, my code can be found in a Jupyter notebook, a2_chart.py.ipynb. 
https://github.com/sjtrauber/a2-DataVis-5ways/blob/main/a2_chart.py.ipynb

I started with the matplotlib library and found it did have a lot of ability to tweek as needed. For my design achievment, instead of leaving the colors to default as I had done in all the R libraries, I chose to select my colors. This is something I have not done before but will almost definetly use again.
![py_matplotlib](img/py_matplotlib.png)

Seeing that plotly was also available in Python, I was interested to see how it varied in Python compared to R. I actually preferred in over the R library, and preferred it over matplotlib which I was not expecting. The only thing I did not like about the library was the way it changed the axis ticks, but as soon as I found the documentation, it was easy to adjust to my liking.
![py_plotly](img/py_plotly.png)


# d3
Lastly, my code for d3 can be found in a2_chart.html.
https://github.com/sjtrauber/a2-DataVis-5ways/blob/main/a2_chart.html

My biggest challenge for plotting in d3 was understanding domain and range. It took me a lot of tweeking to understand what each do. As this is the newest language to me, I was very proud of every adjustment - however it did take the longest, by far. I started by using https://www.d3-graph-gallery.com/graph/scatter_basic.html as a template and adjusted as needed.
![d3_chart](img/d3_chart.png)
