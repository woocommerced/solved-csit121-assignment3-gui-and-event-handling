Download Link: https://assignmentchef.com/product/solved-csit121-assignment3-gui-and-event-handling
<br>
This assignment aims to provide you with some experience in writing codes using Java programming language that covers the following topics:




 GUI and Event Handling

<table width="732">

 <tbody>

  <tr>

   <td width="732"><strong> </strong><strong>Remember that: </strong><strong>1.         </strong><strong>All programs should be able to run on the lab’s computers. </strong><strong>2.         </strong><strong>You must put the following information on the header of each text and source file you will be submitting in this assignment:  </strong><strong>     Student’s full name:   </strong><strong>     Student’s ID:   </strong><strong>     Modification Date:  </strong><strong>     Purpose of this file (or program):   </strong><strong>3.         </strong><strong>Assignments that are not able to be compiled will result in zero mark given to the assignment. </strong><strong>4.         </strong><strong>You must only use the Java features that have already been covered in the lectures </strong><strong> </strong></td>

  </tr>

 </tbody>

</table>










<strong>TASKS: </strong>







For this assignment, you are required to write a Java application using GUI for a small company selling laptops. The application will be used by the staff selling the laptop. The user may choose the details of the laptop to be sold depending on the buyers request (the product with the chosen specification must be available). The application should allow the user to enter the details of the laptop to be sold, determine whether the product is available calculate the sales amount, keep information of the sales done, and display sales information.




The application should display a frame containing the following:




<ul>

 <li>The company name – displayed on a JLabel</li>

 <li>The image of the laptop – shown on a JLabel</li>

 <li>The laptop brand and model (e.g. HP ProBook 650, Dell Inspiron, Apple MacBook Pro) – a JComboBox is used to display the options. Include an event handling for this component where the image should change according to the model chosen</li>

 <li>CPU (e.g. intel CORE i5) – JComboBox</li>

 <li>RAM (4 GB/8 GB/16 GB) – use JRadiobutton to provide this selection</li>

 <li>Screen Size (e.g. 15 inches, 14 inches) – also represented by JRadiobutton</li>

 <li>Color – a simple JTextFiled for the user to type</li>

 <li>Additional Items (e.g. Additional RAM, laptop bag, antivirus software) – several JCheckBox where the user may choose more than one option</li>

 <li>Whether the laptop has a touchscreen or not – a single JCheckBox</li>

 <li>A JButton to make payment – implement an event handling method for this button. When the user click on this button it will display another JFrame to show the sales details and process the payment. (sample output shown below)</li>

 <li>A JButton to save the sale record – implement an event handling for this button. When the user click, it should create a Laptop object based on the details set on the frame and store the object in an ArrayList.</li>

 <li>A JButton to show the overall sales – implement an event handling method for this button to display all sales done so far on a message dialog box.</li>

 <li>A JButton to quit from the application – implement an event handling for this button to allow the user to quit.</li>

</ul>




The payment frame for the make payment button should have the following components

<ul>

 <li>A JTextArea that summarizes the sales details</li>

 <li>Total Price – an uneditable JTextField to display the overall charges</li>

 <li>Discount rate – a JTextField where the user can type the discount rate and should be initialized to zero Price after discount – an uneditable JTextField</li>

 <li>Payment – a JTextField where the user can enter the amount paid</li>

 <li>Balance – a JTextField to show the balance after payment is done</li>

 <li>A JButton to return back to the main frame – implement an event handling method for this button that will close the payment frame.</li>

</ul>




Your application should declare a class called Laptop to keep the laptop details as stated above. Include also a field to store the calculated price. The total price should depend on the brand, model and other options chosen. You are required to use reasonable prices for each of the options to perform the calculation in your application.




The following shows example output. You may have a different layout if you wish but the components must be the same.



















<sup>                                         </sup>area











