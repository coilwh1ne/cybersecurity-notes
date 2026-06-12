# Offensive Security Intro

### Purpose

- Learn what offensive security is.
- Try to hack my first web application.
- Learn what Gobuster is and how to use it.

---

### Theory

- Offensive security is a field of cybersecurity where security professionals simulate attacks to identify vulnerabilities in web applications, operating systems, networks, and other systems.
- I performed my first directory enumeration attack using Gobuster. I found a hidden directory and used it to transfer money to my profile.
- Gobuster is a directory enumeration tool used to discover hidden directories and files on a web application.

---

### Commands

```bash
gobuster dir -u http://fakebank.thm -w wordlist.txt
```
> in this command we say gobuster to enumerate directories from wordlist.txt on host with url ```text http://fakebank.thm``` and send to us which status code they have

 so, I get results:


```bash
ubuntu@tryhackme:~/Desktop$ gobuster -u http://fakebank.thm -w wordlist.txt dir

=====================================================
Gobuster v2.0.1              OJ Reeves (@TheColonial)
=====================================================
[+] Mode         : dir
[+] Url/Domain   : http://fakebank.thm/
[+] Threads      : 10
[+] Wordlist     : wordlist.txt
[+] Status codes : 200,204,301,302,307,403
[+] Timeout      : 10s
=====================================================
2024/05/21 10:04:38 Starting gobuster
=====================================================
/images (Status: 301)
/bank-transfer (Status: 200)
=====================================================
2024/05/21 10:04:44 Finished
=====================================================
```

---

### Conclusion

In this room I:
- huck web-site first time with directory enumeration tool Gobuster
- learn what offensive security is
- learn how to use Gobuster and what is it
