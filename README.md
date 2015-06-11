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
- [Psychology](#psychology)
- [Typography/Fontwerk](#typographyfontwerk)
- [UI](#ui)
- [Writing](#writing)

***

## Elixir

### Books - Elixir/Erlang

[**Études for Elixir**](http://chimera.labs.oreilly.com/books/1234000001642/index.html). Companion to the book *Introducing Elixir*, with descriptions of small programs to use as practise material.

[**SICP**](http://lfe.gitbooks.io/sicp/content/). SICP in Robert Virdig's [Lisp Flavoured Erlang](http://lfe.io/). In addition to its many other merits, the site (and the LFE site itself) is beautifully presented.


***
[*top*](#)
***

## Game Programming

### Blogs - Game Programming

[**Red Blob Games**](http://www.redblobgames.com/) Phenomenal source of useful information - introductions to pathfinding, A*, tiling methods and algorithms, etc. Well written, in-depth, excellent diagrams. Highly applicable outside of game programming/design. Articles are consistently reposted on HN for a reason.

***
[*top*](#)
***

## General CS/Programming

### Articles/Tutorials - General CS/Programming

[**Regular Expression Matching with a Trigram Index or How Google Code Search Worked**](http://swtch.com/~rsc/regexp/regexp4.html) by Russ Cox. Used as a reference to write the Etsy's search tool/app [Hound](https://codeascraft.com/2015/01/27/announcing-hound-a-lightning-fast-code-search-tool/).

### Videos - General CS/Programming

[**Category Theory**](http://youtu.be/o6L6XeNdd_k) by Mathematician Tom LaGatta, Filmed at the March 11, 2014 LispNYC meetup at Meetup HQ in NYC. Clear, detailed overview.

### Papers - General CS/Programming

[**Push-Pull FRP**](papers/push-pull-frp.pdf).
  Elliott, C. (2011) [*Push-Pull Functional Reactive Programming*](papers/push-pull-frp.pdf) Haskell '09. Edinburgh, Scotland.

[**Worlds**](papers/tr2011001_final_worlds.pdf). Interesting paper which (to quote) "introduces worlds, a language construct that reifies the notion of program state and enables programmers to control the scope of side effects."
  Warth, A., Ohshima, Y., Kaehler, T., Kay, A. (2011) [*Worlds: Controlling the Scope of Side Effects*](papers/tr2011001_final_worlds.pdf) VPRI Technical Report TR-2011-001. Glendale, California: Viewpoints Research Institute.

***
[*top*](#)
***

## Haskell

### Articles/Tutorials - Haskell
[**What I wish I knew When Learning Haskell**](http://dev.stephendiehl.com/hask). Useful, in-depth set of notes - on GitHub at https://github.com/sdiehl/wiwinwlh/.

[**http://yannesposito.com/Scratch/en/blog/Haskell-the-Hard-Way/**](Learn Haskell Fast and Hard). Short, dense tutorial on Haskell basics.

[**http://www.willamette.edu/~fruehr/haskell/evolution.html**](The Evolution of a Haskell Programmer).
> I suppose this is what you’d have to call “small-audience” humour.

***
[*top*](#)
***

## JavaScript

### Articles/Tutorials - JS

[**A Monad in Practicality**](http://robotlolita.me/2013/12/08/a-monad-in-practicality-first-class-failures.html). Using monads in JS to deal with failures. By Quildreen Motta - see also her [**Folktale**](https://github.com/folktale) library.

[Comment](https://news.ycombinator.com/item?id=8715373) from HN user *xiaoma* on the use of `this` in JS. Kangax expanded upon this in a [blog post at prefectionkills](http://perfectionkills.com/know-thy-reference/).
> Even more simply, I'd just say:
> 
> 1) The keyword "this" refers to whatever is left of the dot at call-time.
> 
> 2) If there's nothing to the left of the dot, then "this" is the root scope (e.> g. Window).
> 
> 3) A few functions change the behavior of "this"—bind, call and apply
> 
> 4) The keyword "new" binds this to the object just created
> 
> So if you're using the value of "this" in someFunction...
> 
>   thing.someFunction(); // this === thing
>   someFunction();       // this === Window
>   new someFunction();   // this === the newly created object
> 
> It's as simple as that. It's a very useful keyword.

[**Searching JavaScript arrays with a binary search**](http://oli.me.uk/2013/06/08/searching-javascript-arrays-with-a-binary-search/), and the [**follow up article**](http://oli.me.uk/2014/12/17/revisiting-searching-javascript-arrays-with-a-binary-search/) (with linked NPM package). Binary search is quick for large arrays, though the arrays must be sorted.

[**Event Driven & Functional Reactive Programming Step-by-Step**](http://open.bekk.no/event-driven-and-functional-reactive-programming-step-by-step). Good, well written tutorial, and rest of the articles on the site are a useful resource.

[**Higher-order Javascript**](http://interglacial.com/hoj/hoj.html). Companion piece to *Higher-order Perl*

### Books - JS

[**Book of Modern Front-end Tooling**](https://github.com/tooling/book-of-modern-frontend-tooling). Addy Osmani *et al*, covering NPM, Gulp, Grunt, Brunch, ComponentJS, Browserify, WebPack, Yeoman and Loom.

[**Human JavaScript**](http://read.humanjavascript.com/). Henrik Joreteg's guide to building simple browser apps, eschews heavy frameworks as much as possible. Nicely presented.

[**JavaScript Allongé**](https://leanpub.com/javascript-allonge/read) is the boy. Reg Braithwaite is pretty good at explaining.

[**PureScript by Example**](https://leanpub.com/purescript/read). Oh look, it's Haskell, but only not, it's JavaScript. Note compilation is a [very] slight pain point, otherwise language is v good. See also [LiveScript](http://livescript.net/), which maps straight to JS instead of running through a Haskell-based compiler (it is a child of CoffeeScript).

[**You Don't Know JS**](https://github.com/getify/You-Dont-Know-JS). The repo for Kyle Simpson's book series. Very, very good explanations - the async stuff on promises in particular is illuminating. Clear, good examples, highly detailed, engaging.

### Blogs - JS

[**Better World by Better Software**](http://bahmutov.calepin.co/) - Gleb Bahmutov's blog - fairly functional JavaScript advice.

[**Perfection Kills**](http://perfectionkills.com) - Juriy "kangax" Zaytsev's JS blog. Very well written articles - (this one in particular)[http://perfectionkills.com/exploring-canvas-drawing-techniques/], on canvas drawing techniques. Also see his ES6 Compatibility table at http://kangax.github.io/compat-table/es6/.

[**raganwald.com**](http://raganwald.com/), Reginald Braithwaite's archive of technical (mainly JS, some Ruby) articles.

### Repos - JS

[**Bacon.js**](https://github.com/baconjs/bacon.js) - good FRP library. Built to deal with perceived shortcomings of the [MS Cloud Programmibility Group's](https://github.com/Reactive-Extensions) RXJS library. A spin-off built to improve on performance is [Kefir](https://rpominov.github.io/kefir/).

[**React**](http://facebook.github.io/react/), [**Immutable**](http://facebook.github.io/immutable-js/), and [**Flow**](http://flowtype.org/). Respectively, Facebooks's view layer, immutable data library, and static type checker.

[**lodash**](https://lodash.com). Despite the 'orrible looking documentation, possibly still the best. Now has fully curried version ([lodash-fp](https://www.npmjs.com/package/lodash-fp)), which is a rather nice thing to have access to.

[**test-check**](https://github.com/leebyron/testcheck-js) - JS implementation of QuickCheck, allowing generative testing.

***
[*top*](#)
***

## Psychology

### Articles - Psychology
[**The Psychology of Pricing: A Gigantic List of Strategies**](http://www.nickkolenda.com/psychological-pricing-strategies/). Does exactly what it says on the tin. Very useful, and seems very comprehensive.

***
[*top*](#)
***

## Typography/Fontwerk

***
[*top*](#)
***

## UI

### Articles/Tutorials - UI

[**The differences Between print design and web design**](http://www.nngroup.com/articles/differences-between-print-design-and-web-design/). Important to keep at the back of one's mind. It is too, too easy to fall into the trap of carefully laying out elements for a web design, applying beautiful typography to a static mockup in PS/Illustrator/InDesign, and to then have to compromise on every design decision due to the fact the web is not a picture to be printed out.

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

***
[*top*](#)
***

## Writing

### Articles/Tutorials - Writing

[**Search Engine Optimisation in BBC News**](http://bbc.in/1HcAYA7). Headline writing and SEO at the BBC. Key points, alongside the 55-character limit
(the length of a Google search result):

1. Use words that people would use in search in order to find the
   information being provided.
2. Avoid words that people would never use in search to find that content.
3. Put the most searchable elements at the front.
4. Proper names are often used in search, so - following rules 1 and 3 -
   names should be included in the headline and if appropriate at the front.

### Apps - Writing

[**Hemingway**](http://www.hemingwayapp.com/). Very useful, but do use with caution; it is an extremely blunt tool. The app assesses writing, siming to make it "bold and clear".

> Hemingway highlights long, complex sentences and common errors; if you see a yellow highlight, shorten the sentence or split it. If you see a red highlight, your sentence is so dense and complicated that your readers will get lost trying to follow its meandering, splitting logic — try editing this sentence to remove the red.
Adverbs are helpfully shown in blue. Get rid of them and pick verbs with force instead.
You can utilize a shorter word in place of a purple one. Mouse over it for hints.
Phrases in green have been marked to show passive voice.

***
[*top*](#)
***
