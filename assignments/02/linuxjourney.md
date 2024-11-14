# Aufgabe 2 
### 1. Die Schale 
Was soll auf das Display ausgegeben werden, wenn Sie "Echo Hallo Welt" eingeben? = Hello World
$ Datum = Command not found 
$ whoami = Command not found 

### 2. pwd
Wie finde ich das Verzeichnis fest, in dem Sie sich gerade befinden? = pwd

### 3. cd
Wenn Sie sich in /home/pete/Pictures befinden und zu /home/pete gehen wollten, was ist eine gute Abkürzung für Sie?= cd ..
Führen Sie den Befehl cd ohne Flags aus, wohin führt er Sie? = Er führt mich zum Home Verzeichnis

Es kann ziemlich anstrengend werden, die ganze Zeit mit absoluten und relativen Pfaden zu navigieren, zum Glück gibt es einige Abkürzungen, die Ihnen helfen.

. (aktuelles Verzeichnis). Dies ist das Verzeichnis, in dem Sie sich gerade befinden.
.. (Elternverzeichnis). Bringt Sie zu dem Verzeichnis über Ihrem aktuellen.
~ (Home-Verzeichnis). Dieses Verzeichnis ist standardmäßig Ihr "Home-Verzeichnis". Wie /home/pete.
- (vorheriges Verzeichnis). Dadurch gelangen Sie zu dem vorherigen Verzeichnis, in dem Sie sich gerade betreit haben.
$ CD.
$ CD ..
$ CD ~
$ CD -

### 4. ls
Welchen Befehl würden Sie verwenden, um versteckte Dateien zu sehen? = ls -a : weil dies alle elemente im ordner auflistet ohne ausnahmen

### 5. touch 
Wie erstellt man eine Datei namens myfile? = touch myfile

Neue Datei erstellen = touch test
Beachten Sie den Zeitstempel = kontrollieren mit ls -l bei touch wird jedes mal der Zeitstempel aktualliesiert
Tippen Sie auf die Datei und überprüfen Sie den Zeitstempel noch einmal = Aktualisierter Zeitstempel

### 6. file 
What command can you use to find the file type of a file? = you can type file .... 

### 7. cat 
 What's a good way to see the contents of a file? = you can type cat and u will see the content of the file

### 8. less
öffnet dir die datei und mann kann sich den inhalt anschauen 
Use the following command to navigate through less:

q - Used to quit out of less and go back to your shell.
Page up, Page down, Up and Down - Navigate using the arrow keys and page keys.
g - Moves to beginning of the text file.
G - Moves to the end of the text file.
/search - You can search for specific text inside the text document. Prefacing the words you want to search with /
h - If you need a little help about how to use less while you’re in less, use help.

### 9. history 
history listet dir alle benutzte commands auch wenn man gecleart hat 
clear = alles sichtliche ist weg aber die befehle bekommt man noch mit history 

### 10. cp 
cp = man muss sich im ordner befinden die datei als erstes angeben und dann die direction fürs cp

cp -r copying over a file 
cp -i if u have a  same filename this will create a prompt before overwriting 

wildcard operatoren = 
* the wildcard of wildcards, it's used to represent all single characters or any string.
? used to represent one character
[] used to represent any character within the brackets

### 11. Move 

How do you rename a file called cat to dog?
mv cat_to_dog cat_and_mouse

You can rename files like this:

$ mv oldfile newfile
Or you can actually move a file to a different directory:

$ mv file2 /home/pete/Documents
And move more than one file:

$ mv file_1 file_2 /somedirectory
You can rename directories as well:

$ mv directory1 directory2
Like cp, if you mv a file or directory it will overwrite anything in the same directory. So you can use the -i flag to prompt you before overwriting anything.

mv -i directory1 directory2
Let’s say you did want to mv a file to overwrite the previous one. You can also make a backup of that file and it will just rename the old version with a ~.

$ mv -b directory1 directory2

### 12. Make Directory
What command is use to make a directory? = mkdir

### 13. Remove rm 
How do you remove a file called myfile? = rm myfile

### 14.find 

What option should I specify for find if I want to search by name? = -name ($ find /home -type d -name MyFolder)
Achtung ohne speziellen namen sucht er alles durch!

### 15.help 

How do you get quick command line help for built-in bash commands? = help

### 16. man 

ist eine anleitung des folgendes commands

How do you see the manuals for a command? = man 

### 17. whatis
gleiche wie man nur kürzer bzw. zusammengefasst
What command can you use to see a small description of a command? = whatis

### 18. alias 
What command is used to make an alias? = alias 
BSp = $ alias foobar='ls -la'

### 19. Exit
How can you exit from the shell? = Exit







