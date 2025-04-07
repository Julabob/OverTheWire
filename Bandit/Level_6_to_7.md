First, we look at the directory's contents using the ls command.

```bash 
ls -al
```
That lists all the files. 

![Image](https://github.com/user-attachments/assets/284535af-40e0-4e7d-b9dd-e87d4592b8b7)


The directory is empty. I then type the cd command to go to the parent directory and then list the contents. I go to the parent directory once again. 

```
cd ..
ls
cd ..
```
![Image](https://github.com/user-attachments/assets/0b0ead9e-0711-484b-b43c-69afc71af3eb)

Taking help from the clues provided in the webiste, I search for the *group* and *user* options in the *find* command. I then use the find command to get the necessary file.

```bash
man find | grep "\-group"
man find | grep "\-user"
find -user bandit7 -group bandit6 -size 33c
```

However we are receive a lot of permission denied files.

![Image](https://github.com/user-attachments/assets/de2034dd-5c9f-4600-bd55-453b3419d6cc)

I use the same command with an additional command. 

```bash
find -user bandit7 -group bandit6 -size 33c 2>/dev/null
```
The additional *2>/dev/null* directs all error or permission denied files into a null file which leaves us with the file that satisfies all the conditions which we can access. Catting the file gives the password for the next level.
When prompted for the password, we type morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj. We can proceed to level 7.

![Image](https://github.com/user-attachments/assets/5a601b03-b682-4b7d-b424-49f0d2819696)