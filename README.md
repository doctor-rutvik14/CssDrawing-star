# CssDrawing-star
How to create a Star shape in css? 

We can create star by combining 2 triangles, one triangle as it is and one upside down.
So, let's start how to make a triangle:

◙ Let's insight 

    ○ Think about a rectangle.
    
    ○ The rectangle has a border-bottom.
    
    ○ It also has the other borders such as border-left and border-right.
    
![](https://raw.githubusercontent.com/doctor-rutvik14/CssDrawing-star/master/Images/pic1.jpg)

    ○ Notice how the borders are intersecting each other at a particular angles.
    
    ○ Now, reducing to zero width and zero height. We'll get such kind off shape

![](https://raw.githubusercontent.com/doctor-rutvik14/CssDrawing-star/master/Images/pic2.jpg)

    ○ Changing the background of the rectangle to transparent, border left to transparent, 
    which is currently brown in color and changing border right to transparent which is
    currently blue in color.
    
    ○ Will lead us getting a triangle shape as shown below. 
    
![](https://raw.githubusercontent.com/doctor-rutvik14/CssDrawing-star/master/Images/pic3.jpg)

How to create upside down triangle: The whole procedure is same instead of using border-bottom you have to use border-top.

Now, getting back on how to make a star. After creating a triangle and upside down triangle it's time to merge them. 
Here, we have to use ::before selector to create an upside-down triangle before the normal triangle shape.
The ::before selector inserts something before the content of each selected element.
