# MapLinksPlot

<p align="center">
<img height=100 src="images/logo.PNG" alt="geosnap"/>
</p>

<h2 align="center" style="margin-top:-10px">MapLinksPlot is an an open-source JavaScript-based mapping tool that enables linking multiple maps and various charts.</h2> 

## QuickStart
### MapLinksPlot_JS
&nbsp;&nbsp;&nbsp;&nbsp;For Javascript users, example visaulizations are available in the two folders below:<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;JS_Quantitative_Data_VIZ<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;JS_Categorical_Data_VIZ<br/>
### MapLinksPlot_PYTHON
&nbsp;&nbsp;&nbsp;&nbsp;For python users, example visaulizations are available in the two folders below:
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;PYTHON_Quantitative_Data_VIZ/Adaptive_Choropleth_Mapper.ipynb
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;PYTHON_Categorical_Data_VIZ/Qualitative_Analysis_Mapper.ipynb
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;PYTHON_Categorical_Data_VIZ/Neighborhood_Analysis_Mapper.ipynb
## CyberGISX
&nbsp;&nbsp;&nbsp;&nbsp;You can run LinksPlot_PYTHON in your Jupyter Notebook installed in your PC as well as in CybearGISX.<br/>
&nbsp;&nbsp;&nbsp;&nbsp;To use it in CyberGISX, follow steps below:
1. If you do not have a CyerGISX account, create a CyberGISX an account with your GitHub id at https://cybergisxhub.cigi.illinois.edu
2. Open up the CyberGIX, click the "new" button on the top right corner, and select python3 and enter the command line below to download MapLinksPlot.
```bash
	!git clone https://github.com/suhanmappingideas/MapLinksPlot
```    
3. Follow insturctions in Install_geosnap.ipynb.
4. Uncomment out the code below:

```bash  
	#This is for CyberGISX. Uncomment two command lines below when you run in CyberGIX Environment
	#local_dir1 = servers1 + cwd 
	#local_dir2 = servers2 + cwd
```   
&nbsp;&nbsp;&nbsp;&nbsp;in the python code below: <br/>

```bash  
	PYTHON_Quantitative_Data_VIZ/Adaptive_Choropleth_Mapper.py 
	PYTHON_Quantitative_Data_VIZ/Qualitative_Analysis_Mapper.py  
	PYTHON_Categorical_Data_VIZ/Neighborhood_Analysis_Mapper.ipynb
``` 
 
## Visualization Modules
To be updated...
## Built With

* [Leaflet](https://leafletjs.com) - Used to make maps
* [PlotlyJS](https://plot.ly/javascript/) - Used to make charts
* [D3](https://d3js.org/) - Used to make charts


## Authors

MapLinksPlot was originally developed by Su Yeon Han, Sergio Rey, Elijah Knaap, Wei Kang, and other members at the Center for Geospatial Sciences at the University of California, Riverside, and is also updated by members at the CyberGIS Center.


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Funding

<img src="images/nsf_logo.jpg" width=100 /> This project was supported by NSF Award #1733705,
[Neighborhoods in Space-Time Contexts](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1733705&HistoricalAwards=false) and is currenty supported by NSF Award #1743184,
[SI2-S2I2 Conceptualization: Geospatial Software Institute](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1743184). Any opinions, findings, and conclusions or recommendations expressed on the site are those of the author(s) and do not necessarily reflect the views of the National Science Foundation.




