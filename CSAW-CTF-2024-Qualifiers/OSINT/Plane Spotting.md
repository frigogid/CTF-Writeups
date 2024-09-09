![image](/CSAW-CTF-2024-Qualifiers/OSINT/Images/planespot.png)

A google search about this incident brings us to this article:
https://meidasnews.com/news/trump-plane-seen-parked-next-to-russian-government-plane-for-two-days

### Registration number US
We get the information that the former president is Donald Trump and his airplane is the 'Trump force one', a google search gives us the registration number which is: N757AF and we can also easily find out that the model of the russian plane is IL-96-300.

### Airportcode

In the articles above we also find out that the airport where Trump's airplane was parked next to the russian airplane was the Washington-Dulles airport and its code is: IAD

### Registration number RUS
After searching a bit more we find this article talking about the Russian airplane with a tweet which shows the registration number:
https://dailywrap.uk/russian-planes-unexpected-visit-to-the-us-raises-questions,7043084396886145a

![image](/CSAW-CTF-2024-Qualifiers/OSINT/Images/ruplane.jpg)

The registration number is RA-96018

### US city name

The challenge then talks about another russian airplane flew to the US.

After searching a bit more online I found this tweet which talked about another russian airplane which was in the US at the time as the incident:

https://x.com/MenchOsint/status/1806742133069738360?lang=sr

It's reg number is RA-96019, just one digit above the previous one.
I decide to look at it's flight history:

https://fr.flightaware.com/live/flight/RA96019/history
![image](/CSAW-CTF-2024-Qualifiers/OSINT/Images/historyflight.png)

This plane was flying in the US at 21:07 so it it looks like I'm on right track, let's have a closer look at this.
![image](/CSAW-CTF-2024-Qualifiers/OSINT/Images/planecitynear.png)

After looking at the plane's position on google maps we see that the nearest city is Trenton.

We combine all of these informations and we get the flag!

### Flag:
```
csawctf{RA96018_IAD_N757AF_Trenton}
```
