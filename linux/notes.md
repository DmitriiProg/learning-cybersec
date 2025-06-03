<p>Fact: First release of a Linux operating system was in 1991.</p>
Random definition: 
<p><b>Random-access memory (RAM; /ræm/)</b> is a form of electronic computer memory that can be read and changed in any order, typically used to store working data and machine code.</p>
<p><b>Operating System (OS)</b> is a layer between the hardware and the applications. From the application's perspective, the OS provides an interface to access the different hardware components, such as CPU, RAM, and disk storage</p>
<p><b>The graphical user interface, or GUI,</b> is a form of user interface that allows users to interact with electronic devices through graphical icons and audio indicators such as primary notation, instead of text-based UIs, typed command labels or text navigation. GUIs were introduced in reaction to the perceived steep learning curve of command-line interfaces (CLIs),which require commands to be typed on a computer keyboard</p>

<p>As mentioned in TryHackMe (linux fundamentals part 1) linux is lightweight, though it is operated through command-line.</p>

<ls>Commands:
<ul><b>echo</b> - Output any text that we provide (we don't need to use quotes if we print one word (for example, echo Hello), however we need quotes if there is a space between words (for example, echo "Hello Friend!"))</ul>
<ul><b>whoami</b> - Find out what user we're currently logged in as</ul>
<ul><b>ls</b> - listing (we can understand what files and folders exist; ls file_name will list the content of the file)</ul>
<ul><b>cd</b> - change directory (cd file_name)</ul>
<ul><b>cat</b> - concatenate (seeing the contents of files); I accidentally printed cat without arguments after it, and I entered stdin/stdout regime. To escape it you need to press ctrl + d or ctrl + c, or in the case of virtual machine in browser you may need to refresh page (f5)</ul>
<ul><b>pwd</b> - print working directory (finding out full Path to our Current Working Directory)</ul>
<ul><b>find</b> - used to find specific files (syntax: find -name file_name)</ul>
<ul><b>grep</b> - can use to search the entire contents of the file for any entries of the value that we are searching for. grep "what we want to find" file_name</ul>
<ul><b>wc</b> - to count the number of entries in file (for example, in logs) wc -l file_name</ul>
</ls>

<ls>Operators/symbols:
<ul>& - allows you to run commands in the background of your terminal (for example, if you need to download a large file you can use this operator to run the download on background allowing you to continue working in the terminal</ul>
<ul>&& - the same as & except allowing you to run more than 1 command on the background (for example, command1 && command2; though command2 will only run if command1 was successful.)</ul>
<ul>> - output redirector (echo hey > welcome; however if file "welcome" already exists it will be overwritten). To append the output to the bottom of the file you can use ">>"</ul>
</ls>

* - wildcard (to search anything of particular kind, for example find -name *.txt)

<p>To be updated.</p>
