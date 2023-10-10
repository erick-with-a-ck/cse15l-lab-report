# Hello, world!
## ¡Hola Mundo!
**Testing Markdown rn!**
*This is for CSE 15L*
[Link](https://ucsd-cse15l-f23.github.io/week/week1/#week-1-lab-report)

* The commands ‘cd’ and ‘cat’ do nothing when put into the terminal without arguments. The former is not an error; earlier we saw that cd is solely in charge of changing directories, that’s it. Just putting cat into the terminal causes a weird error where our [user@sahara ~]$ completely disappears and the terminal has to be completely reopened to do anything. The ‘ls’ command displays ‘lecture1’ in bold blue text, which is the current directory opened.
![Image](https://i.imgur.com/NMvrJcR.jpg)

* ‘cd’ along with a directory (like lecture1) will open that working directory. This is the only time for the 9 total examples that the working directory changes. According to the terminal, ‘ls’ cannot reach a directory, saying there is “no such file or directory.” This is consistent with our earlier findings since, like pwd, all ls does is display names of files and folders in the working directory, it doesn’t actually do any manipulation. Pairing ‘cat’ with a directory name gives the exact same result as ‘ls'.
![Image](https://i.imgur.com/MLu4WnV.jpg)
![Image](https://i.imgur.com/6Y9lyTE.jpg)

* When pairing cd with a file (like Hello.class), the terminal says that file is not a directory. Cd can change directories but is unable to do anything with files so this is not an error. ‘ls’ along with Hello.class prints ‘Hello.class’. ls displays file names, and since Hello.class is a file, it did just that. A huge exception is thrown when combining cat and a file. This error is consistent with the code of the Hello.java file, which was written to throw an IOException when given the wrong argument.
![Image](https://i.imgur.com/okYjfoA.jpg)
![Image](https://i.imgur.com/nAgZ1xG.jpg)
![Image](https://i.imgur.com/Ztmdi4j.jpg)
