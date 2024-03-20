<img src= "https://www.hackthebox.eu/storage/avatars/00935a242722b9a2c700bdb6b65195f6.png" alt="no image">
<br>
<h1 align='center'>Crocodile Machine Pwned🎯</h1>

## Learning outcome📖
<p>
In the first tier, you will gain essential skills in the world of cybersecurity pen-testing. You'll start by learning how to connect to various services, such as FTP, SMB, Telnet, Rsync, and RDP anonymously. Next, you'll discover the power of Nmap, a valuable tool for identifying open ports on target systems, allowing you to assess their vulnerabilities. Lastly, you'll explore connecting to a MongoDB server, adding a valuable layer to your penetration testing knowledge. This tier will lay a strong foundation for your journey into the realm of cybersecurity.
</p>

<ul>
<li>✅Learn how to connect FTP, SMB, Telnet, Rsync and RDP anonymously.</li>
<li>✅Learn how to use Nmap to identify open ports.</li>
<li>✅Learn how to connect to a MongoDB server.</li>
<ul>


<h4>1) What Nmap scanning switch employs the use of default scripts during a scan?
</h4>

```console
-sC
```


<h4>2) What service version is found to be running on port 21?
</h4>

```console
vsftpd 3.0.3
```


<h4>3)What FTP code is returned to us for the "Anonymous FTP login allowed" message?
</h4>

```console
230
```

<h4>4) After connecting to the FTP server using the ftp client, what username do we provide when prompted to log in anonymously?
</h4>

```console
anonymous
```

<h4>5)After connecting to the FTP server anonymously, what command can we use to download the files we find on the FTP server?
</h4>

```console
get
```


<h4>6) What is one of the higher-privilege sounding usernames in 'allowed.userlist' that we download from the FTP server?
</h4>

```console
admin
```


<h4>7) What version of Apache HTTP Server is running on the target host?
</h4>

```console
Apache httpd 2.4.41
```

<h4>8) What switch can we use with Gobuster to specify we are looking for specific filetypes?
</h4>

```console
-x
```


<h4>9) Which PHP file can we identify with directory brute force that will provide the opportunity to authenticate to the web service?
</h4>

```console
login.php
```


<h4>10) Submit root flag
</h4>

```console
c7110277ac44d78b6a9fff2232434d16
```

<h1 align="center">ThankYou🎉</h1>