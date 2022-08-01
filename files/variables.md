# Variable scopes
* every function *call* gets its own ***stack frame***
* a stack frame is a space to store variables
* the first time a variable is **assigned to** (`foo = 2`) w/in a function, python assumes that we are creating the variable
* since each function call gets its own stack frame, we can use variables within a function and think just about that function itself, ignore the rest of the program!
* variables created outside any function are called ***global variables***
* global variables can be used in any function
* if you want to **assign to** a **global variable** inside a function, you must first write a line like `global var_name`