1.information

Flag: picoCTF{the_m3tadata_1s_modified}

By using exiftool, we get the details of the file. 
In the metadata, we find a base 64 encoded string which upon decoding , we get the flag.




2.Matryoshka doll

Flag: picoCTF{ac0072c423ee13bfc0b166af72e25b61}

Using binwalk -e file_name command, we extract all the files that is embedded inside the image.
Upon extracting we get a base_images folder, inside which it contains the same image but of smaller size.
We have to go on extracting files untill we get flag.txt file which contains the flag for this problem.




3.Glory of the Garden

Flag: picoCTF{more_than_m33ts_the_3y3657BaB2C}

On using ghex we find that the flag is stored in the metadata.
So, by using cat garden.jpg | strings | grep pico, we get the flag for this problem.




4.MacroHard WeakEdge

Flag: picoCTF{D1d_u_kn0w_ppts_r_z1p5}

Here we are given a ppt file which upon extracting we get a bunch of files.
On changing the directory to slidemasters, we find a hidden.txt file which contains a base 64 encoded string.
On decoding the string, we get the flag.

