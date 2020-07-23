# notes-careertrack-29.md
## MVC 
* Model-view-controller, we've been doing this a couple of days now and it's looking familiar. I like this pattern. You separate everything out and the state is used across your small apps. I can see how this would get crazy with more and more containers, models, and views, etc.
 ## Architecting Single Page Applications
 * View
    * <b>Presentational Components</b>-receives state through props, change state through events
    * <b>Container Components</b>-receive state from <i>Store</i>, transfers state to <i>Presentational Components</i>
 * Application Services -interpret state

 * Store-holds state, state is immutable, acts as publisher
 * Domain-represents the state
    * <b>Domain services</b>-business logic without bugs
## MVC in React
1. A Presentation Layer of Controller and View React Components
*  Controller components
* View components
2. A UI-Agnostic Data Model
* <q> The patterns proposed here, (1) Controller + View Components and (2) UI-Agnostic Data Model, do not require strict OOP or FP styles. This is a good thing because JavaScript is a very general language that favors a mixed style far better than a single one. The patterns also mesh well with the spirit of React as “just a view library”. </q> -https://blog.testdouble.com/posts/2019-11-04-react-mvc/
