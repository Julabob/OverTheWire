Level 0 -> 1

Open a Kali Linux Terminal.

```bash
    ssh bandit.labs.overthewire.org -p 2220 -l bandit0
```
Type yes when asked for authenticity.

![Image](https://github.com/user-attachments/assets/9473f510-5b96-4b43-87e8-a6bac7080085)

Type the password *bandit0*

![Image](https://github.com/user-attachments/assets/2ceb9440-7500-4e5b-a65e-ba58b1486771)

You get the prompt.

We use *ls* to list all the files present in the directory.

```bash
ls -al
```
We then use cat to read the readme file which gives us the flag for the next level.

```bash
cat readme
```

![Image](https://github.com/user-attachments/assets/5a6c191d-6094-44b0-af61-ada24c229869)

We then login to Level 1 using the retireved password.

```bash
ssh bandit1@bandit.labs.overthewire.org -p 2220
```

![Image](https://github.com/user-attachments/assets/ec782886-73bf-4c1d-baac-2cec728f6a16)

When prompted for the password, we type ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If. We can proceed to level 1.

![Image](https://github.com/user-attachments/assets/ed6a4662-40f1-45a5-979b-2ded6cb19407)
