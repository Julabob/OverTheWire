First, we look at the directory's contents using the ls command.

```bash 
ls
cat data.txt
```
That lists a single file. Catting the file shows a huge random list of characters.

![Image](https://github.com/user-attachments/assets/58b3491f-310f-4635-a356-4ce73d5d0f2e)

It is mentioned in the website that the password is one of the few human-readable strings. We use the *strings* command which prints human-readable characters. Since it is also mentioned that the password contains a few "=======" signs in the beginning we can use *grep* to filter the output.

```bash
strings data.txt | grep "===="
```
![Image](https://github.com/user-attachments/assets/db558297-49b6-4c60-be49-0f6328fe380c)


When prompted for the password, we type FGUW5ilLVJrxX9kMYMmlN4MgbpfMiqey. We can proceed to level 10.

![Image](https://github.com/user-attachments/assets/ff9f7b23-46ea-4060-aa21-09428a553d1e)