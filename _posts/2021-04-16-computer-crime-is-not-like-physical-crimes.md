---
layout: post
title: Computer security vs physical security
---

There was a [Norwegian article today on computer security](https://e24.no/boers-og-finans/i/56d6jK/dnb-frykter-mer-profesjonelle-hackere-loesepengevirus-er-farligst), from the point of view of the biggest bank in Norway (DNB).  I do see some common misconceptions, both in the article and in the comments field.

The title says that cryptolocker viruses are the worst, and there is a claim in the article that given enough resources on the attacker side, it's possible to break into any computer system.  Both claims are wrong - I would even call it *dangerous* thinking.

Related to this, a month ago there was an attack on the Parliament, the attackers could take out emails and other data from the Exchange servers used by all the parliament members.  The party responsible for the security claimed it was "impossible" to protect against the attack.  Now I believe that's also wrong - even *dangerous* thinking.

(Of course, there is always the "5 USD wrench attack" - but then again, that's in the realm of physical crimes, not a virtual crimes).

![5 USD wrench attack](https://imgs.xkcd.com/comics/security.png)

A physical door with a lock can never be 100% secure, an attacker with enough tools and time will always manage to break into a building.  I think many people consider IT systems to be something of the same, but it isn't.  An IT-system is either secure or vulnerable, it's actually quite binary.  If the IT-system is secure, then it's impossible to break in.  If the IT-system is vulnerable and connected to the internet, then it's almost a certainity that someone will break in, sooner or later - and most likely it will be impossible to identify the attacker or bring him to court.

That's the theory - the real world is a bit more complex.  Vulnerabilities may lurk around for years without being known, it's practically impossible to know that a complex computer system is secure.  Of course, users, developers and system administrators may be tricked - or even paid - into giving access to the system, but still the basic concept stays: if a computer system is broken into, it's something wrong with said computer system, and it's important to learn a lesson from it and ensure it won't happen again.  (And here are always ways to reduce the risks ofbeing struck by unknown vulnerabilties).

The Norwegian mentality is that if a crime happens, the guilt is always on the criminal and never on the victim (this is particularly important in the context of rape victims), and I was castigated in the comments section of the said article for hinting that things may be a bit different for virtual crimes.  One of the analogies in the comments section was blaming a burglary victim for not being at home and protecting the house.  Locking the door should be sufficient.  With an IT-system, if the door is properly locked, the burglary cannot happen, if the door is open, it's bound to happen.

![](https://ipfs.io/ipfs/QmZARWFJYQvqpBpY5vN9GVsXW94oiRQ1gXXZjphek8MMnM)

If there is an outage due to a crypto locker situation, the typical Norwegian reaction would be to be upset with the attacker.  Typical mentality is to never pay up for getting access to the files again (even if the alternative is weeks or months of outage - [Norwegian article](https://www.nrk.no/innlandet/kan-ta-et-halvt-ar-for-ostre-toten-a-rette-opp-dataangrep-1.15364106)), as it will only fund more criminality.  That was my gut reaction also first time I learned about the concept - but giving it a second thought, I think it's misguided.

The important lesson when being hit by a crypto locker virus is that the system is (or was) *vulnerable*.  As said, vulnerable systems connected to the internet will almost always be broken into, sooner or later, it's a given.  It doesn't help raising a clenched fist and being angry. From that point of view, the best thing that can happen is that the system is "only" struck by some harmless crypto locker virus.  It's even a luxury being able to pay for a "quick fix" for restoring it (though, one is in very dangerous terrain if one pays for a "quick fix" without addressing the root security problem).

The worst?  Having attackers covertly accessing systems for months or years, while copying sensitive data from the system, utilizing the foothold gained to get access to "deeper" systems, etc.

Don't get me wrong - I never used the word "guilt".  Clearly, from a juridical point of view, the attacker is doing a crime, and the owner of the attacked systems is innocent.  It's still important to keep in mind that the real victim may not be the owner of the system - the real victim may be the end user who trusted said system with private data.  I think it's quite *dangerous* if the owner of the system can just shrug of an attack with "it wasn't our fault, it was the fault of the attacker".

I did use the word "careless". I believe the very most of such attacks stems down to a careless (or clueless) attitude towards computer security, eventually a lack of time and energy spent on securing systems ... but sometimes, simply bad luck (as with my [corona infection](https://tobixen.github.io/covid-positive/)).  For all I know, sooner or later the same thing will happen to some of my equipment.