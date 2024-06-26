# cowfriends
This is a very simple program which goes through all of your installed .cow files and makes the `cowsay` program say what you write as each of the different "cow friends".

Simply compile the program:
```
g++ --std=c++11 -pedantic -Wall -o cowfriends cowfriends.cpp
```

And run it like so:
```
./cowfriends Hello World!
```
Any arguments passed to it will be passed through to the cowsay program. You can also run it without any arguments, and it will pull from stdin.
