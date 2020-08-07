# ui-assessment

Implemented the cards that have tooltip says “Implement This” with solution proposals for design and ux issues as required in the assessment.

**Additional work:** Implemented responsive design.

## Analysis
While observing the design I had 2 major points in mind
  - consistency (ex: I noticed that numbers in transactions card aren't consistent with other numbers in the design so I changed transactions card numbers color and font to be consistent)
  - user experience (ex: pending status was in green color which would give the user a bad experience so I changed it to yellowish color)
  
I started with making the layout then I made a typography page to visualize text styling (Typography page can be accessed from the sidebar).

Consistent design allowed me to write less code by using mixins and extending styles. 

## Changes made to the design

Searching by the keyword "changed" in the stylesheets will result to the comments about changes made.

**General:**
  - Unified spacings/gaps in the design (ex: gaps between cards and cards padding)
  - Unified cards rounded corners sizes.
  - Unified button styles and text within them is centered.
  
**Statistics card:**
  - Reduced content text font-size (It needs to be discussed with the designer to know if it's intended to be bigger than the card's heading) 
  - Changed pending status color to yellowish color to represent pending/in progress status.
  
**Transaction card:**
  - Changed number color and font in transaction card to be consistent with the rest of design.
  
**Slider card:**
  - Changed text and slider dotgroup colors to match the design primary and secondary colors
  - Changed dots position to the center to be more clear for user that the whole card is a slider (It needs to be discussed with the designer if the whole card is a slider or just the text part of it and the image is static?! if it's the second choice it would be better to be centered to the text half of card or positioned to the right like the design)
