Download Link: https://assignmentchef.com/product/solved-cosc2436-programming-fundamentals-iii-lab-2
<br>
Do the following exercise from the book. Follow the instructions for all assignments (one link up) and any specific additional instructions for each problem.

Ch. 4, Programming Problem 8, pg. 157

Specify and implement an ADT character string by using a linked chain of characters. Include typical operations such as finding its length, appending one string to another, finding the index of the leftmost occurrence of a character in a string, and testing whether one string is a substring of another. Program must compile and run.

Name the program charchain.cpp. Make sure the following requirements are met.

<ul>

 <li>Program must compile and run.</li>

 <li>Create an ADT character string as a class (LinkedChar is name I am using) that uses a linked list of each character. Do not use any STL container for the internal data structure.</li>

 <li>The LinkedChar class minimally has the methods in the UML diagram below. You can add more methods.</li>

 <li>Main function will have a menu of options.</li>

 <li>Enter new string and store as linked list of characters in an ADT LinkedChar class</li>

 <li>Get current length (number of characters stored) from the LinkedChar</li>

 <li>Find index of character in this LinkedChar</li>

 <li>Append another LinkedChar to this LinkedChar</li>

 <li>Test if another LinkedChar is submatch of this LinkedChar</li>

 <li>Quit</li>

</ul>

Example UML Class Diagram (missing attributes)

<table>

 <thead>

  <tr>

   <th>LinkedChar</th>

  </tr>

 </thead>

 <tbody>

  <tr>

   <td>LinkedChar();c</td>

  </tr>

  <tr>

   <td>LinkedChar(const std::string s);</td>

  </tr>

  <tr>

   <td>int length() const;</td>

  </tr>

  <tr>

   <td>int index(char ch) const; // -1 if no match</td>

  </tr>

  <tr>

   <td>void append(const LinkedChar&amp; lc);</td>

  </tr>

  <tr>

   <td>bool submatch(const LinkedChar&amp; lc) const;</td>

  </tr>

 </tbody>

</table>

Remember to upload all files before submitting.

<strong>charchain.cpp</strong>

Textbook:

<em>Data Abstraction and Problem Solving with C++, Frank M. Carrano, ISBN 978-0-13-446397-1</em>