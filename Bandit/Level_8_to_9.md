First, we look at the directory's contents using the ls command.

```bash 
ls
```
That lists a single file. Catting the file shows a huge random list of characters.

![Image](https://github.com/user-attachments/assets/5237dc2c-370d-408d-8edb-a66c1460980c)

We will take the help of the *uniq* command to find the unique string. With the unique command to work effectively, we need all the duplicate strings to be beside one another. We can use the *sort* command to achieve this.

![Image](https://github.com/user-attachments/assets/f61113ba-7274-4cf9-8101-e50fc17c091b)

Finally, we use both commands in conjunction with the *-u* flag, which only prints unique lines.

```bash
sort data.txt | uniq -u
```

![Image](https://github.com/user-attachments/assets/e5547998-6208-43f0-b965-0836daf3273b)

When prompted for the password, we type 4CKMh1JI91bUIZZPXDqGanal4xvAg0JM. We can proceed to level 9.

![Image](https://github.com/user-attachments/assets/975b1e23-e0a3-4f25-904f-a6cc501eccb5)
