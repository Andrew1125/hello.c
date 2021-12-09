~/ $ mkdir ~/pset1/
mkdir: cannot create directory ‘/home/ubuntu/pset1/’: File exists
~/ $ mkdir ~/pset1/
~/ $ cd ~/pset1/
~/pset1/ $ mkdir ~/pset1/hello
~/pset1/ $ cd ~/pset1/hello
~/pset1/hello/ $ ls
~/pset1/hello/ $ ls
~/ $ mkdir ~/pset1/
mkdir: cannot create directory ‘/home/ubuntu/pset1/’: File exists
~/ $ mkdir ~/pset1/
~/ $ cd ~/pset1/
~/ $ mkdir ~/pset1/
mkdir: cannot create directory ‘/home/ubuntu/pset1/’: File exists
~/ $ mkdir ~/pset1/
~/ $ cd ~/pset1/
~/pset1/ $ mkdir ~/pset1/hello
~/pset1/ $ cd ~/pset1/hello
~/pset1/hello/ $ ls
~/pset1/hello/ $ ls
~/pset1/hello/ $ ls
hello.c
~/pset1/hello/ $ make hello
clang -ggdb3 -O0 -std=c11 -Wall -Werror -Wextra -Wno-sign-compare -Wno-unused-parameter -Wno-unused-variable -Wshadow    hello.c  -lcrypt -lcs50 -lm -o hello
~/pset1/hello/ $ ls
hello*  hello.c
~/pset1/hello/ $ ./hello
hello, world
~/pset1/hello/ $ make hello
clang -ggdb3 -O0 -std=c11 -Wall -Werror -Wextra -Wno-sign-compare -Wno-unused-parameter -Wno-unused-variable -Wshadow    hello.c  -lcrypt -lcs50 -lm -o hello
hello.c:3:15: error: initializer element is not a compile-time constant
string name = get_string("What is your name?\n");
              ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
/usr/include/cs50.h:109:25: note: expanded from macro 'get_string'
#define get_string(...) get_string(NULL, __VA_ARGS__)
                        ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~
1 error generated.
make: *** [<builtin>: hello] Error 1
~/pset1/hello/ $ make hello
clang -ggdb3 -O0 -std=c11 -Wall -Werror -Wextra -Wno-sign-compare -Wno-unused-parameter -Wno-unused-variable -Wshadow    hello.c  -lcrypt -lcs50 -lm -o hello
~/pset1/hello/ $ ./hello
What is your name?
andrew
hello, andrew
~/pset1/hello/ $ 
