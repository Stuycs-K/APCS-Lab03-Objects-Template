  <ol>
    <li>Write a Kitty class. Save the file in the same directory as the Driver file.</li>
    <li>
      Fill in all the required methods, but leave the body blank (non-void methods need a temporary return value).
      All methods should be public, and all instance variables should be private.
      <ul>
        <li>Constructor: <code>Kitty(String,int)</code> - initilaizes the name/age to the parameters</li>
        <li>Constructor: <code>Kitty()</code> - initializes the name and age to "Mittens" and 2</li>
        <li>Method: <code>int getAge()</code> - returns the age</li>
        <li>Method: <code>String getName()</code> - returns the name</li>
        <li>Method: <code>void changeName(String)</code> - sets the name to the provided name</li>
        <li>Method: <code>void makeOlder()</code> - adds one to the age.</li>
      </ul>
    </li>
    <li>Compile and run the driver with your "Blank" class.</li>
    <li>Start writing the methods. Every time you write a constructor/method you must:
      <ul>
         <li> Uncomment the part of the main that tests it.</li>
         <li> Actually compile and run the code.</li>
         <li> Commit any successful changes.</li>
      </ul>
    </li>
    <li>
      <p>After all of the above methods work try adding this method to the Kitty class: <code>public String toString()</code> </p>
      <p>toString returns "The amazing XXX" where you replace XXX with the Cat's name</p>
    </li>
    <li><p>Write a comment at the very top of your <code>Kitty.java</code> file where you answer the following questions:</p>
      <p>I)What changes when you run the main after this change? II) What does this suggest about what happens when you print an object?</p></li>
  </ol>
