Assignment 1
============
Create a "TVFinder" webpage

Overview
--------
The file "Concept.png" contains a mock-up for a proposed TVFinder feature. Your assignment for Week 1 is to implement a working webpage version of this design.


Details
-------
- As with all assignments, you need to ensure the implementation adheres closely to the mock-up in a wide variety of browsers. For this assignment, consider IE 9+, Firefox 18+, and Chrome 25+ as browsers you must support.

- Don't take short-cuts on the page implementation; implement the page as you think a real production webpage should be structured (e.g., don't put an image in place of the "Search" box; put a real search box there).

- Demonstrate your best efforts to use front-end optimization best practices.

- None of the text should be imlpemented using bitmaps; real type should be used. Be thoughtful about choosing fonts that best represent the aesthetic of the design; consider using web fonts if appropriate.

- Create a file "televisions.json" that includes at least 100 televisions that will be filtered on the client. A sample file "televisions.json" has been included that illustrates how you might structure your own file.

- A database of television metadata and thumbnails has been included with this assignment. Use these images for televisions, not the images in the mock-up. However, the three televisions just below the "Get More, For Less" header are part of the design and should be included as-is.

- Assume that your "televisions.json" could be loaded remotely and code accordingly (i.e., it may take several seconds to load). This means the page should not block on loading the file and should display some indication to the user that it is loading data.

- Make it easy to change the location of "televisions.json" in your code so we can deploy it to a server and test your assignment under variable latencies.

- Changing the values of the slider or the drop-downs should cause the set of displayed televisions to change in real-time.

- For an extra challenge, consider using animation effects when the set of filtered televisions changes. For example, after changing the drop-down / slider, televisions that no longer match could fade out, new televisions to the matched set could fade in, and televisions that move locations could move (using ease in / ease out to smooth the move path) to the new location.

- Feel free to use third-party libraries for whatever functionality you wish, but be sensitive to overall page size.


Goals
-----
The goal of this assignment is to give you an opportunity to learn and demonstrate the following skills:
- Modern HTML structure and vocabulary
- Core CSS concepts
- Core JS concepts
- Modern JS patterns
- How JSON maps to JavaScript
- Thorax
- Compatibility with required versions of IE, Chrome, Firefox, and Safari on Windows and OS X
- Page Speed Optimization *

Optional:
- CSS Transitions, Transforms, 3D Transforms, and Animation
