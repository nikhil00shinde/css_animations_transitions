* CSS transitions allow you to change property values smoothly, but they always need to be triggered like hover. Property changes do not take effect immediately. Over a period of time, the property changes take place. 

* Animations transitioning between two states.The states between the start and final states are defined by the browser implicitly.
<table>
  <thead>
     <tr>
       <th>
       Transition	
       </th>
       <th>
       Animations
       </th>
     </tr>
  </thead>
  <tbody>
    <tr>
       <td>
       Transitions cannot loop (You can make them do that but they are not designed for that).
       </td>
       <td>
       Animations have no problem in looping.
       </td>
     </tr>
     <tr>
       <td>
         Transitions need a trigger to run like mouse hover.
       </td>
       <td>
       	The animation just start. They don’t need any kind of external trigger source.
       </td>
     </tr>
     <tr>
       <td>
      Transitions are easy to work in JavaScript.	
       </td>
       <td>
       The animations are hard to work in JavaScript. The syntax for manipulating a keyframe and assigning a new value to it, is very complex.
       </td>
     </tr>
     <tr>
       <td>
       Transitions animate a object from one point to another.
       </td>
       <td>
       Animation allows you to define Keyframes which varies from one state to another with various properties and time frame.
       </td>
     </tr>
     <tr>
       <td>
       	
Use transition for manipulating the value using JavaScript.
       </td>
       <td>
       	Flexibility is provided by having multiple keyframes and easy loop.
       </td>
     </tr>
  </tobdy>
</table>
	

 