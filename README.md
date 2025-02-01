# picoCTF-reports
Challenge: "Where Are the Robots"
Flag: picoCTF{ca1cu1at1ng_Mach1n3s_8028f}

Solution: The technique of fuzzing was used to find the flag in this web exploitation challenge. By appending /robots.txt to the domain, a page listing paths was accessed, including 8028f.html, where the flag was found.
