<h4>Red Wine Quality Prediction</h4>

<h6>Description</h6>

The two datasets are related to red and white variants of the Portuguese "Vinho Verde" wine. For more details, consult the reference [Cortez et al., 2009]. Due to privacy and logistic issues, only physicochemical (inputs) and sensory (the output) variables are available (e.g. there is no data about grape types, wine brand, wine selling price, etc.).

These datasets can be viewed as classification or regression tasks. The classes are ordered and not balanced (e.g. there are much more normal wines than excellent or poor ones).

<h6>Data</h6>
winequality-red.csv

<h6>Features</h6>
For more information, read [Cortez et al., 2009].
Input variables (based on physicochemical tests):
<ol>
    <li>fixed acidity</li>
    <li>volatile acidity</li>
    <li>citric acid</li>
    <li>residual sugar</li>
    <li>chlorides</li>
    <li>free sulfur dioxide</li>
    <li>total sulfur dioxide</li>
    <li>density</li>
    <li>pH</li>
    <li>sulphates</li>
    <li>alcohol</li>
    <li>quality (score between 0 and 10) - output variable</li>
</ol>  

<h6>Type of Machine Learning Model Applied</h6>
Random Forest Classification Model

<h6>Performance Metric</h6>
F1-Score