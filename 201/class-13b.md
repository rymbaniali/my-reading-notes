The transform property comes in two different settings, two-dimensional and three-dimensional. Each of these come with their own individual properties and values.

Transform Syntax: the transform property followed by the value. The value specifies the transform type followed by a specific amount inside parentheses.

2D Transform:

Two-dimensional transforms work on the x and y axes, known as horizontal and vertical axes. Three-dimensional transforms work on both the x and y axes, as well as the z axis. These three-dimensional transforms help define not only the length and width of an element, but also the depth.

- 2D Rotate:The rotate value provides the ability to rotate an element from 0 to 360 degrees. Using a positive value will rotate an element clockwise, and using a negative value will rotate the element counterclockwise. The default point of rotation is the center of the element, 50% 50%, both horizontally and vertically.
Example: .box-1 {
  transform: rotate(20deg);
}

- 2D Scale: Using the scale value within the transform property allows you to change the appeared size of an element. The default scale value is 1, therefore any value between .99 and .01 makes an element appear smaller while any value greater than or equal to 1.01 makes an element appear larger. It is possible to scale only the height or width of an element using the scaleX and scaleY values.

- 2D Translate: The translate value works a bit like that of relative positioning, pushing and pulling an element in different directions without interrupting the normal flow of the document. Using the translateX value will change the position of an element on the horizontal axis while using the translateY value will change the position of an element on the vertical axis.As with the scale value, to set both the x and y axis values at once, use the translate value and declare the x axis value first, followed by a comma, and then the y axis value.
Example: .box-1 {
  transform: translateX(-10px);
}
.box-2 {
  transform: translateY(25%);
}
.box-3 {
  transform: translate(-10px, 25%);
}


-2D Skew : is used to distort elements on the horizontal axis, vertical axis, or both.Using the skewX value distorts an element on the horizontal axis while the skewY value distorts an element on the vertical axis. To distort an element on both axes the skew value is used, declaring the x axis value first, followed by a comma, and then the y axis value.

Example: .box-1 {
  transform: skewX(5deg);
}
.box-2 {
  transform: skewY(-20deg);
}
.box-3 {
  transform: skew(5deg, -20deg);
}

-Combining Transforms:  It is common for multiple transforms to be used at once, rotating and scaling the size of an element at the same time for example. 

Example: .box-1 {
  transform: rotate(25deg) scale(.75);
}
.box-2 {
  transform: skew(10deg, 20deg) translateX(20px);
}

- To change the default origin position the transform-origin property may be used.

- The perspective of an element can be set in two different ways. One way includes using the perspective value within the transform property on individual elements, while the other includes using the perspective property on the parent element residing over child elements being transformed.
        
3d Translate: 

 Using three-dimensional transforms we can change elements on the z axis, giving us control of depth as well as length and width.

- 3D Rotate :With three-dimensional transforms we can rotate an element around any axis. Using the rotateX value allows you to rotate an element around the x axis, as if it were being bent in half horizontally. Using the rotateY value allows you to rotate an element around the y axis, as if it were being bent in half vertically. Lastly, using the rotateZ value allows an element to be rotated around the z axis.positive values will rotate the element around its dedicated axis clockwise, while negative values will rotate the element counterclockwise.

Example: 
.box-1 {
  transform: perspective(200px) rotateX(45deg);
}
.box-2 {
  transform: perspective(200px) rotateY(45deg);
}
.box-3 {
  transform: perspective(200px) rotateZ(45deg);
}

- 3D Scale : By using the scaleZ three-dimensional transform elements may be scaled on the z axis.

- 3D Translate: Elements may also be translated on the z axis using the translateZ value. A negative value here will push an element further away on the z axis, resulting in a smaller element. 

- 3D Skew : Skew is the one two-dimensional transform that cannot be transformed on a three-dimensional scale.

-Shorthand 3D Transforms: these properties include rotate3d, scale3d, transition 3d, and matrix3d. These properties do require a bit more math, as well as a strong understanding of the matrices behind each transform.

- Backface Visibility: it will hide the element whenever it is facing away from the screen.

Animations within CSS3 allow the appearance and behavior of an element to be altered in multiple keyframes. Transitions provide a change from one state to another, while animations can set multiple points of transition upon different keyframes.

There are four transition related properties in total, including transition-property, transition-duration, transition-timing-function, and transition-delay. Not all of these are required to build a transition, with the first three are the most popular.

The transition-property property determines exactly what properties will be altered in conjunction with the other transitional properties. not all properties may be transitioned, only properties that have an identifiable halfway point. 

The transition-timing-function property is used to set the speed in which a transition will move. 

To set multiple points at which an element should undergo a transition, use the @keyframes rule. The @keyframes rule includes the animation name, any animation breakpoints, and the properties intended to be animated.

the animation-name property is used with the animation name, identified from the @keyframes rule, as the property value. The animation-name declaration is applied to the element in which the animation is to be applied to. 


EIGHT SIMPLE CSS3 TRANSITIONS THAT WILL WOW YOUR USERS:

1. Fade in: Fade in effects are coded in two steps: first, you set the initial state; next, you set the change.
2. Change color: Animating a change of color used to be unbelievably complex, with all kinds of math involved in calculating separate RGB values and then recombining them.
3. Grow & Shrink
4. Rotate elements
5. Square to circle
6. 3D shadow
7. Swing
8. Inset border