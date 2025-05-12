# ee5907pr-assignment-1-solved
**TO GET THIS SOLUTION VISIT:** [EE5907PR Assignment 1 Solved](https://www.ankitcodinghub.com/product/ee5907pr-assignment-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91269&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EE5907PR Assignment 1 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Data Description

The data is an email spam dataset, consisting of 4601 email messages with 57 features. Feature descriptions are found in this link. We have divided the data into a training set (3065 emails) and test set (1536 emails) with accompanying labels (1 = spam , 0 = not spam).

Data Processing

One can try different preprocessing of the features. Consider the following separately:

<ol>
<li>(a) &nbsp;log-transform: transform each feature using log(xij + 0.1) (assume natural log)</li>
<li>(b) &nbsp;binarization: binarize features: I(xij &gt; 0). In other words, if a feature is greater than 0, it’s simply set to 1. If it’s less than or equal to 0, it’s set to 0.</li>
</ol>
Q1. Beta-binomial Naive Bayes

Fit a Beta-Binomial naive Bayes classifier on the binarized data from the Data Processing section. Since there are a lot of spam and non-spam emails, you do not need to assume any prior on the class label. In other words, the class label prior λ can be estimated using ML and you can use λML as a plug-in estimator for testing.

On the other hand, you should assume a prior Beta(α, α) on the feature distribution (note that the two hyperparameters for the Beta prior are set to be the same). For each value of α = {0, 0.5, 1, 1.5, 2, · · · , 100}, fit the classifier on the training data and compute its error rate (i.e., percentage of emails classified wrongly) on the test data. For the features (i.e., when computing p(x|y)), please use Bayesian (i.e., posterior predictive) training and testing (see week 3 lecture notes on “Predicting Target Class of Test Data x ̃ Using Posterior Predictive Distribution”).

Make sure you include at least the following in your report:

• Plots of training and test error rates versus α

• What do you observe about the training and test errors as α change? • Training and testing error rates for α = 1, 10 and 100.

Q2. Gaussian Naive Bayes

Fit a Gaussian naive Bayes classifier on the log-transformed data from the Data Processing section. Since there are a lot of spam and non-spam emails, you do not need to assume any prior on the class label. In other words, the class label prior λ can be estimated using ML and you can use λML as a plug-in estimator for testing.

For this exercise, just use maximum likelihood to estimate the class conditional mean and variance of each feature and use ML estimates as a plug-in estimator for testing (see week 3 lecture notes on “ML estimation of μ,σ2” and “Predicting Target Class of Test Data x ̃” for Strategies 1 and 2) . Make sure you include the following in your report:

• Training and testing error rates for the log-transformed data.

2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Q3. Logistic regression

For the log-transformed data, fit a logistic regression model with l2 regularization (see week 4 lecture notes on “Newton’s Method for Logistic Regression” and “Exclude Bias from l2 Regular- ization”). For each regularization parameter value λ = {1, 2, · · · , 9, 10, 15, 20, · · · , 95, 100} (note the jump in interval from 10 to 15 and beyond), fit the logistic regression model on the training data and compute its error rate (i.e., percentage of emails classified wrongly) on the test data. Make sure you include at least the following in your report:

• Plots of training and test error rates versus λ

• What do you observe about the training and test errors as λ change? • Training and testing error rates for λ = 1, 10 and 100.

Don’t forget to include the bias term in the logistic regression and your l2 regularization should not apply to the bias term.

Q4. K-Nearest Neighbors

For the log-transformed data, implement a KNN classifier (see week 5 lecture notes on “Non- parametric Classification”). Use the Euclidean distance to measure distance between neighbors. For each value of K = {1,2,··· ,9,10,15,20,··· ,95,100} (note the jump in interval from 10 to 15 and beyond), compute the training and test error rates (i.e., percentage of emails

classified wrongly). Make sure you include at least the following in your report:

• Plots of training and test error rates versus K

• What do you observe about the training and test errors as K change? • Training and testing error rates for K = 1, 10 and 100.

Q5. Survey

Please give an estimate of how much time you spent on this assignment. Note that you will not be given a higher or lower grade if you spend a lot of time or very little time. We just want an honest estimate. Other feedback are welcomed. Please note that regardless of positive or negative feedback, your grades won’t be affected of course. In other words, as long as your report does not leave this section blank, you will get the full 4%.

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
