# alx-higher_level_programming
<h3>Task 1 </h3>
<h4>0. Safe list printing<h4>

  <h4>Write a function that prints x elements of a list.</h4>
<br>
-Prototype: def safe_print_list(my_list=[], x=0):<br>
-my_list can contain any type (integer, string, etc.)<br>
-All elements must be printed on the same line followed by a new line.<br>
-x represents the number of elements to print<br>
-x can be bigger than the length of my_list<br>
-Returns the real number of elements printed<br>
-You have to use try: / except:<br>
-You are not allowed to import any module<br>
-You are not allowed to use len()<br>
guillaume@ubuntu:~/0x05$ cat 0-main.py<br>

  <h3>Task 2 </h3>
  <h4>Write a function that prints an integer with "{:d}".format().</h4>
<br>
-Prototype: def safe_print_integer(value):<br>
-value can be any type (integer, string, etc.)<br>
-The integer should be printed followed by a new line<br>
-Returns True if value has been correctly printed (it means the value is an integer)<br>
-Otherwise, returns False<br>
-You have to use try: / except:<br>
-You have to use "{:d}".format() to print as integer<br>
-You are not allowed to import any module<br>
-You are not allowed to use type()<br>

  <h3>Task 3 File:2-safe_print_list_integers.py</h3>
  <h4>Write a function that prints the first x elements of a list and only integers.</h4>
<br>
-Prototype: def safe_print_list_integers(my_list=[], x=0):<br>
-my_list can contain any type (integer, string, etc.)<br>
-All integers have to be printed on the same line followed by a new line - other type of value in the list must be skipped (in silence).<br>
-x represents the number of elements to access in my_list<br>
-x can be bigger than the length of my_list - if it’s the case, an exception is expected to occur<br>
-Returns the real number of integers printed<br>
-You have to use try: / except:<br>
-You have to use "{:d}".format() to print an integer<br>
-You are not allowed to import any module<br>
-You are not allowed to use len()<br>
 
  <h3>Task 4 File: 3-safe_print_division.py </h3>
  <h4>Write a function that divides 2 integers and prints the result</h4>
<br>
 Prototype: def safe_print_division(a, b):<br>
You can assume that a and b are integers<br>
The result of the division should print on the finally: section preceded by Inside result:<br>
Returns the value of the division, otherwise: None<br>
You have to use try: / except: / finally:<br>
You have to use "{}".format() to print the result<br>
You are not allowed to import any module<br>
 
