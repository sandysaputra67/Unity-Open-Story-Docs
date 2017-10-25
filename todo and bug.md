todo : 
editor script instead of player
tutorial on v1.0
adding sprite object to player
scroll setting on phase editor
skip button on creator
start on current page and current pos
duration with number input
disable camera script on canvas component


Bugs :
line remove on first line wont load 2nd line after removal (emptying a story wont reset interface)
clustered view
loading first page on short term call show bad quality story 
load story wont change story name.
baloon and camera size and arent reset after editting (on empty phase).
---
need fade transition at start of the phase to set up the player
fixed with adding image load at read line
---
cant accept other image file
---
camera positioning on first line is messed up(probably because of loading resources)
fixed by changing "move toward" into lerp
---
newline load from previous state.

---
phase content weirdly scaled on unity 5.50f3 windows file manager wont work as well
Fix : add instantiate third parameter to false
---