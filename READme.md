READme.txt

# 02-DataVis-5ways
Sarah J. Weintraub
Assignment 2 - Data Visualization, 5 Ways  
===

For this project, I used R-ggplot, R-lattice, Python-matplotlib, Python-plotly, and d3 to create the charts based on the cars dataset. 

# R
The charts made in R can be found in an RMarkdown, r_charts.Rmd.

I started with ggplot and quickly met requirements due to the libraries vast documentation and user troubleshooting.
![r_ggplot](https://user-images.githubusercontent.com/57506869/152661160-05f0baa3-4f43-48c6-9c85-cc819ca84181.png)

Next, I tried the library plotly and while I did learn tricks along the way (see r_charts.Rmd), I noticed it does not allow multiple legends. I did like that the plot was interactive so that you could mouse over each point and learn a little bit more about it.
![r_plotly](https://user-images.githubusercontent.com/57506869/152661166-2063ec13-20e8-4b2f-874f-9471c1b88925.png)

For a technical challenge, I wanted to test a few more libraries so I moved on to test plot, a base R library, however it was not very flexible and all the user boards kept pointing me back to ggplot as it is more functional. 
![r_plot](https://user-images.githubusercontent.com/57506869/152661174-a8797e62-e205-495c-81b9-ffb1d7471e71.png)

I still wanted to try some more libraries so I found lattice, while I still prefer ggplot, I was able to do everything I wanted to do with this library. I did have to drastically adjust the size of the circles which I found interesting as I did not need to do that with any other library.
![r_lattice](https://user-images.githubusercontent.com/57506869/152661177-f67fe86a-5504-4bb2-a9ba-7c7c7e163411.png)

To expand my technical and design achievment, I wanted to explore the dataset and play with some more visualizations so I created some more interesting charts including a donut scatter plot, pie chart, and a heatmap.
![r_ggplot_play](https://user-images.githubusercontent.com/57506869/152661182-f39e892f-b74e-4d46-8740-a9740e5d5767.png)
![r_pie_play](https://user-images.githubusercontent.com/57506869/152661184-d29078e4-f5bc-49ca-9e24-bbb04e8a91c8.png)
![r_pheatmap_play](https://user-images.githubusercontent.com/57506869/152661187-1108633b-38fc-454a-9aa9-99c21b14ffbd.png)

I really enjoyed exploring all the extra options I had not been able to use previously with ggplot.



# Python
For python, my code can be found in a Jupyter notebook, a2_chart.py.ipynb. 

I started with the matplotlib library and found it did have a lot of ability to tweek as needed. For my design achievment, instead of leaving the colors to default as I had done in all the R libraries, I chose to select my colors. This is something I have not done before but will almost definetly use again.
![py_matplotlib](https://user-images.githubusercontent.com/57506869/152661189-14d50f0b-648e-4c35-8452-6b7ff8f2dedd.png)

Seeing that plotly was also available in Python, I was interested to see how it varied in Python compared to R. I actually preferred in over the R library, and preferred it over matplotlib which I was not expecting. The only thing I did not like about the library was the way it changed the axis ticks, but as soon as I found the documentation, it was easy to adjust to my liking.
![py_plotly](https://user-images.githubusercontent.com/57506869/152661193-bc1873c9-a013-4366-b92d-e489cb9db90f.png)


# d3
Lastly, my code for d3 can be found in a2_chart.html.

My biggest challenge for plotting in d3 was understanding domain and range. It took me a lot of tweeking to understand what each do. As this is the newest language to me, I was very proud of every adjustment - however it did take the longest, by far. I started by using https://www.d3-graph-gallery.com/graph/scatter_basic.html as a template and adjusted as needed.
![d3_chart](https://user-images.githubusercontent.com/57506869/152661145-f441271b-6ca3-4e8a-9299-9f54353d725b.png)


