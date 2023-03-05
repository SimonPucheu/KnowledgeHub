# Berlingo Forum
## Central locking
https://berlingoforum.com/thread-7251.html

**central locking** - *HansW* - `09-07-2013`

Hi
My 2007 partner has the following problem:
If I press the button on the key fob it does lock, (except the back door) -- if I press the unlock button nothing happens.
If I turn the key in the drivers door, to lock: the central locking locks the rest of the doors, (except the back door).
If I unlock the car with the key, only the drivers door unlocks, the others don't do anything. There is no click at all.

I took the back door apart and measured the electric currents.
When closing, I get an impulse of around 9V between both wires for about 2-3 seconds.
When opening I get none.

I checked the solenoid outside the car with the battery recharger, and it works fine both ways, by changing polarity.

My question is:

These electrical lockers basically seem to work that way, that for closing and opening the polarity just is reversed.
In the older generation of cars this reversing was done by the central lock relay.

in the Berlingo's / partners, does such a relay exist and if so where is it?
Or, is this function integrated in the BSI unit and managed electronically?
If so, -- this would mean, that likewise the BSI is faulty,---

**RE: central locking** - *mikeB* - `11-07-2013`

Hi. My 2005 Berlingo Multispace behaved exactly as yours does, i.e. it would lock but not unlock. The key in the drivers door unlocks only that door.
The problem with mine was in the BSI. You need to remove it completely. There are a number of multipin connectors, all of which seem different. This is a good thing in that it's difficult to reassemble incorrectly, but a bad thing in that they all come apart differently. You have to be patient, especially when working in such a small space.

First of all, do the battery disconnect procedure (see other threads on this forum) then remove the connectors, then remove the BSI. You will see that the BSI is contained within a 2 part plastic case. Remove the case (needs care) which reveals 2 boards, one atop the other. One board contains the computer which contains all the intelligence, the other has the relays which do all the switching and carry the heavy currents needed. The boards are connected by (from memory) 2 sets of expanding pins. These pins are prone to going open circuit, especially if they ever get damp or wet. Separate the two boards (needs care as they are delicate) and minutely examine the pins and the sockets they mesh with. Make sure there is no trace of corrosion in either the pins or the sockets. Reassemble using an electrical lubricant. I used Briggs SKL switch cleaner lubricant. It prevents corrosion and conducts electricity. There are others available. See the CPC (Farnell) website for more info on this.
Reassemble the boards carefully , then the covers and reinsert the multipin connectors. I was elated when it all worked perfectly. That was a year ago and it still works. I hope it does for you. The problem was in the signals from the computer not getting to the relay which opens the doors.

**RE: central locking** - *HansW* - `14-07-2013`

Thanks Mike, -- I had a similar idea, but now have a fair idea. I have to think about it, -- in terms of worst case scenario etc. but it looks to be a do-able thing.
I will report back.
I got as far as having the boards here on the desk, but I am unable to separate them -- They seem to be clued together, -- is there a trick, and what is it to separate them without damaging the boards? does the black plastic stay with the top or the bottom?
Meanwhile, i discovered traces of oxidation on one multiplug, so cleaned up the pins and now will see, if that was the problem, ---
All back in again, and no betterment,--

**RE: central locking** - *mikeB* - `14-07-2013`

By black plastic I assume you mean the 2 covers. I found them quite tricky to separate but they do need to be removed to reveal 2 printed circuit boards connected together by 2 sets of expanding pins.

The printed circuit boards are attached in an offset way, i.e. not exactly on top of each other. On the upper edge of the upper board, the one containing the relays and fuses, you will see 2 lines of 8 pins, each about 4 cm from the edge of the board. You need to insert a flat tool between the boards and twist it slowly and carefully to separate the boards. I used a wooden ruler 1 inch thick. Once separated you can see on the lower board the expanding pins. These need to be examined under a magnifying glass to be sure there is NO corrosion. The sockets on the upper board need also to be examined closely. Then spray with Briggs etc and reassemble carefully.

If you have already done all this it is possible you have a faulty relay. The ones which control central locking are YH119 012-1z11-1A. One controls locking, the other unlocking. You can apply 12 volts to the coil and you should hear it click. You can test the resistance between the contact pins to see which one, if any, is faulty. I searched for YH119 on Google and got the full spec with pin details. It's all a bit tedious but it should produce the desired result. Obtaining a relay is probably best acheived by buying a scrap board and sweating them out. Not an easy job, and it needs a soldering iron with at least 100 watts power. But I would put money on the pins connecting the boards. The relays are robust and seldom go open circuit.

So the best course of action is to separate the boards and have a good look for corrosion. The simple act of separating and reconnecting the boards might well be enough. Persevere! It's worth it. An afterthought - if you can't separate the boards it suggests the pins ARE corroded together. So it's definitely worth a very close look at this. You definitely need to separate them.

A further thought - if you found corrosion on a multiplug this is evidence that it has been wet at some time. The pins MUST be suspect. Another observation - when the key fob was clicked to open the doors the lights flashed but no noise from the doors. Also the tailgate didn't lock at all.

**RE: central locking** - *HansW* - `14-07-2013`

Hi Mike
Ok, I tried again and succeded!!!

I have a second complete unit, where there is no water damage, -- so my plan was to simply take the complete relay board and stick it to my computer board,--

Did that in the meantime, -- all together and it WORKS!
So, thanks for the help here.

**RE: central locking** - *mikeB* - `14-07-2013`

Your strategy is spot on. A new servo board would be a good way.

To separate the boards I suggest a flat, soft tool, slightly wider than the distance between the boards. When inserted near to the pins it should be possible to twist the tool and force the boards apart. They are NOT glued or soldered. The expanding pins are just a tight fit. Corrosion will tend to bind the boards together. A mild releasing agent like WD 40 might help. You will have to spray it sparingly then wait a few tens of minutes for it to work, then try again. They WILL and MUST come apart to check for corrosion. I am sure you will find this is the cause of your problem.

PS Have you tried to separate the boards on your spare BSI. Good practice I think!

**RE: central locking** - *HansW* - `14-07-2013`

cross posting -- of course I separated the spare board first, -- scratched one of the circuits a little bit, but insulated it with glue, -- then separated the second board, cleaned up the pins with 400 sandpaper and checked them with the magnifying glass, -- put the old computer board to the new relais board, -- pressed with two bits of soft timber and have them as close as possible.
We will see how this stands up the test of time!
To be recommended!

**RE: central locking** - *mikeB* - `17-07-2013`

Well done, and I suspect youi have a smile on your face. My local Citroen main agent had my car for a day and could not find the fault. With help and a ciircuit diagram from Rustcrat (one of the very helpful contributors on this forum) I came to the same conclusion as you. And mine is still working after a year. If it happens again I know where to look.

In fairness to the Citroen garage they didn't charge me