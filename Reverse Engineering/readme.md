1.Shop

Flag: picoCTF{b4d_brogrammer_9c118bbf}

Here the edge case is that if we input negative numbers, it will multiply with the count and store the non-negative money in our wallet.
So, then we can buy the fruitful flag, which is an ascii encoded text, on converting gives us the flag.




2.speeds and feeds

Flag: picoCTF{num3r1cal_c0ntr0l_e7749028}

On running the command nc mercury.picoctf.net 28067 in the terminal, we get a set of G-code.
Using a gcode analyzer/viewer we find the flag written in a 3-D plane.




3.crackme-py

Flag: picoCTF{1|\/|_4_p34|\|ut_8c551048}

Here, the greatest number is just a decoy to hide the flag.
Instead of calling the greatest number function, by calling decode_secret(bezos_cc_secret) function , we get the flag.