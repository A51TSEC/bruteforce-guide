# Bruteforce. Introduction. Dictionaries and passwords.



What is brute-force?

  One of the most basic technologies for hacking is bruterofce. 
In this lesson it will be introduced well-known in hacking circles software for bruteforce.


Bruteforce is a technology of hacking where we enumerate passwords and usernames in order to get access to certain service. Bruteforce is known 


# Where brute-force can be used?

 Brute-force atttack can be used to break almost any system that do not have specific protection from it. 

Here is a short list of protocols and software hashing algorithms that can be cracked down by brute-force attack:

FTP, SMTP, RDP, Zip archive password, PDF password, Any database, Remote desktop,  SMTP , SSH , etc.


Lets have a look on dictionary creating process..

# Dictionary creation process:

Manual with extra information:

In first case we have our friend John who accidentally forget his password from his zip archive with photos from his marriage and his wife Margaret is very upset about this. In this situation we need to talk to our friend John and ask for questions. Questions should be like these ones:

When was your marriage?  Date
What passwords do you usually put on zip archives?
What password do you remember you could put on this this archieve?
What passwords do you usually put on websites?
And so on.

Based on this answers we will do individual dictionary. John's dictionary. In this dictionary we will put: date of his marriage in different formats, passwords he talk, passwords he use on websites, his phone number, his wifi passwords, his wife's cats birthday, etc.

After we will shuffle and generate all this information using specific software for dictionary creation on one file. We will name it john.txt and place in on our folder where we put johns_marrage.zip and our software to break password.

  Our text file named john.txt can be manually filled up based on information we have.
We will get something like:


After we have our dictionary done we can try to brute-force our achieve and could be lucky enough to crack this password down based on extra information we got from our friend.
 
This is a good example how to create simple manual dictionaries. But if we will not get our password we will need to use others dictionaries.  Dictionaries like:

# Manual without extra information:
Mostly based on thoughts and ideas of what password is set. As long as no information is provided and this is manual dictionary creation process it is mostly based on thoughts of one who is creating it.

# Based on well-known passwords:
For example: 777777, johny, password, PassWord, pass123, SexyAngel, qwerty,dragon.



# Based on location:

For example: bakerstr, londonstreet, Finesquare, macdonalds, CentralPark 

# Alphabet/Letters:

For example: aaaaa,bbbb,abcde,aaddffwwrr, zswdqdwqdwq,idwqdqwdqw,iioopppo


This is top of most used letters and it is smart to create dictionaries using this statistics.


# Numbers:

For example:12312312312,123457689,987765213,39732134

# Numbers repeation:

For example: 777888777999, 122333444555, 778899, 112233,0009999

# Mobile phones:

For example: +1-760-887-9998, +17608879998, 17608879998,7608879998

# Adresses in specific area:

For example:  ny,Newyork,california,Australia,CaNadA.bakerstreet,young.st



# Words in English:

For example: forest, east, EaT, man, idea, East.

# Words in other language:

For example: password, пароль, Passwort, fjalëkalim , contraseña

Top names for home pets:
For example: Brandy, Casey, Lucky






# Special symbols:

For example: !@#@@#!@, )()()@@#,*(#)~!!,#$@$@#$@#

# Mixed:

For example:  canada1987, eat123, P#SSW()RD, 1@2@3

# Dates and time:

For example:  12.12.2012, 2018.10.10,20122011,20130809,215909,235959

# Popular trands:

For example: gangnamnstyle, youtube,google,bitcoin,cryptocurrency,cybersport

# Morph/combined:  

For example:  gangnamnstyle123, gangnamnstyle!, gangnamnstyle2017, 2016gangnamnstyle 

# Default passwords:

For example: admin, administrator, blank, test, developer




# Birthday passwords:

For example:  10201982,19821712,1212,19921010


# Specially removed:

(when we have someone who can not type “ “a” and never uses 0”: )
For example: bcdef,llow,anger,ornge,mllow ,123456789.


Here is an example of username and password compilation in one file:

password.txt file exampe

After we created dictionaty file it will be right to soft it based on our thoughts and logic.
We can http://softfie.com/download/soft/sortir.rar download it from here and sort our dictionary.

# Software to generate dictionaries.




# What do we need to know before we will brute-force?


  Before talking about bruteforce we should take a look on protocols and ports.
Almost any webserver has some open ports with certain software running. Based on experience I can say that almost any web server has at least 3-5 open ports that could be attacked by brute-force.

 21 port stands for FTP server, 22 port stands for SSH server at 80 port we can find http server with administration login and so on.

Right after we did port scanning we can see open ports and based on this information we can think of ideas of what service to brute-force.

For example: We scanned some server where we found open 25 port which usually stands for smtp server. After we get all information about this software and open specific bruteforce software and prepare all dictionaries we can start.


	
*Nmap port scanning.


Statistics of bruteforce in World:

Statistics on attacks on servers  by country.





Statistics of brute-force cracking estimate time:











How to protect yourself from brute-force attacks?


Password strength:
It is well-known that based on password strength ability to crack it goes down.

Here is an example of password check. There are a lot of services 


Here is an example of password checker. http://www.passwordmeter.com/

* But always remember – if you put your password it means it can go to dictionaty.txt file ;)


URL for download.
https://securesafepro.com/passtrength-download.html


How to start brute-force? 


Before we start to brute-force we scanned our target and generated dictionary. Now we have to use specific software to do our job.
We can choice software based on service running on server or situation we are facing, for example to bruteforce MD5 hash or FTP bruteforce should be used different software.

Now lets take a deep look on our software:
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Patator. Hydra.Brutus ( Single bruteforce software with different protocols to choice )
https://github.com/1N3/BruteX ( Mass scan)

MD5 brute , SALT password ,Handshake bruteforce ,Wi-Fi bruteforce
Windows NTLM, Hashcat, Router bruteforce, Virus admin panel bruteforce

Generate list:
https://github.com/Broham/PassGen Smart generator

Dictionary list:
https://github.com/duyetdev/bruteforce-database
https://github.com/danielmiessler/SecLists/tree/master/Passwords

Additional:
https://github.com/N3TC4T/InstaBrute
https://github.com/superhacker777/hikka webcamera bruteforce hikka ( Hikvision)

Custom dictionary generator:
https://github.com/Mebus/cupp

Protection from ssl brutefoce:
https://jerrygamblin.com/2017/08/24/disallow-million-most-common-passwords/

IPBOX can be a good example of numberic bruteforce.

# Disclamer

Do not use this information to cause hard.
Use this information in educational purpose only.
Never use this software or algorythms in your country if it is prohibited by low.
