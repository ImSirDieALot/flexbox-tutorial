# Flexbox Tutorial

##### What is Flexbox?
A CSS3 layout mode that provides an easy and clean way to arrange items within a container
1. No floats
2. Responsive and mobile friendly
3. Positioning child elements is MUCH easier
4. Flex container's margins do not collapse with the margins of its contents.
5. Order of elements can easily be changed without editing the source HTML
6.  Ability to alter item width and height to best fit in the containers
7. Flexbox is direction-agnostic
8. Built for small scale layouts

### The FlexBox Look
![image of flexbox](https://github.com/ImSirDieALot/flexbox-tutorial/blob/main/assets/flex-box.png)
1. Main Container - Flex Container (red box). This is where we assign the `display: flex` property. 
2. Inside this main container we have the child items - `flex-items`
3. There are X (main) and Y (cross) axis. We can use certain alignment properties to the elements across these axes

### Main Flex Properties
display: flex | inline-flex 
flex-direction: row | column
flex-wrap: wrap | nowrap | wrapreverse
flex-basis: <length> {basically width}
justify-content: flex-start | flex-end | center
align-self: flex=start | flex-end | center = Default alignment to over ridden to individual elements
align-content: flex=start | flex-end | center
flex-grow: <number>
flex-shrink: <number>
flex: <integer>
order: <integer>
