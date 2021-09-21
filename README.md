# Real World


### Parameter vs Argument

**Parameter** - _make_omelette(bacon)_

Bacon is an argument, or value passed to the function. 


**Argument** - _def make_omelette(ingredient)_

Ingredient is a parameter, or the variable name used to reference the arguments passed to the function.


        Parameter != Argument

Functions search for variable locally first. If the variable is not in the local scope, it expands the search to the global search.


 Python will automatically pass a reference to that object as the first argument.

 Python provides a convenient way to access and modify that object from within the method.