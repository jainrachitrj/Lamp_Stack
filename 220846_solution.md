# Details

Rename this file in the format `yourRollNumber_solution.md` (example, `220000_solution.md`) and submit the solution in the Google form link provided 
*** https://forms.gle/RZtKpFcKfrWrYYxF9 ***


## Your zeroth approach below

Reasoning - %%% Installed WSL2(Windows Subsystem for Linux) with help from given links. Then I cloned the git repo and ran the zeroth.c file with gcc. It gave the error - "cannot initialize array of 'int' from a string literal with type array of 'char'. So I changed the datatype to char and then code ran fine and gave the output - The answer of this challenge is output of "man" when run on the terminal, copy the exact output %%%

```
%%% What manual page do you want?
For example, try 'man man'. %%%
```

---

## Your first approach below (first.txt)

Reasoning - %%% In the zeroth.c file, clue is given to crack this challenge in the #define macro. It says - "not rot13 try all" which gives a hint to try the rotation encryptions. I tried them one by one on https://rot13.com/ and rot8 was the one to be used. The text written in first.txt file on decryption was - "noicee you did crack a rotation encryption on your own. The following is a clue for the next puzzle: CLASS of that INPUT"  %%%

```
%%% noicee you did crack a rotation encryption on your own. The following is a clue for the next puzzle: CLASS of that INPUT %%%
```

---

## Your second approach below (strings.txt)

Reasoning - %%% I unzipped "Lamp_Stack_Task.zip" using unzip command and then navigated to the directory "Lamp_Stack_task/question_mark/Lamp_Stack" and then to find the file strings.txt, I ran the command "file -name strings.txt" which gave me the location "A" of the file strings.txt which is - "./1/5/0/3/strings.txt". Displaying the contents of the file, I got some strings of which the string "8dc2evcCSSc4kUy" had password written after it. Thus, I had to find which file had this string in it. Then using the grep command, I searched for the string in all the files and found that two files - eleven.txt and final.txt had that string. %%%

```
%%% Location A is "./1/5/0/3" and the password for fourth.zip was "eleven.txt" or "final.txt" %%%
```

---

## Your third approach below (fourth.zip)

Reasoning - %%% I unzipped fourth.zip using unzip command and found that eleven.txt was the password for it. Then I again used the grep command to find the string "DevOps", using the -r flag for recursive search and found that the file "0.txt" at the location "4/2_inner" had the string - "DevOps{y0ur3_4w350m3_4nd_0ne_5t3p_c1053r}" %%%
```
%%% DevOps{y0ur3_4w350m3_4nd_0ne_5t3p_c1053r} %%%
```

---


- Name :  Rachit Jain
- Roll :  220846
- GitHub username: jainrachitrj
- Discord username: RachitJain#3006


## Do not tamper below this line

---

Q29yZSB0ZWFtIGtvIGZha2UgZG8=
