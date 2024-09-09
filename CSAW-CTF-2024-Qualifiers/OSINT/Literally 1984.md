This was probably the most controversial OSINT chall of this ctf, personally I liked it a lot I found it pretty original.

![image](/CSAW-CTF-2024-Qualifiers/OSINT/Images/1984challdesc.png)

We don't have many informations with this description but if we look at the html code of the website we see something interesting:

![image](/CSAW-CTF-2024-Qualifiers/OSINT/Images/secret.png)

"&zwnj" is what we see between "name of" and "made a cover" in html.

If we search online this sequence of characters it brings us to this wiki page:
https://en.wikipedia.org/wiki/Zero-width_non-joiner

I then decided to search on youtube for singing related content using this sequence:
![image](/CSAW-CTF-2024-Qualifiers/OSINT/Images/songsearch.png)
 
 In the first results we find a japanese singing channel which looks like it has no name and goes by the nickname x0o0x_:
 ![image](/CSAW-CTF-2024-Qualifiers/OSINT/Images/nonamechannel.png)

On the popular videos of this channel we see a song called big brother, all of a sudden the name of the challenge makes much more sense.
https://www.youtube.com/watch?v=5lrseDtxX_E

We then look at the composer's name in the description of the video and we translate it in english which gives us our flag:

### Flag:
```
csawctf{Susumu_Hirasawa}
```
