# alx-higher_level_programming
<h3>Tasks </h3>
<h4>0. Safe list printing<h4>

  <h4>Write a function that prints x elements of a list.</h4>
<br>
Prototype: def safe_print_list(my_list=[], x=0):<br>
my_list can contain any type (integer, string, etc.)<br>
All elements must be printed on the same line followed by a new line.<br>
x represents the number of elements to print<br>
x can be bigger than the length of my_list<br>
Returns the real number of elements printed<br>
You have to use try: / except:<br>
You are not allowed to import any module<br>
You are not allowed to use len()<br>
guillaume@ubuntu:~/0x05$ cat 0-main.py<br>

guillaume@ubuntu:~/0x05$ ./0-main.py<br>
12<br>
nb_print: 2<br>
12345<br>
nb_print: 5<br>
12345<br>
nb_print: 5<br>
guillaume@ubuntu:~/0x05$ 
Repo:<br>

File: 0-safe_print_list.py<br>
