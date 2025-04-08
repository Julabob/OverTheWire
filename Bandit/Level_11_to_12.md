First, we look at the directory's contents using the ls command. 

We hava a single file. Viewing the file gives a sequence of characters. The website mentions that the characters in the password have been rotated by 13 positions. We can use the *tr* to translate i.e. shift the characters by 13 positions.

```bash 
ls
cat data.txt
cat data.txt | tr 'a-zA-Z' 'n-za-mN-ZA-M'
```
In the *tr* command, *'a-zA-Z'* consists of all the lowercase and uppercase letters present in data.txt. *'n-za-mN-ZA-M'* states that, we replace the characters from first string into the format of second string i.e. a -> n, b -> o, c -> p ... A -> N, B -> O, C -> P ... Essentially shifting the characters 13 places to the right.

![Image](https://github.com/user-attachments/assets/1ccb0f45-0b3a-4a09-8d07-305e734de8cf)

When prompted for the password, we type 7x16WNeHIi5YkIhWsfFIqoognUTyj9Q4. We can proceed to level 12.

![Image](https://github.com/user-attachments/assets/b1bd1ce1-bbaf-43d4-a4a3-aab95dec50d4)