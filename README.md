# Iowa Employment

IA-Jobs is a repo hosting some a la carte data visualization from Iowa's Open Data website.

  - Type some Markdown on the left
  - See HTML in the right
  - Magic

Dataset description from the **Iowa Open Data** website [here.](https://data.iowa.gov/Economy/Iowa-Seasonally-Adjusted-Non-Farm-Employment-by-Mo/sxz8-4swt)
> This dataset provides final seasonally adjusted employment estimates for the State of Iowa. Iowa's estimate contained in this dataset is broken into the following "expanded" supersectors:
 * Goods-Producing: Construction, Manufacturing, and Mining and Logging 
 * Service-Providing: Education and Health Services, Financial Activities, Information, Leisure and Hospitality, Other Services, Professional and Business Services, Retail Trade, Transportation and Utilities, and Wholesale Trade 
 * Government: Federal Government, State Government, and Local Government

### Preview
![Alt text](https://raw.githubusercontent.com/ryan-p-larson/ia-jobs/master/animation.gif)


### Installation & Running
1. Run the makefile in the repo, this will use Curl to download the csv: ``make ia-jobs.csv``
2. Start a local server for d3.js, if you use Python 2 enter ``python -m SimpleHTTPServer 8888 &`` or Python 3 ``python -m http.server 8888 &``
3. Open a web browser and go to http://localhost:8888/index.html to see the results 


### Todos

 - Iterative relaxed label placemen (overlap)
 - xAxis zoom
 - Mouseover value solution
 - Add comments, clean code (ongoing)

License
----
MIT

**Free Software, Hell Yeah!**




