# react-native-draggable
Draggable item for react-native!

```
npm install react-native-draggable --save
import Draggable from 'react-native-draggable';
```
How to use

```
return (
  <View >
    <Draggable renderSize={56} renderColor='black' offsetX={-100} offsetY={-200} renderText='A' pressDrag={()=>alert('touched!!')}/> 
    <Draggable reverse={false} renderColor='red' renderShape='square' offsetX={0} offsetY={0} renderText='B'/>
    <Draggable/>
  </View>
);
```

[![N|Solid](https://github.com/tongyy/react-native-draggable/blob/master/demo/demo.gif)]()

Props spec

		renderText:React.PropTypes.string => text of draggable item
		renderShape:React.PropTypes.string => 'circle' 'square'
		renderSize:React.PropTypes.number =>'36' 
		offsetX:React.PropTypes.number => offsetX with center
		offsetY:React.PropTypes.number => offsetY with center
		renderCorlor:React.PropTypes.string => [Colors](https://facebook.github.io/react-native/docs/colors.html)
		reverse:React.PropTypes.bool => reverse to initial position
		pressDrag:React.PropTypes.func => onPress event
    
    
   
