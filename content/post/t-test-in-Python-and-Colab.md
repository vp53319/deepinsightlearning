---
title: "T Test in Python and Colab"
date: 2022-07-10T10:07:24-07:00
---

hi everyone in this video i'm going to be talking about the t test uh in python and collab now uh when you do an experiment like for example in deep learning and you have two models model a and model b and you want to see if model a is significantly different than model b then you're gonna then we're gonna need to have a way to test it if it is significantly different or is it not and the t-test give us the ability to do that now in order to let's take a look at the notebook right now in order to do the t-test we need to import the scipy stat library as that's right here and of course right we also import numpy as np you know for to populate the data and the method live to libraries to plot to visualize the data so the definition of a t-test is that if you have two population and you have their mean their average uh what you're gonna do is that you can take the difference of the two and you divide by the standard deviation right here so you know the mean x minus mean y divided by the standard deviation um and then of course square root of n will be important is the standard deviation right here so n in here is the number of times we run the experiment and the t-test can tell if one model is better or significantly better and uh better or significantly better than the order right there the t-test tell also tell you know another way of saying it is the t-test tell whether the alternative of hypothesis and the alternative hypothesis usually model a is it better than model b it's certificate different um and then

yeah the null hypothesis is that there's no difference you know between the two so the t-test tell if the hypot alternative hypothesis is better than the null hypothesis and usually the threshold value is 0.05 or 5 percent and the null hypothesis is assuming there's no difference so if the threshold the value for t is about point under or 0.05 under then yes the the hypoth the alternative hypothesis is different than the null hypothesis and here is the formula for the t-test written and written in the latex in in collab notice that there is there is the money symbol right here and n1 is simple and the uh then the formula is going into here so you know if you want you can learn more about latex and how to generate the formula in google collab and this cell right here by the way is using the text cell instead of the coding cell okay so here is an example of the t-test so i creating a sample population a and population b and and you know i give the number of data and a is 73 and 67 and then i'm generating a random number with mean a and mean b for population a and b respectively and then i

and then i called these stat t test of the scipy library and i i gave it population published a and b the order is not the the order does not make a difference what it do is that it will make this number right here minus or positive right here but the b um you know this test right here is going to return a tuple a t and a p right here okay and then the p1 is what is the one we're looking for right here so let's say right if i change it from b to a and i'll just right here right the side will change but the p-value is going to be

it's going to be positive and of course why because i'm doing a random sample right here every time i every time i do that it's gonna give me a different result okay so let me change this one right here let me see

five point one four see right there right so it's gonna give me a different number every time okay but notice that but notice that the um you know when you have the mean of one and one right a lot of time the p-value is going to be higher than the 0.05 right here so it's not statistically significant let's say right if i change it b to 2 right here

see right there right when you have a mean difference of one in this situation right here the um the p value is going to be under the 0.05 trestle so that is you know the statistical significant uh difference between the two model right here so you can change so you can play with this right here you can change the mean you can change the number uh and you can of course write because it's a random sample so every time you run it it's going to be a bit different let's say if i do instead of 2 i do 1.5 for example right there right so some sometimes when you do 1.5 for example right there right this one right here is statistic statistical significant uh that's a different under 0.05 but all the time it's not so the t the t squared you know the t test can tell uh whether the alternative hypothesis model a versus mode of b in this situation right here right is significantly different and the va threshold value usually 0.05 now there's another way to visualize the two population let's say right if i put it one and one right here

okay and you visualize that basically what i do is that i i plot you know all of the a on the zero for x zero right and then i plot on the b um and for x equal to one right here okay and then um i you know i mark population a and pop this population b right here and then this one right here give us the color for the marker and the shape of the marker right here this one is the star symbol blue and this one is the diamond uh yellow right there okay and then the w right here would give this marker a color in this situation it'd be one okay so this video uh give an example of the teeth test and

python and collab using the scipy library i hope this helped if you like it please give a thumb up you know give a hug comment and have a good day


{{< youtube OsFAUvy1S4k >}} 


[Google Colab Notebook of t-test](https://colab.research.google.com/drive/1WYjxnumCULNEnf60iCIIOKsGtGLIC1oz?usp=sharing) . 


![Colab Picture 1 of t-test](/img/ttest-01.jpg)
![Colab Picture 2 of t-test](/img/ttest-02.jpg)



