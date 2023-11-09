## Problem
Not all ancient ciphers were so bad... The flag is not in standard format.

## Points
70

## Solution
![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/ca5e33e6-f750-4f9f-9b31-28325d8acde4)
Take two prime numbers p,q and multiply 
We need an exponent e which is an integer and not a  factor of Φ(n) = (P-1)(Q-1)
d = (k*Φ(n) + 1) / e
Encrypted Data c = (Messagee)mod n
Decrypted Data = (cd)mod n
So e is 3(really small) so we can try finding the cube root

I tried to make my own code which would store all the possible answers into a txt file but that didn't work
![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/dede6bcd-273a-4841-852a-c8fb1ca5a02a)

I looked up at write up where they used gmpy2 which checks if the ith root of a number exists

![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/e06810e6-6b91-4254-baf0-25bed0abfbf0)

![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/c7f9c3f1-c2ef-4b03-a540-553c4d700a77)

Seems to be reversed, so I made it a point to reverse

![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/00210da6-6ced-482e-bd3d-c2bd6af0c347)

![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/7018169b-bf0e-4ccf-80ff-9180ffbba273)

## Flag
 picoCTF{e_sh0u1d_b3_lArg3r_a166c1e3}
