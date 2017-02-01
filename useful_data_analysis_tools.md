
# pandas

- [`pd.merge`](http://pandas.pydata.org/pandas-docs/stable/merging.html#)
- [`pd.concat`](http://pandas.pydata.org/pandas-docs/stable/generated/pandas.concat.html)


# web data parsing

our work-flow:

 `base_url` + `params_dict`  --> `rq.get(base_url,params=params_dict)` -->   

`bs4.BeautifulSoup(form_source.text, "html.parser")` -->   

`result_soup.find_all('table')[0]` --> `pd.read_html(result_table.decode())[0]`

# applied ML

- [SK-learn notebooks](https://github.com/justmarkham/scikit-learn-videos), in particular:
	- [example of K-nn](https://github.com/justmarkham/scikit-learn-videos/blob/master/04_model_training.ipynb)

	- [linear regression](https://github.com/justmarkham/scikit-learn-videos/blob/master/06_linear_regression.ipynb)

	- [cross-validation](https://github.com/justmarkham/scikit-learn-videos/blob/master/07_cross_validation.ipynb)

	- [evaluate classifier](https://github.com/justmarkham/scikit-learn-videos/blob/master/09_classification_metrics.ipynb)

	- [hyper-parameters optimization](https://github.com/justmarkham/scikit-learn-videos/blob/master/08_grid_search.ipynb)

	



# bokeh

- [example](https://nbviewer.jupyter.org/github/bokeh/bokeh-notebooks/blob/master/gallery/glucose.ipynb)
 the [official gallery](https://github.com/bokeh/bokeh-notebooks)



