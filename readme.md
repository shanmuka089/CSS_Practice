1. element name Selector: when we want to apply some styles throughout the document for all the elements.
EX: h2 {
    color: blueviolet;
}
2. id selector: when we want to select elements uniquely in a html file.
EX: #element2 {
    background-color: burlywood;
}

3. class selector: when we want to select multiple elements.
EX: .arrange-element {
    text-align: center;
    color: white;
    font-weight: bold;
}
4. universal selector: when we want to apply global styles to html document.
EX: * {
    margin: 0;
    padding: 0;
    font-family: 'Courier New', Courier, monospace;
}
5. Group Selector: when we want to apply common styles to different elements.
EX: .arrange-element, h2 {
    padding: 20px;
}
6. Descendent Selector: when we want to select the elements at particular level then we will go for Descendent selector.
EX: .container div {
    background-color: aqua;
}

7. Child Selector: When we want to select the direct child of an element we will use child selector.
EX: .container > .second-element > span{
    font-weight: bold;
    font-size: large;
    font-family: serif;
    color: brown;
}
8. Adjacent sibling selector: When we want to select the adjacent sibling element we will go for Adjacent Siblint Selector.
EX: p + h2 {
    background-color: violet;
}

9. General Sibling Selector: When we want to select the same level sibling element we will go for General Sibling Selector.
EX: p ~ span {
    background-color: tomato;
}
10. Attribute Selector: when we want to select an element based on attribute & its value.
EX: [id="ele1"] {
    background-color: yellowgreen;
}

*** CSS Positions ***
=> when we want to give postions to the ui component in a web page we have to use CSS Positions
    
    static(default): we can't move the component horizentally or vertically.
    relative: we can move the component horizentally & vertically.
    absoulte: when we want to place an component from absolute position.
    sticky: The position: sticky property in CSS is a hybrid of relative and fixed positioning. It allows an element to switch between relative and fixed positioning depending on the user's scroll position.
    fixed: When we want to fix an component in a web page based on the requirement.
    