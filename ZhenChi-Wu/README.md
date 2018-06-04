##### How did you determine which rules should be placed in each new CSS file?

(Put your answer here)
I only refactor into 3 style sheet which are base/layout/modules.   There are no hover/animate/transition effect on the page so I didn't place any codes into state/theme css. 


Base --> Look for the overall font/background color setting.
I personally also prefer setting global variables for css, so I may put my .root{} into base.css

Layout --> Group all the layout relate elements into here,basically all the barebone elements.

Modules --> misc and specific items go here

State --> all the transit/animation/hover go here

theme.css --> haven't touch it yet, but it may come handy to swap theme. I know certain webpage has "movie mode" to turn the light off.  

---

##### Did you do any refactoring of the existing CSS? If so, briefly explain what you did and why.

(Put your answer here)
I removed the @import url from style.css placed it in index.html instead. No particular reason, that's what google suggests.

On top of that I fixed a broken link for #recipe 's background.

Other then that there is one missing file from img named"hr-img.gif".
