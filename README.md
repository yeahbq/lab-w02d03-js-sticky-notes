# Getting Sticky
---------------------------------------------------------------------------------------------------
Add structure to a web page from the DOM point of view. Build a page where the user can create a series of notes to the page and edit and delete the content. 
---------------------------------------------------------------------------------------------------

## MVP

When a user visits the site...
    they should see... 
    - a field called "Total number of notes:", initially this should be set to zero
    - as you add notes the total number of notes should be updated
    - a button that says "Add A NOTE"

When a user clicks on the "Add A Note" button 
     they should see...
     - a new editable note pop-up, where they enter text
     - a should be able to come back to the note and edit it, or delete it
     - also the total note counter needs to be updated

### Feature Requests

- Create a button, which when clicked lets the user add a note
- Create a counter that keeps track of number of notes
- The user likes adding notes, but from time to time they want to come back and edit these notes. Make these notes editable, maybe what you need is content editable attribute!!!!
- User needs to delete some notes, when they become outdated. Add a "X" on the notes so they can be disposed when the "X" is clicked

### Bonus
- Add a datetime stamp for the note, when it is created




**Here is a basic wireframe** 

![](assets/asset1.png?raw=true)
 

![](assets/asset2.png?raw=true)


![](assets/asset3.png?raw=true)



## Resources
- [Making content editable](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/Editable_content)
- [Replacing nodes](https://developer.mozilla.org/en-US/docs/Web/API/Node/replaceChild)
- [Get elements using id](https://developer.mozilla.org/en-US/docs/Web/API/Document/getElementById)
- [document.createtextnode](http://www.w3schools.com/jsref/met_document_createtextnode.asp)
- [Nodes](https://developer.mozilla.org/en-US/docs/Web/API/Node)

