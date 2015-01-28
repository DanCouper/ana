# ana
A collection of useful miscellania.

*Fancy ordering and maybe a shiny front end can be implemented once substantial content has been added, and building an enormous list becomes tiresome.*

## Contents

- [Design](#design)
- [Elixir](#elixir)
- [Game Programming](#game-programming)
- [General CS/Programming](#general-csprogramming)
- [Haskell](#haskell)
- [JavaScript](#javascript)
- [Typography/Fontwerk](#typographyfontwerk)
- [UI](#ui)

***

## Elixir

***
*[GOTO TOP](#contents)*
***

## Game Programming

### Blogs - Game Programming

[**Red Blob Games**](http://www.redblobgames.com/) Phenomenal source of useful information - introductions to pathfinding, A*, tiling methods and algorithms, etc. Well written, in-depth, excellent diagrams. Highly applicable outside of game programming/design. Articles are consistently reposted on HN for a reason.

***
*[GOTO TOP](#contents)*
***

## General CS/Programming

### Videos

[**Category Theory**](http://youtu.be/o6L6XeNdd_k) by Mathematician Tom LaGatta, Filmed at the March 11, 2014 LispNYC meetup at Meetup HQ in NYC. Clear, detailed overview.

### Papers - General CS/Programming

[**Push-Pull FRP**](papers/push-pull-frp.pdf).
  Elliott, C. (2011) [*Push-Pull Functional Reactive Programming*](papers/push-pull-frp.pdf) Haskell '09. Edinburgh, Scotland.
[**Worlds**](papers/tr2011001_final_worlds.pdf). Interesting paper which (to quote) "introduces worlds, a language construct that reifies the notion of program state and enables programmers to control the scope of side effects."
  Warth, A., Ohshima, Y., Kaehler, T., Kay, A. (2011) [*Worlds: Controlling the Scope of Side Effects*](papers/tr2011001_final_worlds.pdf) VPRI Technical Report TR-2011-001. Glendale, California: Viewpoints Research Institute.

***
*[GOTO TOP](#contents)*
***

## Haskell

### Articles/Tutorials - Haskell
[**What I wish I knew When Learning Haskell**](http://dev.stephendiehl.com/hask). Useful, in-depth set of notes - on GitHub at https://github.com/sdiehl/wiwinwlh/.

[**http://yannesposito.com/Scratch/en/blog/Haskell-the-Hard-Way/**](Learn Haskell Fast and Hard). Short, dense tutorial on Haskell basics.

[**http://www.willamette.edu/~fruehr/haskell/evolution.html**](The Evolution of a Haskell Programmer).
> I suppose this is what you’d have to call “small-audience” humour.

***
*[GOTO TOP](#contents)*
***

## JavaScript

### Articles/Tutorials - JS

[**A Monad in Practicality**](http://robotlolita.me/2013/12/08/a-monad-in-practicality-first-class-failures.html). Using monads in JS to deal with failures. By Quildreen Motta - see also her [**Folktale**](https://github.com/folktale) library.

[**Searching JavaScript arrays with a binary search**](http://oli.me.uk/2013/06/08/searching-javascript-arrays-with-a-binary-search/), and the [**follow up article**](http://oli.me.uk/2014/12/17/revisiting-searching-javascript-arrays-with-a-binary-search/) (with linked NPM package). Binary search is quick for large arrays, though the arrays must be sorted.

[**Event Driven & FRP Step-by-Step**](http://open.bekk.no/event-driven-and-functional-reactive-programming-step-by-step). Good, well written tutorial, and rest of the articles on the site are a useful resource.

[**Higher-order Javascript**](http://interglacial.com/hoj/hoj.html). Companion piece to *Higher-order Perl*

### Blogs - JS

[**Better World by Better Software**](http://bahmutov.calepin.co/) - Gleb Bahmutov's blog - fairly functional JavaScript advice.

[**Perfection Kills](http://perfectionkills.com) - Juriy "kangax" Zaytsev's JS blog. Very well written articles - (this one in particular)[http://perfectionkills.com/exploring-canvas-drawing-techniques/], on canvas drawing techniques. Also see his ES6 Compatibility table at http://kangax.github.io/compat-table/es6/.

### Repos - JS

[**Bacon.js**](https://github.com/baconjs/bacon.js) - good FRP library. Built to deal with perceived shortcomings of the [MS Cloud Programmibility Group's](https://github.com/Reactive-Extensions) RXJS library.

[**test-check**](https://github.com/leebyron/testcheck-js) - JS implementation of QuickCheck, allowing generative testing.

***
*[GOTO TOP](#contents)*
***

## Typography/Fontwerk

***
*[GOTO TOP](#contents)*
***

## UI

### Articles/Tutorials - UI

[**First Principles of Interaction Design**](http://asktog.com/atc/principles-of-interaction-design/). Bruce Tognazzi's in-depth rundown of useful ID principles to adhere to.

[**7 Principles of Rich Internet Applications**](http://rauchg.com/2014/7-principles-of-rich-web-applications/). Guillermo Rauch's in-depth rundown of useful RIA principles to adhere to. Good diagrams.

[Comment](https://news.ycombinator.com/item?id=8632427) from HN user *bane* in response to this [good] article posted on Medium: [7 Rules for Creating Gorgeous UI](https://medium.com/@erikdkennedy/7-rules-for-creating-gorgeous-ui-part-1-559d4e805cda?hn=1).
> Here's some rules that almost every designer I know ignores:
> 1) Map out your interface and interaction trees first
> 
> 1-click - most common actions
> 
> 2-clicks - second most common actions
> 
> 3-clicks - power user level stuff
> 
> Put the most commonly used stuff at 1-click or interaction. If you don't know what goes at 2 and 3 clicks in, you don't understand how the application is used, because you don't understand what the most common interactions are. If you've run out of room for the 1-click stuff in your UI, then your UI concept is poorly designed. Keep iterating and collecting information until you can fulfill this.
> 
> Don't put anything at more than 3 clicks in.
> 
> 2) Double the number of interaction points in the UI. Assume the application will grow and add features. If you optimize your design for the number of features you have today, you'll have no where to put all the stuff you're going to get over the application lifetime and it'll all just end up getting buried in menus. I've seen lots of gorgeously, carefully, designed applications die a year in because of this.
> 
> Double everything and see if that number of interaction points still fits within your concept, that way the interface has room to grow without getting messy.
> 
> 3) Don't make your users interpret, make them understand.
> 
> If your concerned about how universally an icon is interpreted across cultures, you're doing it wrong. Interpretation is an additional step your users have to go through to use your UI, it's like putting everything at 2, 3 and 4 clicks in because they now have to not only look and scan the UI for what they want, they need to figure out what each interface item means before they can interact with it.
> 
> Even worse, as they grow to become accustomed to your UI, they're going to end up memorizing location and placement of options because the interface widgets take too long to interpret. Get 2 revisions down the road and you move a button and wham your tech support calls jump 50% because the users never bothered to remember what the symbol for their action looked like, just where it was on the screen.
> 
> 4) Everything must be discoverable. This is why the world moved to GUIs from CLIs. Don't make your users play a 1990's era adventure game where they have to click every pixel on the screen to see if they can advance their usage. The Flat UI trend is notorious for this.
> 
> 5) Consistency rules. Also see #3.
> 
> 6) Eliminate Steps. Map out how many steps certain actions are. Cut them down to as few as possible. I remember one time going through a file import process with a tool, by the time you got the file imported the user had to navigate 27 different steps! Almost every step required minimal or no user input. Nobody had ever bothered to map out the interaction patterns in the tool before but users were constantly complaining about how difficult it was to use.
> 
> We reworked the workflow and got it down to 3 steps and user-engagement jumped triple digits.
> 
> 6) After you've addressed 1-6, make it look nice.