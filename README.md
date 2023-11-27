# navbar
The main idea is to change our navbar when the size of the screen is less than 620px using media querries
when size of screen is less than 620px then we do
1. make the position of our navbar absolute to body and shift to left .
2. Then we transform it to negative x axis 100% and make its visibility and opacity as none.

Then for our toggle btn which was set display : none  previously ,  we set it display : block

there is "active" class present in our header (header is the parent of navbar) 
-> so if active class is present then we transform our navbar to X(0) and make it visible and opaque
and if "active" class is present then we make our close-toggle btn display:block and our open-toggle btn display : none

then Java script help to toggle the "active" class by clicking on toggle btn
it will add or remove the "active" class when toggle btn is pressed.
