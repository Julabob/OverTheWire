First, we look at the directory's contents using the ls command. 

We hava a single file. Viewing the file gives a sequence of characters. The webiste mentions that the password is in a base64 form. Using the *base64 -d* is used to decode the base64 encoding which gives our password to the next stage. to

```bash 
ls
cat data.txt
cat data.txt | base64 -d
```

![Image](https://github.com/user-attachments/assets/19b4b1ed-d1d8-4f84-80d9-e4d18bca0417)

When prompted for the password, we type dtR173fZKb0RRsDFSGsg2RWnpNVj3qRr. We can proceed to level 11.

[Image](https://github.com/user-attachments/assets/dff0b1bd-1def-432f-b245-82049e700a66)