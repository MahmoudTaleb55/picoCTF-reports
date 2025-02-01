# picoCTF-reports
Challenge: "Where Are the Robots"

Flag: picoCTF{ca1cu1at1ng_Mach1n3s_8028f}

Solution: The technique of fuzzing was used to find the flag in this web exploitation challenge. By appending /robots.txt to the domain, a page listing paths was accessed, including 8028f.html, where the flag was found.
---------------------------------------------------------------------------
Assignment: Insp3ct0r

Flag: picoCTF{tru3_d3t3ct1ve_0r_ju5t_lucky?832b0699}

Solution: The source code of the webpage was inspected, revealing three parts of the flag. The first part was found at the end of the main source code, the second part in mycss.css, and the third part in myjs.js. Combining these parts revealed the flag.
---------------------------------------------------------------------------
Assignment: Logon

Flag: picoCTF{th3_c0nsp1r4cy_l1v3s_6edb3f5f}

Solution: The HTML source code was examined to find the correct username and password. After logging in, the flag was not found in the source code. Using the browser's inspect element tool, the application tab was navigated to, revealing a hidden admin cookie. Changing its value to True revealed the flag.
---------------------------------------------------------------------------
Assignment: Basic-mod1

Flag: picoCTF{R0UND_N_R0UND_B6B25531}

Solution: A Python script was written to find the flag using a for-loop. The script mapped numbers to characters based on provided criteria, ultimately revealing the flag.
---------------------------------------------------------------------------
Assignment: CVE-XXXX-XXXX

Flag: picoCTF{CVE-2021-34527}

Solution: Research was conducted on the RCE vulnerability discovered in 2021, identifying it as CVE-2021-34527, which was the flag.
---------------------------------------------------------------------------
Assignment: Roboto Sans

Flag: picoCTF{Who_D03sN7_L1k5_90B0T5_718c9043}

Solution: The website's source code was searched, but nothing was found. Using fuzzing, /robots.txt was appended to the domain, revealing Base64-encoded characters. Decoding them revealed the flag.
---------------------------------------------------------------------------
Assignment: Useless

Flag: picoCTF{us3l3ss_ch4ll3ng3_3xpl0it3d_6140}

Solution: The SSH work directory was accessed via webshell commands. Unable to open the useless file directly, the man useless command was used to access the manual and discover the flag.
