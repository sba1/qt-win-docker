This is a simple docker image that can be used to cross
compile Qt applications for the Windows plattform. It
does not much more than building the environment using
the project at https://github.com/mxe/mxe.git, copying
the sources of the directory and then invoking
```qmake``` and ```make```.

To start the compiling process, simply enter

```
 $ ./build
```

from the command line. You can test the application on
Linux using Wine

```
 $ wine ./helloworld.exe
```

