# Project 2 - iOS App of Awesomeness

## I. Overview
- Create a useful or entertaining iOS app or game in teams of 1 to 2 students. The app theme and capabilities should be "App Store ready" (or nearly so). The target hardware can be iPhone or iPad (or Universal).
- See the mycourses discussion thread and dropboxes for deliverable due dates

### I-A. Project Ideas

Previous submissions have included:

- **Games!**
  - It could be a "companion app" to a board or card game - ex. Diablo 3 Skill Calculator
  - It could be a digital card game, board game
  - It could be something more "spritey"  - you can use either UIKit (which was covered in this class), or something like the [SpriteKit API](https://developer.apple.com/documentation/spritekit)
- **Apps that utilize web services to display data:** Traffic App, Woot Ware, Starting Five (Dribble.com client), USGS Earthquake Mapper, iGas-Station, Philly Arts Today, Grubulate (recipe finder), Aimless Reader (random articles), Local News (in App Store)
- **Entertainment:** BackAppYa (comeback generator), Beer of the Day, Lionfish Hunter, Sudoku, Star Trader, Rate Your Boys, They all look the same to me, Jetpack Joyride Clone
- **Utilities:** S.P.A. - Shotgun Pattern Analyzer (used OpenCV), Veg Nut (recipe finder), MyIndia, Nihongo Study (Japanese Language App), Garbage Plate Finder (in App Store), Fitness App, Split the Bill
- **Media Apps:** Audio Streamer, Manga Reader
- **RIT Themed:** iRIT/RIT Now (in App Store), RIT Student Government, RIT Virtual Tour, RIT Taxi, Wallace Library App, RIT Room Booker, RIT Bus, TigerSafe (in App Store, never a student of mine)

- ***Apps that would have to run on a jailbroken device ARE NOT ALLOWED***
- **Would the theme of the app be OK for the App store?** is the question your app should answer in the affirmative.

<hr> 

<a id="milestones"></a>
  
## II. Milestones

### 1 - Create an Application Definition Statement
An Application Definition Statement is a one or two line statement answering these two questions: What's the app do? and Who is it for?

### 2 - Proposal
Using your Application Definition Statement as a starting point, put together the following:

- Full list of features - Brainstorm a full list of features that could possibly be implemented by the application. Even though we would never think of building such an App, think "Kitchen sink" or "Word on iPhone" as you are creating your list of features.
- Filtered list of features - Distill these features down to only the most essential ones that allow the application to fulfill its Product Definition Statement. Apple's Mantra: Pick the few features, most frequently used, by the majority of your users, most appropriate for the mobile context.
- Do a competitive analysis - Discover your competition at least 3 existing iPhone Apps in the App Store that are similar to what you want to create. Also look for one similar Android App in the Android app markets. Read the descriptions in the App store, and download the apps if they are free. Write a quick review of each App: include its features, user rating, its strengths and weaknesses relative to its competition, and what features you feel its missing.
- Iterate - head back to steps A and B - did you leave anything out? Are there features you should add or remove? Update your document.
- Sketch out the UI - Describe the UI, and produce some mock-ups. These can be drawn by hand or created in Photoshop or Storyboard it. Tip: The OS X Grab utility can grab some or all of the screen.
- Deliverable - Put the above in a PDF and post it to mycourses.
- Be ready to discuss your idea in class

### 3 - Prototypes(2)
Getting a prototype up an running as fast as possible is critical.

- Put together the primary navigation of the App in Storyboard, and find at least 5 people to try the app on actual hardware. Use the knowledge gained to add critical features, and fix navigation issues.
- Install on iOS hardware and bring to class on due date

### 4 - Final Deliverable

#### 4A - Requirements
- Meets the Application Definition Statement - an "A-level" app is a "polished solution to a well defined problem".
- A polished User Experience that respects the iOS Mobile HIG, as well as iOS 7/8/9/10 Design Principles:
  - Clarity - it should be clear what the app does, and people should be able to use it without instruction.
  - Deference - content is front and center - the UI should fade into the background.
  - Depth - it should be a vibrant and life-like experience, and people should not get "lost" or be confused about what state the app is in
- Media - icons & splashscreen required
- Saves state when user force-quits by utilizing *UserDefaults* or similar
- Uses Frameworks and/or methods of those frameworks that go well beyond what we've done in class this semester.
- Meets course coding standards (see below)
- Install on iOS hardware and bring to class on due date


#### 4B - Coding Standards
- Design Patterns: MVC, Singletons, Delegation, Notifications, Dependency Injection
- Separation of Concern - You should have multiple classes, with each class having well-defined functionality accessed through a public interface.
- D.R.Y. - Don't Repeat Yourself. Repeated blocks of nearly identical code should be factored out and placed in a separate method.
- No "magic numbers" (unnamed numerical constants) - declare constants or enums or structs instead.
- Code conventions: follow principle of least privilege, class names are capitalized, method names are in lower case.
- Avoid global variables.
- Well commented code. Each and every method you wrote gets a comment indicating what it does.
- There will be no compiler warnings, and no run time errors.


### 5 - Documentation

- Document that you met your application definition statement, and be specific about any work you did that truly went above and beyond.
- Discuss any struggles or failures in the development process.
- Describe which team member worked on what part of the project.
- Give credit for resources like images and sounds, and any software libraries or tutorials you used. Be sure to give yourself credit for graphics you created, or any code solutions you spent extra time on.
- Grade yourself (0-100) and justify it. Put this in a text file or Word document or PDF and submit it with your project.
-10% if not done

<hr> 

## III. Grade Rubric

- Good (Meet all requirements above reasonably well) = 90%
- Better (Go beyond expectations) = 95%
- Best (Go significantly beyond expectations) = 100%
- Wow! = 101%+

**Deductions:**
- (-35%) The project won't compile. (Be sure that your resources have been imported and are in your project directory!)
- (-10% to -30%) The app crashes.
- (-20%) The completed project is not installed on your iOS device.
- (-??%) Egregious violations of MVC or Coding Standards

<!--
Milestones
Team member name(s), idea, and proposal due start of class Tuesday 4/25 (week 13) - post to mycourses dropbox. 15% deduction from final project 3 grade if not done.
Working Prototype #1 due start of class Tuesday 5/2 (week 14) - post to mycourses dropbox - install on iOS hardware and bring to class. 15% of off your final project 3 grade if not done.
Working Prototype #2 due start of class Tuesday 5/9 (week 15) - post to mycourses dropbox - install on iOS hardware and bring to class. 15% deduction from final project 3 grade if not done.
Final Version Due Finals Week during the scheduled final exam time (Tuesday 5/16 @ 10:15AM) - post to mycourses dropbox with your documentation - install on iOS hardware and bring to class. Late submissions will not be accepted.
** If you borrowed an iOS device from IGM, you must return it at the time of our final meeting - and don't forget the cable. **
-->

<hr> 

## IV. Resources
- We've just scratched the surface of iOS this semester - you are encouraged to explore other frameworks and capabilities of iOS.
- Look over this [list of iOS frameworks](https://developer.apple.com/documentation/)
- http://www.raywenderlich.com has many written tutorials and a few video tutorials
- https://www.lynda.com also has some iOS related courses - free to RIT students
