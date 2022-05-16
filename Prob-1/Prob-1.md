# Building a Simple Class

## Create a Car Class

What follows are step-by-step instructions for building a simple car class that holds three data elements.

1. Start by defining a class named Car. (This is a single line of code)
2. Insert class documentation that describes this class - see Canvas page: "Multiple Files and Module Documentation". This is a docstring just below the class definition code line described above.

> > The remaining code is all part of the class. That means it should be indented relative to the class definition line.

3. The first item to define is the constructor method. Remeber that this belongs to the class, so it should be indented from the class definition line. This class has three instance variables for make, model, and year. Include the parameters make, model and year in the constructor definition. Don't forget that self is always the first parameter.

> > Within the constructor define instance the variables. We want these to be "private" so use a leading underscore in the name. Use the constructor parameters to assign values to the instance variables.
>
> - _make
> - _model
> - _year
>
> > Once you have initialized the instance variables, the constructor coding is done.

4. Continue with the class definition by defining the following six methods.

> - set_make(self,make)
> - set_model(self,model)
> - set_year(self,year)
> - get_make(self)
> - get_model(self)
> - get_year(self)

> > At this point the class definition is complete. Continue by writing test code that will test all the methods defined in the class.

5. Create a TestCar() function that

> - creates a car
> - prints the car's properties using the get methods
> - updates the car's properties using the set methods
> - prints the car's properties again to demonstrate that the set methods worked.
> - add comments above each line of code to indicate what you think the following code is testing.

6. Use conditional execution ("if \_\_name__== "\_\_main__":) to call the TestCar function.
