# Wine Quality Analysis
# Red Wine 
<h3> Acidity Study </h3>

<p align="center">
  <img width="250" height="250" src="https://github.com/ShamimaMoni/wine-quality-analysis/blob/master/Red%20Wine/images/tartaricaciddistribution.png">
  <img width="250" height="250" src="https://github.com/ShamimaMoni/wine-quality-analysis/blob/master/Red%20Wine/images/aceticaciddistribution.png">
  <img width="250" height="250" src="https://github.com/ShamimaMoni/wine-quality-analysis/blob/master/Red%20Wine/images/citricaciddistribution.png">
  
</p>

Tartaric Acis has almost normal distribution. Wines having tartaric acid concentration greater than 14 is very low. Also wines having acetic acid concentration greater than 1.05 is very low though the range is about 1.6.

But Acetic Acid and Citric Acid does not have a normal distribution. To see if there is any normality, log10(Acetic Acid) vs Grade and log10(Citric Acid) vs Grade is plotted.

<p align="center">
  <img width="250" height="250" src="https://github.com/ShamimaMoni/wine-quality-analysis/blob/master/Red%20Wine/images/aceticacidlogdistribution.png">
  <img width="250" height="250" src="https://github.com/ShamimaMoni/wine-quality-analysis/blob/master/Red%20Wine/images/citricacidlogdistribution.png">
  
</p>

Still no normality is not seen in citric acid concentration histogram rather there are a lots of peaks which is bad. But acetic acid concentraion histogram shows a right skewed log-normal distribution.

<h3> Tartaric Acid </h3>
Now let's break the Tartaric Acid Value and see what's in there. The boxplot of tartaric acid concentration greater than anf less than 14 for different grade is given below:

<p align="center">
  <img width="250" height="250" src="https://github.com/ShamimaMoni/wine-quality-analysis/blob/master/Red%20Wine/images/tartaricgreater14.png">
  <img width="250" height="250" src="https://github.com/ShamimaMoni/wine-quality-analysis/blob/master/Red%20Wine/images/tartaricless14.png">
  
</p>
Nobody gave 3,4 or 8 rating for Tartaric Acid greater than 14 and there are no outliers for 3,7 or 8 rating for tartaric acid less than 14.

<h3> Acetic Acid </h3>
Now let's break the Acetic Acid Value and see what's in there. The boxplot of acetic acid concentration greater than anf less than 1.05 for different grade is given below:

<p align="center">
  <img width="250" height="250" src="https://github.com/ShamimaMoni/wine-quality-analysis/blob/master/Red%20Wine/images/aceticgreater1.05.png">
  <img width="250" height="250" src="https://github.com/ShamimaMoni/wine-quality-analysis/blob/master/Red%20Wine/images/aceticless1.05.png">
  
</p>
Nobody gave 6,7 or 8 rating for acetic Acid greater than 1.05 and there are no outliers for 3,4 or 8 rating for acetic acid less than 1.05.

<h3> Acidity vs Grade </h3>
<p align="center">
  <img width="250" height="250" src="https://github.com/ShamimaMoni/wine-quality-analysis/blob/master/Red%20Wine/images/tartaricacidboxplot.png">
  <img width="250" height="250" src="https://github.com/ShamimaMoni/wine-quality-analysis/blob/master/Red%20Wine/images/aceticacidboxplot.png">
  <img width="250" height="250" src="https://github.com/ShamimaMoni/wine-quality-analysis/blob/master/Red%20Wine/images/citricacidboxplot.png">
  
</p>

From the boxplots, we can see that the rating increases with the increase in citric acid concentartion and with the decrease in acetic acid concentration. Tartaric acid concentration has almost no effect on the grade of the wine.

<p align="center">
  <img width="250" height="250" src="https://github.com/ShamimaMoni/wine-quality-analysis/blob/master/Red%20Wine/images/acetictartaric.png">
  <img width="250" height="250" src="https://github.com/ShamimaMoni/wine-quality-analysis/blob/master/Red%20Wine/images/citricacetic.png">
  <img width="250" height="250" src="https://github.com/ShamimaMoni/wine-quality-analysis/blob/master/Red%20Wine/images/citrictartaric.png">

Acetic and Tartaric as well as Citric and Acetic acid has an inversely proportional relationship whereas Citric anmd Tartaric Acid has a proportional relationship.
