## Problem
This file was found among some files marked confidential but my pdf reader cannot read it, maybe yours can.

## Points
100

## Solution
I used Exiftool to check the metadata of the file

![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/accb2a2a-3c14-4a26-82fe-32fd6a1c3e03)

It turned out to be a shell script

![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/9f1c0de0-d692-4fb7-9bd7-9f38b09f3919)

Changed the permissions

![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/e10d4e9e-1803-4e16-9372-a5ae90eea6bc)

And executed it.

![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/84fd1be6-73bc-4e1e-bd7b-a6d862bda244)

This is what the flag looked like turns out it's a bzip2 file which I extracted.

![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/270224b4-0b9d-429c-9a7c-d0b72e4ceca1)

Now it seems to be a gzip file

![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/dfd9c628-508a-4421-8ff0-219415991401)

And then a lzip file.

![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/bad49796-f5a4-4812-85a0-9e40ddc11608)

Then a lz file

![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/1b3cf850-cf8d-434f-a8c5-417abf140c87)

Then a lzma file

![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/8f3abd35-fc91-48fa-87f6-41f81d359a74)

![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/10a5447e-2680-4348-9a20-daa0a25a62e8)

Then a lzo file

![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/bd672826-0b43-4c32-9618-3d3b0b610b44)
![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/667e1468-8255-47b7-9823-6472e4d8459a)

Then a lzip

![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/752ae2db-e7ae-4a5a-8ced-992f27aa6642)
![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/aeddd70d-a506-4bec-b7f8-b6ba26758f26)

Then a xz file

![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/7e402395-7d9f-476d-a8b8-5bde7d3e1e28)

Finally we get some ASCII
![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/a2195e86-8f97-423f-847a-21988c705580)

And the flag

![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/bef30e47-b9d2-412d-bf25-0f2893980b5b)

## Flag
picoCTF{f1len@m3_m@n1pul@t10n_f0r_0b2cur17y_79b01c26}
