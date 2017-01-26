# 100 Days Of Code - Log

### Day 0: January 3, 2017

**Today's Progress**: Created a JFrame with constructor to play around with a nice UI.

**Thoughts:** I really suck at GitHub!!!

**Link to work:** I deleted the repository!!!

### Day 1: January 4, 2017

**Today's Progress**: Figured out how to properly create a repository and push/pull to it from command line. I added BeerCalc...I will probably use bits and pieces of this and blend it with the UI...maybe make it a method with getters/setters.

**Thoughts**: Glad to get the GitHub problems somewhat under control...

### Day 2: January 5, 2017

**Today's Progress**: Added labels, text fields, and buttons to UI. I didn't add in any event handlers -- yet...

**Thoughts**: Need to figure out BorderLayout vs. FlowLayout...I can't get new lines in FlowLayout. Everything is back-to-back

### Day 3: January 6, 2017

**Today's Progress**: Not much at all :-( ... I worked for over 2 hours and seriously jacked up my UI. I'm not uploading this to Github.

**Thoughts**: Need to search the web to figure out how other people manage layouts in Java...the built in stuff is really not very good...

### Day 4: January 7, 2017

**Today's Progress**: Made a webapp that autofills city, state, and county after zipcode is entered. I lauched this to github pages.

**Thoughts**: I'm actually pretty proud of it. I got the Google geocoding API to work and debugged that it needed to be HTTPS. I haven't used APIs successfully this quickly before. https://dylanwaynefoster.github.io/zipToCounty/

### Day 5: January 8, 2017

**Today's Progress**: Added getters and setters to the main class. Commited methods to do the calculations.

**Thoughts**: I haven't called methods from a separate class in a while. I need to review. I got kind of frustrated; I've been snowed in and not really feeling it today. I did about 1 1/2 hours today for the AleCulator2 project. I worked a long time on the zipToCounty app yesterday...probably why I'm not feeling it today.

### Day 6: January 9, 2017

**Today's Progress**: Generally cleaned up. Added event handling, and successfully called methods from another class. It is now an actual functioning ABV calculator!

**Thoughts**: I'm getting better at knowing how/when to call methods just generally. The UI thing is beating me up. I need to figure out the Layout Managers...like really figure them out.

### Day 7: January 10, 2017

**Today's Progress**: Now using GridBagLayout on AleCulator2. It looks much better but still not quite what I want. Also, I added a Menu Bar with File and Other Calculations tab.

**Thoughts**: The UI is WAY better now and at least intuitive. It still isn't what I envisioned. I'm going to continue working on it. I added a Menu Bar with File menu that includes 'exit'...but I can't get it to fire. I need to work on that. Also, continue working on Layout Managers until I get that down.

### Day 8: January 11, 2017

**Today's Progress**: Added Menu Items About, and Coming Soon to the menu bar. I added informational pop-ups for those two with JOption pane. Using Action Listeners for those and for the 'Exit' choice which I finally got to work. I need to ensure that I really understand what's going on with these, they are a little tricky.

**Thoughts**: Getting better at actually following the OO logic. Need to continue getting better in general and read other people's Java code.

### Day 9: January 12, 2017

**Today's Progress**: None really...I worked for over 2 hours trying to get a new content pane from a menu item...nothing to commit... :-(

**Thoughts**: I really suck at action listeners and Layout Managers; I mean - really suck...I may get a book just about Java Swing components.

### Day 10: January 13, 2017

**Today's Progress**: Created a separate Class in the AleCulator program specifically to figure out Layout Managers...currently it is Card Layout which looks like what I am going to end up wanting/using...should have used it first. I was actually getting what I planned at the end.

**Thoughts**: I only did a little over an hour but it felt very productive. I'm getting things quicker now (or at least things are sinking in). I plan on trying to install and mess around with Spring and Maven this weekend. Apparently if you want to be a working Java programmer (that gets paid anyway) these tools are essential.

### Day 11: January 14, 2017

**Today's Progress**: Added CardLayout to my main AleFrame Class. It definitely needs work but I got the separate panels to do what I intended...I have to hit the trigger to add the second panel twice, so something is up with my logic there...Spent WAY too long trying to 'install' Maven on my machine.

**Thoughts**: Maven is a bitch to install, but I need to figure it out. If I want to be a highly paid, professional Java programmer I apparently have to have Spring and Maven in my toolbox...

### Day 12: January 15, 2017

**Today's Progress**: Added key listener for Enter/Submit...added yet another layout attempt - JTabbedPane. Downloaded Spring Tool Suite.

**Thoughts**: Tabbed is definitely more of what I was looking for (but I've said this before...). I'm hoping the Spring Tool Suite will handle the Maven nonsense I dealt with yesterday.

### Day 13: January 16, 2017

**Today's Progress**: Added some new methods with getters for temperature conversion calculations to be used in the "Other Helpful Calculations" section of AleCulator2. I also added labels and text fields to the JTabbedPane to use these calculations...this is for testing/planning purposes.

**Thoughts**: Did 2 hours. I'm a little tired/burnt on this project but hanging in. Continuing my quest for Java knowledge; planning on buying a Spring Framework book to fill in some of the gaps in said Java knowledge.

### Day 14: January 17, 2017

**Today's Progress**: Added the temperature conversion functionality to the AleClass constructor. Inserted some HTML inside the JLabels to get new lines because again: Layout Managers suck! Reading on Spring, Maven, and Hibernate.

**Thoughts**: I'm continuing to get better. The Layout Managers are frustrating, but all of the work is allowing me to see what I really want to do with the project. Also, my understanding of the flow of business logic in an object oriented setting is much improved since starting (and because of) this challenge.

### Day 15: January 18, 2017

**Today's Progress**: Added a greeting pane; moved the ABV calculator to the "Calculators" menu in order to make it a more general purpose brewing calculator. Cleaned up a good bit. Made the frame non-resizable. (This all refers to the AleCulator2 project.)

**Thoughts**: It's definitely buggy, but I'm happy with the progress. I need to make sure you can clear/refresh the panes. I also need to make sure you can choose any of the calculations in any order...currently you have to go in the order they are listed.

### Day 16: January 19, 2017

**Today's Progress**: Added functionality to choose any of the calculations in any order you want. Added 'Refresh' buttons to the panes to clear the fields and allow for new data entry.

**Thoughts**: I am able to usually figure things out much quicker than I used to be, at least when trouble shooting. The daily 'practice regimen' seems to be working. I'm definitely not following the 'text book,' if you will, as far as best practices are concerned, but I am getting things done. These are things I want to get done and they are working. That, to me, means a lot.

### Day 17: January 20, 2017

**Today's Progress**: Added Menus and sub-menus for AleCulator project. Used action listeners to build the JPanels - non-functioning at the moment.

**Thoughts**: Not really feeling it today...however, I was able to knock out exactly what I was wanting in about an hour and twenty minutes. That is definitely progress that I can recognize. The way I am generating the JPanels while simultaneously removing any others is getting cumbersom. I also am putting everything in the constructor; someone will definitely give me a hard time about it. I am going to consider refactoring it once I get it finished, perhaps before I package it.

### Day 18: January 21, 2017

**Today's Progress**: Added dry and liquid measurement calculations to use in the JPanels I created yesterday. I also made getter/setter methods for those calculation methods. They are now functional in the calculator.

**Thoughts**: I can tell the 19 day streak is helping me out. I can think up something and type it out and get going a lot faster now. I need to start a new project soon.

### Day 19: January 22, 2017

**Today's Progress**: Added Dry Weight Method for Pounds/Kilograms to AleCulator2 project. 

**Thoughts**: Did an hour and 10 minutes...wasn't really feeling it...21 days makes a habit! Look forward to tomorrow.

### Day 20: January 23, 2017

**Today's Progress**: Added some more conversion methods. Installed Spring Tool Suite.

**Thoughts**: Did very little over 1 hour - but I got my time in. I need to make a new project. This one does what I want and I'm growing weary of working on it. I may start something new with the Spring framework.

### Day 21: January 24, 2017

**Today's Progress**: Started a Spring Boot project...sort of got it to work(?). Maven still likes to not show on my machine even though I know it's there. Also started a console game project in Java; nothing I want to commit yet...

**Thoughts**: Maven is alarmingly frustrating...I really need to spend some time laying out my projects instead of approaching it like a brain storm...that can be good at times - like a jam session - but I kind of need to know where I'm going to draw the map...

### Day 22: January 25, 2017

**Today's Progress**: Wrote some Apex code for a SalesForce app that sends email.

**Thoughts**: Apex is interesting. It's basically Java. I will probably check out the SalesForce ecosystem more.

