Download Link: https://assignmentchef.com/product/solved-math4387-homework-3
<br>
<h1>Problem 1</h1>

Download the <sub>simu_hw3.txt </sub>data from canvas and read it in R. The data has four columns <sub>x1, x2, x3 </sub>and y. Print the summary of the linear regression model

<em>y </em>= <em>β</em><sub>0 </sub>+ <em>β</em><sub>1</sub><em>x</em><sub>1 </sub>+ <em>β</em><sub>2</sub><em>x</em><sub>2 </sub>+ <em>β</em><sub>3</sub><em>x</em><sub>3 </sub>


<ul>

 <li>Is there something that surprise you? What it is?</li>

 <li>Why do you thing it might happend? Justify your answer. (You can use plots or some statistic for justification.)</li>

 <li>What model do you recommend? Run the recommended model and print the summary.</li>

</ul>

<h1>Problem 2</h1>

Fit <em><sub>y </sub></em>= <em><sub>β</sub></em><sub>0 </sub>+ <em><sub>β</sub></em><sub>1</sub><em><sub>x</sub></em><sub>1 </sub>model and populate the following table without using the <sub>anova </sub>function.

<table width="154">

 <tbody>

  <tr>

   <td width="107">Source             SS</td>

   <td width="27">df</td>

   <td width="20">MS</td>

  </tr>

  <tr>

   <td width="107"><em>SS</em><em>reg</em>(<em>X</em>1) RSS(<em>X</em><sub>1</sub>) TSS</td>

   <td width="27"> </td>

   <td width="20"> </td>

  </tr>

 </tbody>

</table>

SS, <sub>df</sub>, and <sub>MS </sub>represent the sum of squares, degrees of freedom, and mean sum of squares, respectively. <sub>MS </sub>= SS/df.

<h1>Problem 3</h1>

Fit <em><sub>y </sub></em>= <em><sub>β</sub></em><sub>0 </sub>+ <em><sub>β</sub></em><sub>1</sub><em><sub>x</sub></em><sub>1 </sub>+ <em><sub>β</sub></em><sub>2</sub><em><sub>x</sub></em><sub>2 </sub>model. Now, if you want, you can use the <sub>anova </sub>function.

<table width="177">

 <tbody>

  <tr>

   <td width="130">Source                    SS</td>

   <td width="27">df</td>

   <td width="20">MS</td>

  </tr>

  <tr>

   <td width="130"><em>SS</em><em>reg</em>(<em>X</em>1<em>,X</em>2) RSS(<em>X</em><sub>1</sub><em>,X</em><sub>2</sub>)TSS</td>

   <td width="27"> </td>

   <td width="20"> </td>

  </tr>

 </tbody>

</table>

<h1>Problem 4</h1>

Define <em>SS<sub>reg</sub></em>(<em>X</em><sub>2</sub><em>|X</em><sub>1</sub>) = <em>RSS</em>(<em>X</em><sub>1</sub>)<em>−RSS</em>(<em>X</em><sub>1</sub><em>,X</em><sub>2</sub>). <em>SS<sub>reg</sub></em>(<em>X</em><sub>2</sub><em>|X</em><sub>1</sub>) is called the extra sum of squares. Calculate <em>SS<sub>reg</sub></em>(<em>X</em><sub>2</sub><em>|X</em><sub>1</sub>). Can you write <em>SS<sub>reg</sub></em>(<em>X</em><sub>2</sub><em>|X</em><sub>1</sub>) in terms of <em>SS<sub>reg </sub></em>of the above models?

1

<h1>Problem 5</h1>

The dataset <sub>teengamb </sub>from <sub>faraway </sub>package concerns a study of teenage gambling in Britain. Fit a regression model with the expenditure on gambling as the response and the sex, status, income and verbal score as predictors. Present the output.

<ul>

 <li>What percentage of variation in the response is explained by these predictors?</li>

 <li>Which observation has the largest (positive) residual? Give the case number.</li>

 <li>Compute the mean and median of the residuals.</li>

 <li>Compute the correlation of the residuals with the fitted values.</li>

 <li>Compute the correlation of the residuals with the income.</li>

 <li>For all other predictors held constant, what would be the difference in predicted expenditure on gambling for a male compared to a female?</li>

</ul>

<h1>Problem 6</h1>

In this question, we investigate the relative merits of methods for computing the coefficients. Generate some artificial data by:

x&lt;-1<strong>:</strong>20 y &lt;- x<strong>+ </strong><strong>rnorm</strong>(20)

Fit a polynomial in <em><sub>x </sub></em>for predicting <em><sub>y</sub></em>. Compute <em><sub>β</sub></em>ˆ in two ways — by <sub>lm() </sub>and by using the direct calculation described in the chapter. At what degree of polynomial does the direct calculation method fail? (Note the need for the <sub>I() </sub>function in fitting the polynomial, that is, <sub>lm(y ~ x + I(xˆ2))</sub>.

<h1>Problem 7</h1>

The dataset <sub>prostate </sub>in the <sub>faraway </sub>package comes from a study on 97 men with prostate cancer who were due to receive a radical prostatectomy. Fit a model with <sub>lpsa </sub>as the response and <sub>lcavol </sub>as the predictor. Record the residual standard error and the <em>R</em>2. Now add lweight, svi, lbph, age, lcp, pgg45 and gleason to the model one at a time. For each model record the residual standard error and the <em><sub>R</sub></em><sup>2</sup>. Plot the trends in these two statistics.