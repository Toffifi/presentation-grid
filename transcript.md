Slide 1.1

Hi! My name is Aleksandra and today I want to talk about CSS grid. 
CSS Grid Layout is completely changing the game for web design. It allows us to create complex layouts on the web, using simple CSS.

Slide 1.2

CSS Grid Layout is a two-dimensional grid system that is native to CSS. It is a web standard, just like HTML, and it works in all modern browsers. So if u don’t stack with internet explorer 11 support, there are no reasons for u to avoid this technology. With CSS Grid Layout you can create precise layouts for the web.

Slide 1.2

Like this, for example. It is a beautiful markup and u can imagine how painful it is to implement it. But It is pretty simple if u will use grid layout and we can create something like that in 5 minutes.

Slide 2.1

Ok. And if we want to deal with this, we need to learn a couple of sings. Let's go through the basics of grid layout. I created some simple markup to show u how it works. We have a container and a few items inside. I filld them with different colors for illustrative purposes.

Slide 2.2

When we add display grid property for the container, nothing will change. Basically, it works like display block. But this div already has it, and we need add smt more to do the magic. 

Slide 2.3

Obviously, we need rows and columns to create a grid. To define their numder we can use grid template rows and grid template columns properties, which accept width and height as values. Grid will create as many rows and columns, as many values u provide. We can use any units of measurement, like px, %, em, or we can use 'auto' to fill remaining space.

Slide 2.4

Let's check our example.  I used special grid unit of measurement called a fraction. Here we have 3 columns 1 fraction each and 2 rows, 1 fration and 2 fractions. And I added the container height to make the example more visible. As u can see, grid filled the container with 3 equal columns. As for rows, we have 2 of them, one third and two third of the container. If we change the container size, the ratio  will remain the same.

Slide 2.5

This code works exactly the same as the previous one. But we used a special repeat function to create the certain amount of equal columns or rows. It can help u to avoid writing a similar code if u have a lot of equal values. Later on, u will see that grid system was designed to make your code shorter and cleaner.
One of the major advantage of grid layout is the ability to control each element size working only with a container.
But sometimes we want one element to fill several cells and we need to work directly  with element. 

Slide 2.6

For example, we want to spread an item over the whole row. Here u can see the lines which we can use to decide on the begin and the end of the item. Grid has grid column or row start and grid column or row end properties for this.

Slide 2.7

Here we moved and stretched the 4's element.  Right now it locates from the second line to the 4's line. And for the first item we used short expression which works exactly the same and we stretch it from the first line to the third line.

Slide 2.8

We need to work with the container again to create space between items. It can be easily done by adding grid gap property. Here we add a gap of 5 px and it would remain the same on any display resolution.

Slide 3.1

Ok. Do u remember the layout from our example? And now we know enough to make it. We have difficult markup which can be done only using position absolute and this implementation would be complicated and confusing. And right now, when we know grid layout basics, I think it became clear how easy it can be done and it wont take more then 5 minutes. 

Slide 3.2

We need 6 elements to create this layout because we have 6 pictures. U can imagine any content inside this items it doesn't matter. And I already add a container height and grid gap.

Slide 3.3

Now we need to know location of elements. For this purpose we draw the grid on the layout. As u can see we have 3 rows. 2 of them are identical and the third is twice the size. Speaking about the columns, we have 4 of them and their size are equal so we can use repeat function.

Slide 3.4

Let's apply this changes. Right now it doesn't look the right way. As u can see, our items don’t fill the container, because we have a lot more cells then items. I also added a borer property to the container, so u can see the actual container size. As u understand, we need to decide how to spread our items.

Slide 3.5

I hope u remember that we used lines to measure the items size. Here we draw the lines on our layout and now we can easily find the start and the end of grid item. As u can see, our first element has grid-row start on the first line, and the end on the third line. The same, for columns. We will use short expression.

Slide 3.6

I analyzed other items in the same way. And now we have the right layout . As I promised It took less then 5 minutes and just a couple lines of code. In this way, u can create layout of any complexity using this technology.

Slide 4

Ok. That was all I wanted  to say about css grid. I think it is pretty amazing technology and I like to use it a lot. Thanks for watching :)
