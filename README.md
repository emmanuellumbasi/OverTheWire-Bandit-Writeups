# OverTheWire-Bandit-Writeups

### :open_book: Introduction



Write-ups/solutions for OverTheWire Bandit CTF challenges. Includes step-by-step Linux commands, analysis techniques, and learning notes.


![image](<Screenshot 2026-06-15 181910-1.png>)


## :triangular_flag_on_post: Bandit Level 00 - 01

### Problem Description:
![image](https://user-images.githubusercontent.com/84661482/132094626-39a1e512-5658-4feb-bd4f-187f34b17514.png)


### Explanation:
This level is also a straightforward giveaway. As suggested by the level's hint, run **ls** to examine the current directory, then **cat** the **readme** file to view its information. 

If you don't understand the meaning behind any of these commands. Read the manual pages! **man** is the name of the command that pulls up manpages. So you use **man** by doing this:

```
$ man [name of command]
```
Here is the manpages of **ls** and **cat**:


### Solution:
```
bandit0@bandit:~$ ls
readme
bandit0@bandit:~$ cat readme 
ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If
 ```
> Password: **ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If**