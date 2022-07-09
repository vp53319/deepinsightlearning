---
title: "Min Max Functions in Python and Colab"
date: 2022-07-08T19:44:32-07:00
---

hi everyone in this video i'm going to be talking about the min max functions and the argument and functions uh in numpy now the min and max function if you have a list or you have an nd array it will return the maximum or minimum value in the list uh it worked for matrix too but you know there's a couple variation in matrix that we have to pay attention a bit later the min max function and the admin and admire functions are useful because sometimes for example when you do deep learning you have a whole bunch of category like for example cat dog stop for example and then the model would return a probability value for each of those categories so we could want to find out which one give us the maximum probability at what index and the max and ackman are max and the function

helping us with finding out those probability and location of that probability or the category so if you take a look at the collab dot book right here you see that uh first of all i'll import the library numpy and python library to use um the next one i i did is that i create a numpy array with the density of the planet but you can see right here for example mercury have 5429 and the unit is kilogram per meter q and i place it in the variable planet density right here so you have the um the a planets plus pluto right here and then when you have the better density you can use the max function in numpy to find the the max value and the min function to find the min value right here and the arc max and r min admin would find the location index for this array right here and remember the index in python style with the value zero so if it sits in the second position that the index would be one because zero is the first and then second is one right there and so this one right here is printing out the index for the min and the max this you can see right here two and five so the max index is two so you go hd zero one two which is the density of earth right there and then the fifth one is the min right there right so zero one two three four five which is a density of saturn right there and coincidentally coincidentally if you have a bathtub making up to put saturn in there it would float because this density is lower than water okay um so you can see right here and you can test it out by printing out the uh the matrix element uh the array element uh planet density at the min index and it's gonna give us 687 which you can see right here 687 and the max index is 5514 and you can see right here right you go back to the planet's density it's going to be 5514 right here the next thing is that we can use index the min max augmented argument on a matrix two so right here i create a three by two matrix the first one is the just some some sample from distant to the sun in eu this one right here is jupiter saturn and uranus and the second row is uh gravity earth moon and mass right here you can see right here so you print down the planet info that's going to give us a 2 by 3 matrix right here okay and from that right there we can find you know we use numpy to find the min function and the max function down here to find the uh the min for the planet info what this would do right here if you don't specify the axis it's just gonna flatten everything out into a single line right here and it's gonna and it's gonna find out the minimum in that you know in that in that flattened line right there and it's going to print out right here which is 1.6 now if you

now if you want to you know do the axis you can specify the axis of 0 or x is one so if you if you try to do the min and you specify x is zero for example right here right it's gonna go this way uh this way vertically and then it's gonna look at this column right here and you can see it would see if we compare which one is smaller and it's going to pick that one because this is a min right here so you see 5.2 the next one is 1.6 right there and the next one would be 3.7 now if you could have access equal to 1 it's going to go across horizontally like this right here so in this row right here the smaller the smallest one will be 5.2 and on the second row the smallest one be 1.6 it's going to be one point b right here

so you can also do the max 2 right there right the max and if you if you take a look at that it's going to work out similarly that on the mac is 19.2 and you can do the max with access 0 axis 1 similar to what we just discussed in this example right here okay so you can see that because for to get the argument for the min right there okay if you don't specify an axis it's going to flatten the it's going to flatten the um it's going to flatten the matrix into one line okay let me delete right here because this is not relevant to our example so it's going to flatten the matrix and then it's going to find it's going to find the position in that flattened line that has the minimum so you should see right here right zero one two three four so zero one two three four so that's gonna give us a position of four right here now if we want to find out um uh the actual position of the matrix we have to unravel the index right here so you you pass in the um the argument right here and then you pass in the matrix that you want to unravel and it's going to give us a position of one and one so you can see right here right it's going to go to 0 1 and then it's going to go 0 1 which is 1.6 right here which is a min okay and then

and then we can also uh specify an axis zero or an axis one for admin and arc max right here okay so if you specify the uh argument and you give it an axis of one right here it's going to go to this way okay and then min is 5.2 which is position zero and that's zero one right and then here the second one is going to be 1.6 it's gonna be position one and this one right here is three point seven is gonna be position one okay and then if you're gonna go to uh if you do access equal to one and do arc max for example let's go look here and consider the maximum which is zero one two let's put it right there and let's look at the second row and the second it's gonna see 9.8 which is a position zero it's gonna put it right here okay we can also do the um uh min and max using tensor but the first thing we have to do we have to convert the array and the array to tensor type right there because uh the and the maximum of the pi chord library doesn't work well within the array it's gonna give us an error so when you convert it into a tensor you can pass this um this tensor into the um min and max uh function of pi torch and print it and yeah when you print it out it could give us the same right so this one right here is the converted planet info to tensor and then here is the max of this tensor and here's the min right there right and then the position of this um the position of the max is zero one two three four uh zero one two three four uh zero one two right zero one two right and the min is zero one 2 3 4 5 right here okay so max 0 1 2 and min 0 1 2 3 4 5

and then finally we can also work with matrix two two by two matrix in this situation for example and again right we also convert it into a tensor okay and then

and then here uh we find them in we find that vitamin when when we do the men like this right here it's gonna again write flatten without specifying axis it's going to flatten it's going to flatten the kind of tensor right here and it's going to look for the smallest value of all of this elements right here and then put it you know at 5.1.6 but if we specify the axis for example right here x is zero right here right then it's going to go into the column 5 9.8 pick out the min which is 5.2 go here second column and i find out the min which is 1.6 put it right here and then this one right here is 3.7 and for the max for example going uh x is equal to one which is going row across the row then this one right here the max would be 19.2 um actually it's a min right here too right here right so uh it would be 5.2 and then the second row it would be 1.6 right there so you can see that you can use the min max arcman x max function in numpy or pi torch to find you know to give you valuable information about the the tensor or the array or the list or the matrix that that you have right there so hope this helped for everyone understand about this function a little bit if you like it please share like give a hug comment and have a good day bye

{{< youtube g-IXQybTQRI >}} 


[Google Colab Notebook of Min Max Functions](https://colab.research.google.com/drive/1Z-IF7lGc8anDmnI3G853Bdgfs_KH0cbW?usp=sharing) . 


![Colab Picture 1 of Min Max](/img/min-01.jpg)
![Colab Picture 2 of Min Max](/img/min-02.jpg)
![Colab Picture 3 of Min Max](/img/min-03.jpg)
![Colab Picture 3 of Min Max](/img/min-04.jpg)