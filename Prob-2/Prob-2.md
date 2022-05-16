# Building a Simple Class

## Create a Simple Student Class

Develop a class named **Student** that holds the following data about a student in instance variables:

- name
- ID number
- major
- GPA

You, as the programmer, have some decisions to make about these instance variables. In the previous program with the car, all the instance variables could be accessed as well as updated (i.e. each variable had both a get and set method). In some cases the desired behavior is to limit the ability of the class user to update certain data. That means the programmer needs to decide, for each variable, whether a get method or a set method should be coded. Coding a get method but not a set means the class user can see the informatino but can't update it.

For each of the variables in this class think about whether there is a need for the class user to potentially update the information. Can you name a case or situation where that variable would need to be updated? Document your rationale in a comment block above the class definition. **Explain your reasoning.**

Now it's time to start coding. You may want to refer back to the Prob-1 description for step-by-step instructions.

1. Code the class definition line
2. Include a docstring that defines the class
3. Code the constructor which initializes the instance variables
4. Code other methods for access or updating the instance variables. The code here will reflect your thinking about each of the instance variables discussed above.

Once you have written the class, write a unit test function that is called using conditional execution. The test function should:

- test all of the class's methods. Test one thing at a time.

As a final test create a list and fill it with student objects that match the output below. Then use a traversal loop to iterate over the students in the list. The traversal loop should print the information for each student. The ouptut should match the sample output below.

Hint: Go back and review text formatting. Use the width feature to define the columns.

```text
Name            ID Number       Major           GPA
Joe Bella       9933            Web Development 3.8
Tucker Blank    3399            Nursing         3.0
Gayle Ujifusa   1011            Baking          2.8
Edna Anker      9875            Medical Office  3.0
```
