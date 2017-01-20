# 100 Days Of Code - Log

### Day 0: January 2, 2016 - Refactoring Old JS

I had some time on the train back to DC from New York, so I cracked open my laptop and got to coding. The internet on the train leaves a bit to be desired, so I figured that the best way for me to spend some time was to refactor some old JavaScript from my color guessing game.

The code is a complete mess - variables everywhere, no comments, etc. It's basically unreadable, and if anyone even tried to look at it on my GitHub, I'm pretty sure they would explode. I'm porting over the code to a much more manageable MVC organizational framework, which will make things much prettier to read. Not to mention easier to update and add features to in the future.

**Link to Work:** [RGB Game - Refactored JS Code](https://github.com/leo-generali/rgb-game/blob/refactoredCode/js/app.js)

### Day 1: January 3, 2016 - Udacity Final Project, Hugo

Kicked off the 100 Days of Code by working on the Udacity Final Project - the neighborhood map. I'm excited to see this through to completion, because it'll be a really expansive app that will look great on my portfolio! Plus, working with knockout.js and the Google maps API is a great learning experience.

I also took a little time to myself and fiddled around with Hugo. I thought it was going to be complicated, but it doesn't look like it's too hard to set up.

**Link to Work:** None - I didn't upload anything to GitHub.

### Day 2: January 4, 2016 - Udacity Final Project

I was running into a lot of closure and scope related issues, but poking around in the Udacity forums and checking out the old lessons led me to the right fix.

As of right now, my map displays every metro station in the DMV area. When the map marker is clicked, that station's name is displayed. There's still a lot of work to be done, but it's all shaping up nicely!

*Side note*: I'm really enjoying this 100 Days of Code challenge. I didn't think I'd like it this much, but interacting with the community in the small ways I have so far has been so great.

**Link to Work:** [Metro Map](https://github.com/leo-generali/metro-map/blob/master/js/app.js)

### Day 3: January 5, 2016 - Udacity Final Project

Slower day today... I kept on running into some pretty serious dead ends. 

Having a really hard time figuring out how I'm supposed to incorporate knockout.js into this project. I have a suspicion that I'll be reading up on a fair share of tutorials online.

**Link to Work:** [Metro Map](https://github.com/leo-generali/metro-map/)

### Day 4: January 6, 2016 - Udacity Final Project

Calling it a day early. Still having some trouble with knockout.js so I decided to make the app look nicer. Will try and get in some more coding if I can make within the day.

**Link to Work:** [Metro Map](https://github.com/leo-generali/metro-map/)

### Day 5: January 8, 2016 - Udacity Final Project

I'm ashamed... I had all of Saturday to do some coding, and I flubbed it - hard. Hopped on the horse back in force today though. I coded for 3+ solid hours. Hopefully that makes up for it.

 I began creating the UI for the map. It's not just an input bar in the top left anymore! I also finally implemented some Knockout into this project. I used the framework's templating features to update the DOM with the names of every station.

I'm getting pretty close to the end of this project. I have a few more things I want to finish up, but in all honesty, I don't think it will all take me that much longer.

**Link to Work:** [Metro Map](https://github.com/leo-generali/metro-map/)

### Day 6: January 9, 2016 - Udacity Final Project

After yesterday's steamroll of a day, I would be lying if I said I wasn't looking forward to crushing this array filter...

Hasn't happened yet, but I think I'm getting close. I read up on a gazillion tutorials and learned a lot more about using Knockout in general. I'm going to turn to the forums and see what I can learn.

**Link to Work:** [Metro Map](https://github.com/leo-generali/metro-map/)

### Day 7: January 10, 2016 - Udacity Final Project

Another slow day for the project... I tried out a bunch of different techniques, but nothing really worked.

**Link to Work:** [Metro Map](https://github.com/leo-generali/metro-map/)

### Day 8: January 11, 2016 - Udacity Final Project

Huzzah! Big shout out to Karol over at Udacity for his help with this one. I posted a question up on the forums and he was able to point me in the right direction. You can check out our conversation [here](https://discussions.udacity.com/t/looking-for-help-filtering-through-array/208860/5?u=leo.generali).

I solved my problem of filtering the array by adding a second, empty observable array that is updated based on the users input. When the user types in the name of a station, every metro stop with the characters being searched for get added to the filtered array. This array is reflected in the DOM which continually gets updated.

Yes, this does mean that some stations will come up if you type in "ASFD", but as a whole, I'm going to treat this positively. The search system is loosey goosey enough that misspellings are sometimes still represented. I think that's good!

My next plan of action is to add a function that opens a station's infoWindow when it is clicked in list view.  

**Link to Work:** [Metro Map](https://github.com/leo-generali/metro-map/)

### Day 9: January 12, 2016 - Hugo

Got sucked into editing my personal site with Hugo. Super fast static site generator, but the docs are pretty bad. Thankfully there's an active forum so I can troll around and find some direction.

**Link to Work:** [Personal Site](https://github.com/leo-generali/leo-generali.github.io)

### Day 10: January 13, 2016 - Hugo

Redid my personal site using Hugo. Still working on small problems but I like where I'm going with it.

**Link to Work:** [Personal Site](https://github.com/leo-generali/leo-generali.github.io)

### Day 11: January 15, 2016 - Hugo

Oops! I somehow forgot to do anything on Saturday... Hopefully that doesn't become a trend. More Hugo/Personal site work today.

**Link to Work:** [Personal Site](https://github.com/leo-generali/leo-generali.github.io)

### Day 12: January 16, 2016 - Hugo

More Hugo and personal site stuff. Having some big problems updating a singular page.

**Link to Work:** [Personal Site](https://github.com/leo-generali/leo-generali.github.io)

### Day 13: January 17, 2016 - Hugo

Finally got it looking and working well! Swag.

**Link to Work:** [Personal Site](https://github.com/leo-generali/leo-generali.github.io)

### Day 14: January 18, 2016 - Metro Map

Spent a lot of time working on the map today. My click list view finally works.

**Link to Work:** [Metro Map](https://github.com/leo-generali/metro-map/)

### Day 15: January 19, 2016 - Metro Map

Tons of work spent on the map today. Among the things I did:

 - Only one info window can be open at a time. Opening a new infowindow closes all other open ones. 
 - Clicking on the marker/list view that is currently open will close that info window
 - Styling changes to the info windows. They are now flexboxes, which means the metro stations listed are much pretty than long bars.

**Link to Work:** [Metro Map](https://github.com/leo-generali/metro-map/)
