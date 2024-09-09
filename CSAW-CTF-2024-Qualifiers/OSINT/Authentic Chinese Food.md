![PDF Header in strings](/CTF-Writeups/CSAW-CTF-2024-Qualifiers/OSINT/Images/pandachalldesc.png)

On the top right corner of the picture we can see a phone number, after a quick google search we realise the number is from NewYork.

We can then search on google maps "Panda Express New York" and we will find the one corresponding to the picture above.

![[Images/pandapicture.png]]

It's address is : 423 Fulton St, Brooklyn, NY 11201

### Healthgrade

On this website if we type the address of the restaurant we can find out its grade says pending, it turns out this was the first part of the flag:

https://a816-health.nyc.gov/ABCEatsRestaurants/#!/Search/50055636

### Year Built

On some websites it says the building was built in 1920 but if we look at this article about this particular building it says it was built in 1931:
https://www.brownstoner.com/architecture/building-of-the-day-423-fulton-street/

### LLC Name

On many different housing websites if we type this address we can see it's owned by BNN FULTON FLUSHING OWNER LCC
https://www.compass.com/building/423-fulton-st-brooklyn-ny-11201/293532309167074133/

### FLAG: 
```
csawctf{Pending_1931_Bnn_Fulton_Flushing_Owner}
```
