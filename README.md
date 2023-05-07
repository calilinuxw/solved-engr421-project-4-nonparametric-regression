Download Link: https://assignmentchef.com/product/solved-engr421-project-4-nonparametric-regression
<br>
<span class="kksr-muted">Rate this product</span>

In this homework, you will implement three nonparametric regression algorithms in Matlab, Python, or R. Here are the steps you need to follow:

<ol>

 <li>Read Section 8.8 from the textbook.</li>

 <li>You are given a univariate regression data set, which contains 133 data points, in the file named hw04_data_set.csv. Divide the data set into two parts by assigning the first 100 data points to the training set and the remaining 33 data points to the test set.</li>

 <li>Learn a regressogram by setting the bin width parameter to 3 and the origin parameter to 0. Draw training data points, test data points, and your regressogram in the same figure. Your figure should be similar to the following figure.</li>

</ol>

h =3

training test

50 0 −50 −100

0 10 20 30 40 50 60 x

4. Calculate the root mean squared error (RMSE) of your regressogram for test data points. The formula for RMSE can be written as

! ∑ # $ % &amp; $ ( # ! $ #% ! ) ” !'( .

‘$%&amp;$

Your output should be similar to the following sentence.

<pre>  Regressogram =&gt; RMSE is 24.7260 when h is 3</pre>

5. Learn a running mean smoother by setting the bin width parameter to 3. Draw training data points, test data points, and your running mean smoother in the same figure. Your figure should be similar to the following figure.

y

h =3

training test

50 0 −50 −100

0 10 20 30 40 50 60 x

<ol start="6">

 <li>Calculate the RMSE of your running mean smoother for test data points. Your output should be similar to the following sentence.<pre>  Running Mean Smoother =&gt; RMSE is 23.8403 when h is 3</pre></li>

 <li>Learn a kernel smoother by setting the bin width parameter to 1. Draw training data points, test data points, and your kernel smoother in the same figure. Your figure should be similar to the following figure.</li>

</ol>

h =1

training test

50 0 −50 −100

0 10 20 30 40 50 60 x

8. Calculate the RMSE of your kernel smoother for test data points. Your output should be similar to the following sentence.

<pre>     Kernel Smoother =&gt; RMSE is 24.1672 when h is 1</pre>