A3-KSMANGONE
---

https://glitch.com/edit/#!/a3-ksmangone

## Run Training Index

This is a website made to index runs for a training program you follow. Simple tracking website. CSS Grid was used to create the 3 input boxes (and titles) to appear in a 3 across position instead of 3 top down in one column.
To use the application simply input a Distance traveled in miles, Time taken in minutes (use decimals to indicate seconds -- secs/60) and an optional description of the run, if it was a workout or not this may be important or part of a 
multi part run. Finally, an output will appear on the table with the information inputted, as well as a calculated average pace of the run. Finally, there are 2 buttons in which the user can edit or delete a row. Clicking the edit button
will return 3 prompts in which you can adjust either of the 3 original inputs. The delete button (on first attempt takes 2 clicks) instantly deletes the run from the table.

For authentication there is a simple database collection storing username and passwords. It is simple to register for an account, simply type a username that isnt already in use, and a corresponding password then hit register. You must be logged in 
to a specific account to see that account's run entries. This was simple for me to implement, and the main reason I did it this way.

I used the MVP css, simply due to time constraints and being unable to learn a more in depth framework like bootstrap. I made some small adjustments including centering, adjusting the width of the entry table to match the rest of the form. Button colors to increase contrast (and outline), as well as input bar lengths.

Middleware:

app.use(express.json()) & BodyParser: Important middleware to reading and parsing the data sent through the body section of a request.

app.use(express.static("public")) : used for express to serve the static files within the public directory i.e. index.html

Cookie-session: Create cookies stored in the user browser to contain their username once logged in. This is then used for retrieving data & overall verifcation of logged in user.

## Technical Achievements
- **Tech Achievement 1**: I achieved a 100% in all four lighthouse tests required for this assignment.

https://cdn.glitch.global/57c886ed-d2ac-472e-b97b-50bca4611ec7/3c7ba04e-a856-46f4-b8a8-076d6c64bfb7.image.png?v=1695487318263

Achieved using suggestions from the lighthouse analysis.



