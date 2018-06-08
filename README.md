# Time Lord

* A playground for timers where the experimental is dead are selectable through menus
* Pomodoro features through the settings menu
* Time tracking features in future where *pomodoros* are labeled, time stamped and stored in remote databases
* Good candidate for progressive web app


First Steps
--------------

* The boilerplate repo was made just for getting quick ideas like this is the ground
* Install Bulma for quick initial store version
* Consider using this as an opportunity to learn redux
* document it for the sake of blog post. * Tutorial and as complement to the *miCloud* series


First Version
-------------

* Timer state
* Simple Bulma style
* Pomodoro workflowt
* Non persisted `timedblock` UI to show pomodoros completed
* Later it will be persisted
* Document process for blog post

Components
----------

App is the root that contains everything
Workspace is where everything in the current context is contained
  Later this will be separated by using a menu button and different timer workflows
TimerContainer - the container of timer state and layout


Early Future Features
---------------------
*These are in order of importance
Menu to select style*

* Storage database to store timedblocks and settings
* Basic express API to handle the database
* Menu to select workflows
* Multiple timers
* New clock styles
* A timer server where synchronizations occur. This will eventually become a way to push events to clients
* Integration with home dash
