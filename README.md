# PW-Crack-1
Cylab CTF PW Crack 1

Q: Can you crack the password to get the flag? Download the password checker here https://challenge-files.cylabacademy.net/library/8bd8366ce732391ec41228eae748ee97bdcbba4e83438e196e6d8b4ecda2c224/level1.py and you'll need the encrypted flag https://challenge-files.cylabacademy.net/library/8bd8366ce732391ec41228eae748ee97bdcbba4e83438e196e6d8b4ecda2c224/level1.flag.txt.enc in the same directory too.

Hint1: To view the file in the webshell, do: $ nano level1.py

Hint2: To exit nano, press Ctrl and x and follow the on-screen prompts.

Hint3: The str_xor function does not need to be reverse engineered for this challenge.

Step1: Download all the files level1.py and level1.flag.txt.enc
wget https://challenge-files.cylabacademy.net/library/8bd8366ce732391ec41228eae748ee97bdcbba4e83438e196e6d8b4ecda2c224/level1.py
wget https://challenge-files.cylabacademy.net/library/8bd8366ce732391ec41228eae748ee97bdcbba4e83438e196e6d8b4ecda2c224/level1.flag.txt.enc

Step2: Open file level1.py and copy password.
nano level1.py or cat level1.py
Note: cat = display file content
    nano = open and edit a file
<img width="542" height="595" alt="image" src="https://github.com/user-attachments/assets/c937def4-6013-46c9-b007-de6b2c59d98c" />

Step3: python3 level1.py and enter password: 8713

<img width="457" height="216" alt="image" src="https://github.com/user-attachments/assets/e4e2f998-3047-468e-bd12-95a277c990a1" />

Step4: Final Answer: academy{545h_r1ng1ng_d218163c}
