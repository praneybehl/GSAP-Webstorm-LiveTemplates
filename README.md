GSAP JS Webstorm Live Templates
===========================

Live templates to be used in WebStorm with GreenSock Animation Platform (GSAP JS)


##Introduction

This repository contains LiveTemplates for [GSAP](http://www.greensock.com/) to be used with [JetBrains](http://www.jetbrains.com/) products such as [WebStorm](http://www.jetbrains.com/webstorm/).

Live Templates are a set of abbreviations that expand in to 'code snippets' for common tasks such as creating variables and functions. These abbreviations significantly speed up development and reduce coding errors.

##Installation

##WebStorm

WebStorm doesn't have any particular installation (or import) procedure for LiveTemplates.
Instead just drop `GSAPLiveTemplates.xml` filee from this repository into WebStorm's folder where it stores LiveTemplates.

Live templates are stored in the following location:

```
Windows: <your home directory>\.<product name><version number>\config\templates
Linux: ~\.<product name><version number>\config\templates
MacOS: ~/Library/Preferences/<product name><version number>/templates
```


##How to use the Live Templates
The following show the available abbrivations and their default implementations. All input fields of the templates are variables thus Tabbing futher will jump to the next variable of the template.

All templates here are Global, that means they can be used in any type of document in Webstorm. If you like to restrict them to any particular file extension you can edit by going into :

```
Webstorm -> Preferences -> Live Templates -> GSAP JS 
then for the template you wish to change select Change at "Applicable in:" at the bottom of the window.
```
You can also edit the abbreviations, description or variable if you wish so.

##Live Templates
###GSAP JS
####Globals

`twl + [Tab]` - Types TweenLite.

```
TweenLite
```

`twm + [Tab]` - Types TweenMax.

```
TweenMax
```

`tll + [Tab]` - Types TimelineLite.

```
TimelineLite
```

`tlm + [Tab]` - Types TimelineMax.

```
TimelineMax
```

`twlt + [Tab]` - Creates a TweenLite.to( ) Template.

```
TweenLite.to(element, 1, {vars});
```

`twlf + [Tab]` - Creates a TweenLite.from( ) Template.

```
TweenLite.from(element, 1, {vars});
```

`twlft + [Tab]` - Creates a TweenLite.fromTo( ) Template.

```
TweenLite.fromTo(element, 1, {fromVars}, {toVars});
```

`twmt + [Tab]` - Creates a TweenMax.to( ) Template.
```
TweenMax.to(element, 1, {vars});
```

`twmf + [Tab]` - Creates a TweenMax.from( ) Template.

```
TweenMax.from(element, 1, {vars});
```

`twmft + [Tab]` - Creates a TweenMax.fromTo( ) Template.

```
TweenMax.fromTo(element, 1, {fromVars}, {toVars});
```

`.t + [Tab]` - Creates a .to( ) Template.

```
.to(element, 1, {vars});
```

`.f + [Tab]` - Creates a .from( ) Template.

```
.from(element, 1, {vars});
```

`.ft + [Tab]` - - Creates a .fromTo( ) Template.
```
.fromTo(element, 1, {vars});
```

`stg2 + [Tab]` - Creates a staggerTo( ) Template.

```
staggerTo(element, 1, {vars}, 0)
```

`stgf + [Tab]` - Creates a staggerFrom( ) Template.
```
staggerFrom(element, 1, {vars}, 0)
```

`stgft + [Tab]` - Creates a staggerFromTo( ) Template.
```
staggerFromTo(element, 1, {fromVars}, {toVars}, 0);
```

`tllt + [Tab]` - Create a TimelineLite.to( ) Template.
```
TimelineLite.to(element, 1, {vars});
```

`tllf + [Tab]` - Create a TimelineLite.from( ) Template.
```
TimelineLite.from(element, 1, {vars});
```

`tllft + [Tab]` - Create a TimelineLite.fromTo( ) Template.
```
TimelineLite.fromTo(element, 1, {fromVars}, {toVars});
```

`tlm2 + [Tab]` - Create a TimelineMax.to( ) Template.
```
TimelineMax.to(element, 1, {vars});
```

`tlmf + [Tab]` - Create a TimelineLite.from( ) Template.
```
TimelineMax.from(element, 1, {vars});
```

`tlmft + [Tab]` - Create a TimelineLite.fromTo( ) Template.
```
TimelineMax.fromTo(element, 1, {fromVars}, {toVars});
```

`set + [Tab]` - Creates a set( ) method Template.
```
set(elem, {vars})
```

`kill + [Tab]` - Creates a kill( ) method Template.
```
kill({vars}, targetObject)
```

`atw + [Tab]` - add a tween to the end of the timeline.
```
add( TweenLite.to(element, 1, {vars}) );
```

`atl + [Tab]` - add a timeline to the end of the timeline.
```
add( TimelineLite.to(element, 1, {vars}) );
```

`alb +[Tab]` - add a label at a position to timeline.
```
add("myLabel", 2);
```

##Credits
* [Praney Behl](https://github.com/praneybehl) for initial creation of the GSAP JS Webstorm Live Templates.
* [John Lindquist](https://github.com/johnlindquist) for showing what is possible with a good IDE in his amazing video tutorials
