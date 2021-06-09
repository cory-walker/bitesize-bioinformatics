# bitesize-bioinformatics

This research file is an exploration into Bioinformatics of Acetylcholinesterase using the ChEMBL database, rdkit, and then testing multiple regression models at once using lazypredict.<br>

### General flow of the notebook

 <ul>
<li>Collect the data</li>
<li>Wrangle the data</li>
<li>Calculate Lipinski descriptors</li>
<li>Convert IC50 to pIC50</li>
<li>Visual exploratory analysis</li>
<li>Statistical analysis using Mann-Whitney U tests</li>
<li>Compare performance for 42 different ML models for pIC50 prediction</li>
 </ul>
 <br>
 Here is the original tutorial I learned from while developing the first draft of this project: <a href="https://www.youtube.com/watch?v=jBlTQjcKuaY">Python for Bioinformatics - Drug Discovery Using Machine Learning and Data Analysis</a><br><br>

## Libraries used

<i>This notebook was developed using Python 3.8</i>

<ul>
<li><a href="https://pandas.pydata.org/">pandas</a></li>
<li><a href="https://docs.python.org/3/library/os.html">os</a></li>
<li><a href="https://plotly.com/python/">plotly</a></li>
<li><a href="https://numpy.org/">numpy</a></li>
<li><a href="https://scikit-learn.org/stable/">sklearn</a></li>
<li><a href="https://www.scipy.org/">scipy</a></li>
<li><a href="http://www.rdkit.org/docs/">rdkit</a></li>
<li><a href="https://github.com/chembl/chembl_webresource_client">chembl_webresource_client</a></li>
<li><a href="https://pypi.org/project/lazypredict/">lazypredict</a></li>
</ul>
