# Arkanoid-Xinu-Game
Team Members: 
Marshood Ayoub (Marshood.) 
Firas Gadban 
Ameer amer 

To run the game , run the resulting exe, in this case Arkanoid.exe. Do not forget that Ctrl-F1 enables you to view inners of the system to run just enter "Arkanoid.exe" in the dosbox. 

Arkanoid game in DoxBox Using XINU .

You have to install dosbox to run the exe file : https://www.dosbox.com/download.php?main=1
You have to install XINU OS to compile the c file : http://math.haifa.ac.il/~oscourse/index_files/xinu4win.exe
You have to install the game and save it on XINU4WIN\NEWSRC\ArkanoidGame
Compile a game :
Lets say you would like to compile one of the examples in XINU4WIN\NEWSRC\EXAMPLES, ex5.c for instance.
if you want to run the exe file you can do : 
Open a DOSBOX window, and after this write :-
mount c c:<br> c:
then go to the folder of the game and run Arkanoid.exe 
if you want to compile the code Arkanoid.c you can install Xinu :- 
Open a DOSBOX window, and after this write :-
mount c c:<br> c: 
Use the "path" command to include tc\bin in your path, for instance:
path c:\tc\bin 

cd XINU4WIN\NEWSRC\FileName 

and then :<br>
tcc -I.. Arkanoid.c ..\XINU.LIB <br>
Arkanoid.exe<br>
NOTE !! 
To check the compilation and error messages run
tcc -I.. Arkanoid.c ..\XINU.LIB > errs
type errs






To run the application, run the resulting exe, in this case Arkanoid.exe.
Do not forget that Ctrl-F1 enables you to view inners of the system
to run just enter "Arkanoid.exe" in the dosbox.
