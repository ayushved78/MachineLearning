# MachineLearning
<hr/>
<h3>#<a href="https://github.com/ayushved78/MachineLearning/tree/master/Data%20Preprocessing"> Data Preprocessing </a></h3>
<p>Steps for perfrming Data Preprocessing:<ol>
  <li> Importing the libraries </li>
  <li> Importing Dataset</li>
  <li> Handling the missing data in Dataset</li>
  <li> Encoding</li>
    <ul>
      <li> Caegorical/Independed Data (not used for prediction) </li>
      <li> Depended Data (used for prediction) </li>
    </ul>
  <li> Split, Train and Test </li>
  <li> Feature Scaling</li>
</ol></p>
<br/>
<hr/>
<h3>REGRESSION</h3>
<p>The branch of Machine Learning which aims over prediction of continuous data/numbers.</p>
<hr/>
<h3>#<a href="https://github.com/ayushved78/MachineLearning/tree/master/Simple%20Linear%20Regression"> Simple Linear Regression </a></h3>
<p> Used for data having only one feature (I.D)</p>
<p><strong>equation:</strong> <em> y = b0 + b1 * x </em></p>
<p>where,</p>
    b0 -> constant,
    b1 -> coefficient,
    x  -> independent variable,
    y  -> dependent variable
</p>
<br/>
<p> Steps to perform SLR:
<ol>
  <li> Importing the libraries </li>
  <li> Importing the Dataset</li>
  <li> Splitting the Training and Testing data</li>
  <li> Training SLR over the Training Set</li>
  <li> Predicting the Test Results (FIT)</li>
  <li> Visualisation of Training Set Data (PYPLOT)</li>
  <li> Visualisation of Testing Set (PYPLOT)</li>
</ol></p>
<hr/>
<h3>#<a href="https://github.com/ayushved78/MachineLearning/tree/master/Multiple%20Linear%20Regression"> Multiple Linear Regression </a></h3>
<p> Used for data having more than one feature (I.D)</p>
<p><strong>equation:</strong> <em> y = b0 + b1*x1 + b2*x2 + b3*x3 +......+ bn*xn</em></p>
<p>where,</p>
    b0 -> constant,
    b1,b2,b3,b4,....bn -> coefficient,
    x1,x2,x3,x4.....xn  -> independent variable,
    y  -> dependent variable
</p>
<p> It has 5 major methods to build a model, as mentioned belwo:</p>
<ol>
  <li> All-in</li>
  <li> Backward Elimination</li>
  <li> Forward Selection</li>
  <li> Bidirectional Elimination</li>
  <ul>
    <li> Not much used as Python provides libraries which already perform this operation</li>
  </ul>
  <li> Score Comparision</li>
</ol>
<br/>
<p>Steps to perform MLR:
<ol>
  <li> Importing the libraries </li>
  <li> Importing the Dataset</li>
  <li> Encoding the categorical data</li>
  <li> Splitting the Training and Testing data</li>
  <li> Training MLR over the Training Set</li>
  <li> Predicting the Test Results (FIT)</li>
</ol></p>
<hr/>
<h3>#<a href="https://github.com/ayushved78/MachineLearning/tree/master/Simple%20Linear%20Regression"> Polynomial Linear Regression </a></h3>
<p> Same like the Linear Regression but with a better prediction over salary</p>
<p><strong>equation:</strong> <em> y = b0 + b1 * x1 + b2 * x1 ^ 2 + b3 * x1 ^ 3 + b4 * x1 ^ 4 + .... + bn * x1 ^ n </em></p>
<p>where,</p>
    b0 -> constant,
    b1,b2,b3,....,bn -> coefficient,
    x1  -> independent variable,
    y  -> dependent variable
</p>
<br/>
<p> Steps to perform SLR:
<ol>
  <li> Importing the libraries </li>
  <li> Importing the Dataset</li>
  <li> Training Linear Regression over dataset (linear_model | LinearRegression)</li>
  <li> Training Polynomial Regression over dataset (preprocessing | PolynomialFeatures)</li>
  <li> Visualisation of LR result (PYPLOT)</li>
  <li> Visualisation of PR result (PYPLOT)</li>
  <li> Visualisation of PR result for  higher resolution(PYPLOT)</li>
  <li> Predicting new LR result (will be low)</li>
  <li> Predicting new PR result (more accurate and better)</li>
</ol></p>
<hr/>
