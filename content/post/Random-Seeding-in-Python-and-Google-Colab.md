---
title: "Random Seeding in Python and Google Colab"
date: 2022-07-09T16:59:09-07:00
---

hi everyone in this video i'm going to be talking about the random seating using numpy and pytorch in python and in google collab now randomness in nature is pretty challenging to control and it's practically impossible to recreate it but in numpy and python in computer generate you can set the seating so that you can recreate that randomness state again and again and again why do we want to do that and programming the reason is that for example if you do deep learning you have a model and you have you know you optimize your model using you know some randomness uh optimization um now you're gonna want to have the ability to recreate a state so that for example some other programmer researcher would come in there take a look at your model try to recreate that and try to for example reproduce it or to extend it right there so that's there needs to be a way to set the seating so that you can create that randomness state again later on and if you take a look at the collab notebook again right the first thing we do is import numpy and pi torch right there you can set the seating and numpy for example right here the first thing i want the first thing i'm doing right here is i'm setting the precision print option precision to two so that when it print out i just print out two digits right here precision so it looks nicer and the next thing i do is that i use the render random random run-in method in the random numpy library to produce a random a number um and i store that in the numbers variable right here and then i print this number right here now you can see right here right if i go to another one uh it's given it will give me a different random set each time so this one is 0.1316 but if you set the c right here for example i'm choosing 23. there's nothing particular about 23 maybe it's michael jordan number uh right there but i'm choosing the number 23 right here right and then if i print the same if i print the same random uh number again it will you see right here right they're just gonna repeat the same set of number by setting the seed right here by seating it right here okay see right there right there and right there now there's another way uh a newer method no way to do the random random seating in the numpy and that is to use the random state um set the random state to for example in this in this example right here i'm setting it to 90210 that's just the uh the the title of tv series and also to be happened to be the zip code of beverly hills um so i'm setting the random state and i started a variable state right here okay i'm uh right here right so now every time that you want to you know reproduce that random that random state right there you could just say state not ran and a see right here right and then you know that it run the same again and again and again the advantage of this is that you can localize your random state right here so you notice that you can also use the np dot random dot run and a right here right and every time you run it uh it will change to different numbers right there right gentle different number but these two right here stay fixed right there so there's advantage of precisely setting the seating random seating so that it's localized to a particular state right there finally you can also um uh do a setting the random seating in pi torch and do a random you know in pi torch right here and you can set also the print option precision in this situation i set it to one okay so if you take a look at the seed right here i set it again to 23 and then here i can you can see right here right each time i since i didn't set the c each time i run it it's gonna give me a different number but once i set the c right here it's just gonna repeat the same number again and again again so right here so this is right here this video is just a little example of random setting at random seating and setting the random state in uh codelab in python i hope this helped if you liked the video please give a thumb up give a hug comment subscribe thank you and have a good day

{{< youtube ElosoekoGCo >}} 


[Google Colab Notebook of Random Seeding](https://colab.research.google.com/drive/1lXArOU9tp7sIAm0KoH1m1Sx-2wIK3RbR?usp=sharing) . 


![Colab Picture 1 of Random Seeding](/img/seeding-01.jpg)
![Colab Picture 2 of Random Seeding](/img/seeding-02.jpg)