Download Link: https://assignmentchef.com/product/solved-sys466-lab-1
<br>
<strong> (2%): System Sequence Diagrams</strong>

<ul>

 <li>This is an individual lab and must be completed in the lab room.</li>

 <li>Using StarUML, create the required diagrams as per the instructions in this lab, then post the model you created to Blackboard, named with your name e.g. Lab1MaryLee.uml</li>

</ul>




<strong>Setting up StarUML:</strong>

<ul>

 <li>When opening a new model select the default configuration (use case model, analysis model, etc)</li>

 <li>Before you create any of your SSDs do the following:

  <ul>

   <li>Select tools

    <ul>

     <li>options</li>

     <li>diagram

      <ul>

       <li>Message signature: “select name only”</li>

       <li>Show activation: uncheck this box.</li>

      </ul></li>

    </ul></li>

  </ul></li>

</ul>

<strong> </strong>

<strong>Case Study:</strong>Venus Security is planning a system to allow managers to create routes that security guards must follow when working in a building.  Managers define checkpoint locations then put this information on sensors that are inserted at the locations. Security guards scan each sensor on a route as they walk, using a phone app. The system records the time that each sensor was scanned and also shows any special instructions for that location e.g. “Check the door to make sure it is locked”




<strong>Use case diagram:</strong>

<strong>For each of the four scenarios below create a SSD in the use case model. You will need to add the actors to the use case model also. Name each SSD as follows: Scenario1, Scenario 2, etc. </strong>

<strong>Your teacher will show you how to use StarUML. Here are a few tips:</strong>

<ul>

 <li>Select Use Case Model, right click, add diagram, Sequence diagram</li>

 <li>Drag in actor, pull in object from the toolbox and name it System</li>

 <li>Pull in Stimulus from toolbox for messages. If it is a return, click on the message and in the Properties window select and actionkind of return.</li>

</ul>

<strong> </strong>

<strong>Use Case 1: Create Check Points</strong>

<table>

 <tbody>

  <tr>

   <td width="312"><strong>Manager</strong></td>

   <td width="312"><strong>System</strong></td>

  </tr>

  <tr>

   <td width="312">Requests to create a check point</td>

   <td width="312">Generates a check point id; and asks for location information.</td>

  </tr>

  <tr>

   <td width="312">Enters location id and description and special instructions</td>

   <td width="312">Creates a checkpoint using the given information.</td>

  </tr>

  <tr>

   <td width="312">Scans a sensor (a small chip that will be mounted at the specific location)</td>

   <td width="312">Updates the sensor with the check point information.Displays the sensor id and all checkpoint information</td>

  </tr>

 </tbody>

</table>

<strong> </strong>

<strong>Use Case 2: Create Route</strong>

<table>

 <tbody>

  <tr>

   <td width="311"><strong>Admin</strong></td>

   <td width="313"><strong>System</strong></td>

  </tr>

  <tr>

   <td width="311">Requests to create a route.</td>

   <td width="313">Asks for a route name.</td>

  </tr>

  <tr>

   <td width="311">Enters a route name.</td>

   <td width="313">Lists all available check points showing location information.</td>

  </tr>

  <tr>

   <td width="311">Selects a check point to add to the route.</td>

   <td width="313">Adds the check point to the route. Displays the location of each check point on the route.</td>

  </tr>

  <tr>

   <td width="311">Repeats the above until the route is done</td>

   <td width="313"> </td>

  </tr>

  <tr>

   <td width="311">Specifies the order in which the locations (check points) will be followed and scanned.</td>

   <td width="313">Reorders the locations/sensors as per the input and saves the route with its name.Displays the list of locations/sensors on the route in the order they will be followed.</td>

  </tr>

 </tbody>

</table>

<strong> </strong>

<strong>Use Case 3: Follow Route</strong>

<table>

 <tbody>

  <tr>

   <td width="311"><strong>Security Guard</strong></td>

   <td width="312"><strong>System</strong></td>

  </tr>

  <tr>

   <td width="311">Request to start following route.</td>

   <td width="312">Shows all routes.</td>

  </tr>

  <tr>

   <td width="311">Choose a route name.</td>

   <td width="312">Shows all locations on the route.</td>

  </tr>

  <tr>

   <td width="311">Goes to the next route location and scans the sensor</td>

   <td width="312">Records the visit and displays any instructions</td>

  </tr>

  <tr>

   <td width="311">Repeats the above until done.</td>

   <td width="312"> </td>

  </tr>

 </tbody>

</table>

<strong> </strong>

<strong>Use Case 4: List Checkpoints Visited for a route</strong>

<table>

 <tbody>

  <tr>

   <td width="302"><strong>Admin</strong></td>

   <td width="321"><strong>System</strong></td>

  </tr>

  <tr>

   <td width="302">Asks to see all routes for the day</td>

   <td width="321">Shows all routes that were followed.</td>

  </tr>

  <tr>

   <td width="302">Chooses a route.</td>

   <td width="321">Shows each location on the route and when it was visited.Also lists any missed locations.</td>

  </tr>

 </tbody>

</table>


