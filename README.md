# opacity-property
Opacity describes how opaque, or non-transparent, something is. For example, a solid wall is opaque, and no light can pass through. But a drinking glass is much more transparent, and you can see through the glass to the other side.  With the CSS opacity property, you can control how opaque or transparent an element is. With the value 0, or 0%, the element will be completely transparent, and at 1.0, or 100%, the element will be completely opaque like it is by default.

.sleeve {
  width: 110px;
  height: 25px;
  background-color: white;
}
In the .sleeve CSS rule, set the opacity property to 0.5.
.sleeve {
  width: 110px;
  height: 25px;
  background-color: white;
  opacity: 0.5;
}
In the .sleeve CSS rule, add the border-left-width property with the value 10px
.sleeve {
  width: 110px;
  height: 25px;
  background-color: rgba(255, 255, 255, 0.5);
  border-left-width: 10px;
}
In the .sleeve CSS rule, add the border-left-color property with the value black
