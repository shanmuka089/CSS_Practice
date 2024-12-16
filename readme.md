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

*** Responsive Design ***
to change the screen layout based on screen sizes we have to use below features.
1. media queries
2. Flex Box (1-D)
3. Grid (2-D)
4. Bootstrap

    
Flex Box:
- It used to create responsive web design in 1 dimensional way, to create flex box we have to apply display:flex to the container.
- We have specify wrap property, by default it will be no-wrap.
- To add gap between the components we have to use gap property.
- To specify flex direction we have to use flex-direction: row/coumn
    1. flex direction is row:
        a. main axis is horizental (justify-content)
        b. cross axis is vertical (align-items) 
    2. flex direction is column:
        a. main axis is vertical (justify-content)
        b. cross axis is horizental (align-items) 

- when we using flex wrap & if we want to align the items along the cross axis we have to use align-content.
- when we using no wrap & if we want to align the items along the cross axis we have to use align-items.
- to align individual component along the cross axis we have to use align-self
