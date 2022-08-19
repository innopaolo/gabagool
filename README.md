# gabagool
A Sopranos meme as a Google search parody

<h3>I cloned the Google dark theme and came across a few troubles that I haven't completely resolved:</h3>

The search bar implementation was difficult. Using z-index to layer over the icons on it disabled
the input and hover capabilities of the textbox, so I scrapped that. I realized I can use padding
and house the icons on that extra space and disable outline and border for the textbox, and house
it inside a div with a border to mimic the google search bar.

Hovering changed the color of the textbox, and I wanted it to both change for the input box and the 
div it wss in. It worked, then the next step were the icons. I used a lot of free tools online to 
make icons have transparent backgrounds. The problem was the magnifying glass for the image search 
bar, despite having a transparent background, still had a black square around it. I'm guessing it 
has something to do with an input tag with an image type, which bypasses the hover styling somehow.
Googling didn't seem to help, and I'm going to have to ask real human beings for help.

The last concern is the responsive design of the pages. I think the widths turned out fine, though
not the height. I am aware that the code is messy and chaotic, and certainly have contributed to
the weird behavior of the search bar when I resize the page vertically: it seems that the margin
right styling grows, squishing the bar sideways to the left side. 

<h3>Things I'm proud of:<h3>

This is my first clone of any webpage and I'm proud of being able to solve how the search bar works
coming from no coding experience and just doing self-studying. It's a small step, but towards the 
right direction I hope. 

The footer stacking on top of each other using flexbox seems like an easy thing, but it took me hours
poring over documnetation to finally figure that one out. I also had to use padding to cover the 
different color of the background the second row ended up in when stacked. With the first row of the
footer expanding in height, it covered what essentially is the html body background, which has a 
different color.

Finally, figuring out the url search terms I needed to implement the input boxes correctly is like
drinking that first sip of beer in summer. Amazing feeling.

Coming out of this small problem set, I learned a lot about CSS and respect it mch more now than before.

I placed a lot of random links around the site, a bit of levity to amuse me while I torture myself
building something out of nothing.

If you read up to this point, thank you. And I'm sure you have better use of your time. Have a nice
day my friend.

/end
