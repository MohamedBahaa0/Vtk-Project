# Project: VTK webapp

##### by: Omar Essam, Mohamed Bahaa, Youssef El Gazzar, Mohamed Ahmed Hamed

#### Problems we faced in:
- Toggling between modes


#### Toggling between modes 
1. After choosing the mode, we were unable to change the mode 
- We used QuerySelector function that allows changing mode once again 
2. Toggling between two modes was allowed only once
- we used QuerySelectorAll instead of QuerySelector as :
 The querySelector() method returns the first element within the document which matches a specified CSS selector(s).
 If multiple elements occurs, then it returns the result for only the first matching element.
The querySelectorAll() method returns all the elements within the document which matches the specified CSS selector(s).
 It returns all the elements that matches with the selector in the form of a static NodeList object which is a collection of nodes.



#### Output 


- Changing iso value:
<center><img src="Output Screenshots/Chest.gif" alt="alt text" width="600" height="400"></center>

- Changing ray casting properties:
<center><img src="Output Screenshots/Skull.gif" alt="alt text" width="600" height="400"></center>

-Toggling between  modes: 
<center><img src="Output Screenshots/Toggle.gif" alt="alt text" width="600" height="400"></center>
