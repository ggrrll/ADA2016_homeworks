
# pandas

- [`pd.merge`](http://pandas.pydata.org/pandas-docs/stable/merging.html#)
- [`pd.concat`](http://pandas.pydata.org/pandas-docs/stable/generated/pandas.concat.html)


# web data parsing

our work-flow:

`base_url` + `params_dict`  --> `rq.get(base_url,params=params_dict)` -->   

`bs4.BeautifulSoup(form_source.text, "html.parser")` -->   

`result_soup.find_all('table')[0]` --> `pd.read_html(result_table.decode())[0]`



# applied ML


- our pipeline to build and test a classifier, used in [this notebook](https://github.com/ggrrll/tatoule/blob/master/04%20-%20Applied%20ML/1-hw4_applied_ml.ipynb):

	- `from sklearn.ensemble import RandomForestClassifier`

	- `from sklearn.model_selection import cross_val_score`

	- `from sklearn.model_selection import GridSearchCV`

	-  `from sklearn.model_selection import learning_curve` 


	
- [SK-learn notebooks](https://github.com/justmarkham/scikit-learn-videos), in particular:
	- [example of K-nn](https://github.com/justmarkham/scikit-learn-videos/blob/master/04_model_training.ipynb)

	- [linear regression](https://github.com/justmarkham/scikit-learn-videos/blob/master/06_linear_regression.ipynb)

	- [cross-validation](https://github.com/justmarkham/scikit-learn-videos/blob/master/07_cross_validation.ipynb)

	- [evaluate classifier](https://github.com/justmarkham/scikit-learn-videos/blob/master/09_classification_metrics.ipynb)

	- [hyper-parameters optimization](https://github.com/justmarkham/scikit-learn-videos/blob/master/08_grid_search.ipynb)


# data VIZ 

## folium

[our notebook](https://nbviewer.jupyter.org/github/ggrrll/tatoule/blob/master/03%20-%20Interactive%20Viz/2-Map-Viz.ipynb) with folium for ADA lab 3, and
[folium git hub](https://github.com/python-visualization/folium) 

## bokeh

- [example](https://nbviewer.jupyter.org/github/bokeh/bokeh-notebooks/blob/master/gallery/glucose.ipynb)
 the [official gallery](https://github.com/bokeh/bokeh-notebooks)



