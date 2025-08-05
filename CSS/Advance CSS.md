August 2, 2025

**

# CSS Display 

  

A span element has a value that is called inline. 

- Displays an inline element when in text form. 
    
- Normally, most elements are blocks by default. 
    

  
  

We cannot set the width and the height of an inline element. However, we can do that in block display.

  

On the other hand, the inline block’s width and height can be set. 

  

The None display property sets any element to disappear. 

  

Experimenting on: [https://appbrewery.github.io/css-display/](https://appbrewery.github.io/css-display/) 

  

So block takes up the entire length, hence if you want to make your div box line up horizontally, I suggest using display = inline-block. Otherwise, use display = block so that they are aligned, vertically on the y-axis.

  

—

  

# CSS Float 

  

The float property allows text to wrap around a div or an element on a webpage. 

  
  

Float is the name of the property you can set the value to left, right, center, etc.

An example is that you can set the image to float to the left or right based on the value given to the float element. ![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXe8zhqluFxmqqSA3CwgLyhK1McIt42soQJYBY18qi7xtbA-DRYh9teWVL9HQUZiRB0XExAzRCc9zCGSRFhjP8XB3Ihx8l8qQRjLG0v-9SVV-1f30IiXuOb6MctwuvE74TqEQtmJZw?key=NUwC39JZhGkpBZduK8y5VQ)

  

An example, when an image is set to float on the left side of a website. 

  

But there is a case where we need a footer to take up the entire page at the bottom of the webpage. 

  

To achieve this, we are going to change the value of the footer to “clear: left”. It clears any responsibility for wrapping. It can go to its normal position and ignore everything around it. ![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXdKUR_c1boCP5Z_xomPKxvHYRB-NZGYzDCgru0K9Cit7Fb3ySHk1FZ7x3ie-AZ0Uy84yOIcCFVwRMKoYYeXLEzBJe51tJBqo1MWPKOgfLIslbYCoPzUHJ_NdAvDpvaXn_ke_0eHEQ?key=NUwC39JZhGkpBZduK8y5VQ)

Note: Only use float when you want to wrap text around an image. 

  
  

In modern web design or developing because there is much better tools for us. They can be very unexpected results. 

  

—

  

# Responsive Website

  

Make a website that is adaptable on the platform it occupies. 

  

Four main ways of doing this: 

### Media Queries - Something that you put in. Instead of a css selector. 
    

- We can define very various width. Tell the navigation bars to have different css layout. 
    

### CSS Grid 
    

- Harder to understand, yet more flexible.
    
- Create a div that contains five divs. That employees a class
    
- Containing divs that have different styles
    
- Set the display to grid. Where we define how the columns and rows are lay out. 
    
- Look at the image above. ![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXcK0cL0PkJj6eBhi2r8fSeW-z5ajQOlN3-L3l_vIEl8uCWRZvf2j4xVpuDlQ5z-H1hULYLPx_gCjwOGdqVJxKW-bLMlbRwatmAEcGzZIX_eRf1Al5k_O4OUBevfmm1Yf47OlcpXsg?key=NUwC39JZhGkpBZduK8y5VQ)
    
- Create two columns where each columns have three rows. 
    
- It states that the top, middle, and bottom rows have 100, 200, and 200 px. 
    
- We can also define a gap between divs. As it is shown above is 30px. 
    

  
  
### CSS Flexbox

If grid applies to two d layout, then flex is flexible for a one dimensional layout. 
![[Pasted image 20250802205733.png]]

- Where a div container, contains four containers. 
- There is a two special class contained for first and second child div. 
- Using flex property to set a complex ratio.
- flex is basically a dynamic width of the parent width. 
- Divide a single dimensions in a more flexible way.
- There is no fixed width, perhaps the width is just the maximum width. 


### External Framework e.g. Bootstrap

Something that is defined of external source, it is a framework, so you don't have to make a card, theme, divs, and so forth and so on. 

- They also have flex system. 
- Because they are built on-top of flexbox. 
- Good for responsiveness.
- Styling comes in easily. 

![[Pasted image 20250802210422.png]]


Note: *Which one is the best?
- They are just tools
- They're all have different speciallities. 
- They have strength and weaknesses. 



# Media Queries 

Media query can help us to style based on a particular device, by setting the width and height. 

![[Pasted image 20250802212132.png]]

- It states that we will have 15px font-size when the width is 600px for phones. 

**When the width is at x, the styling bellow is applied**.

Note: *it overrides the default style*
![[Pasted image 20250802212326.png]]
- We can use min-width
- Anything from the 600px above we will have 15px font-size.. 
- We can also use **max-width** to target anything that is less than 600 px, which is the maximum width. 

![[Pasted image 20250802212502.png]]
- There is also combination using AND keyword. 
- Combine things to make the sizing of the screen. 
- In accordance with the width of the screen. 

![[Pasted image 20250802212612.png]]
- There is also screen keyword; 
- Target only your website when it is being printed. 
- Targeting screen when the layout is landscape.
- Not really necessary by default. 
- Use media query to target only your website when it is being printed, to be given a different layout. Kind of vague explanation for me. 

For more media queries: [developer.movilla.org](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_media_queries/Using_media_queries)  