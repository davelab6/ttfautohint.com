# What does TTFAutohint do now?

The ttfautohint library brings the excellent quality of FreeType rendering to platforms that don’t use FreeType, yet require hinting for text to look good – like Microsoft Windows. 
Roughly speaking, it uses the glyph analysis done by FreeType’s auto-hinter to create TrueType hinting inside font files. 
Better hinting means better rendering webfonts. 

There are no surprises with TTFAutohint. 
It already works. 
Period. 
But it has potential to become even better.

# What This Next Funded Update Will Produce

There are three main goals for next version of TTFAutohint: 

1. offer expanded language support,

2. design a simple GUI to craft final hint adjustments,

3. produce a plugin of that GUI for both Glyphs and Robofont.

# Chasing Waterfalls

Side-by-side comparisons should speak volumes to you. 
Here we have one waterfall showing the result of a time-consuming and costly hinting job by a professional, and another made with TTFAutohint:

TODO: Images

# It Already Works, See.

## Finessing x-heights

TODO: Images of x-height increase

TODO: link to further info

## Better, Stem Control

To take this further, let's look at the routines associated with controlling stems and stem contrast. 

TODO: explain the two routines

TODO: include image of Mertz Bold g's

TODO: link to further info

## Visualizing Your Instructions

Instead of needing to code your fine-tuning data, we will make a GUI plugin so you can craft the highest quality results with a UI. 
You will no longer have to worry about typing ‘Q left 38’ in a text file. 
Instead you will be able to resolve issues dynamically.

TODO: include the O's and Q's imagery

TODO: link to further info

# Making It Work For Today's Type Design Apps

Glyphs and Robofont are now the center of your workflow. 
Think about the benefits of having a plug-in with this control at your fingertips—it levels the playing field. 
And we need your help.

TODO: mockup of plugin UI here?

To do this, we need your help. We need your money.

TODO: donate prompt

## Timetables & Expectations

TODO: 

Now, if you wanna geek out more about this, click here to read more about it. [ttfautohint manual]

#### Thanks

This website was put together by Neil Summerour and Dave Crossland to help the developer of ttfautohint, Werner Lemberg, take it to the next level. 