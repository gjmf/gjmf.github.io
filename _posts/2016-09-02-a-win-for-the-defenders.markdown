---
layout: post
title:  "Security: A foiled attack against human rights - a win for the defenders!"
date:   2016-09-02 19:30:00
categories: tech-blog
tags:
 - infosec
---

As you may have already read at [Citizen Lab](https://citizenlab.org/2016/08/million-dollar-dissident-iphone-zero-day-nso-group-uae/) and [Lookout](https://blog.lookout.com/blog/2016/08/25/trident-pegasus/), Apple's iOS 9.3.5 release patches three remotely-exploitable 0-day vulnerabilities in iOS, which were discovered in the course of a clumsy attack against a human rights defender.

This is fascinating to me because it's such a decisive morale-boosting win for defenders - not only was the attack detected and foiled, but all three(!) Apple iOS 0-days behind it were effectively nullified less than two weeks after the attack.  (I'm also proud of the role that higher ed played in this - [Citizen Lab](https://citizenlab.org/) at University of Toronto led the way, with assistance from [ICSI](https://www.icsi.berkeley.edu/) at UC Berkeley.)

Of course there will remain a long tail of unpatched (therefore vulnerable) iOS devices for quite some time, but the publicity surrounding this attack and iOS' strong update adoption means these particular exploits are much less valuable now.  That in turn sets the bar higher for the development, sale, and use of other 0-days.  It also makes financing this kind of attack somewhat more challenging.  Let's bask in the win and not dwell too much on what that means in terms of a higher bar for defenders, shall we?  :)

Lessons I (re-)learned from this event:

* There is always hope for defenders. Even well-resourced nation-state-affiliated attackers make mistakes, particularly in tactical execution or in the expectations of gullibility.

  * This means we don't have to set an impossible bar for ourselves and our protectees.  "Think twice and ask questions about that unexpected link" is a good place to start, as is "patch promptly".

  * Of course, sometimes malicious links will be followed by well-intentioned people. Adding a protective layer such as DNS-based filtering (e.g. [OpenDNS Umbrella](https://www.opendns.com/enterprise-security/), or the nascent [Foghorn](https://github.com/hasameli/foghorn/blob/master/docs/bsides-preso.pdf)) and more comprehensive endpoint management (e.g. [Opswat Gears/Metadefender](https://www.opswat.com/products/metadefender/endpoint/management)) is worthwhile, too.    

* We who work in infosec may spend most of our time on infrastructure security impacting large groups of people, but we also inevitably rub shoulders with individuals who are of specific interest to an attacker (or several attackers).

  We should consider that hostile interest transitive, and defend our own personal infrastructure just as strongly as we defend our colleagues.  Let's follow the good example of the medical professionals who stay healthy, and not the mechanics who drive unreliable cars.

* Protecting mobile devices is just as important as protecting other endpoints and infrastructure.  This can of course be tricky given the muddy ownership issues.
 
  The approach that seems to work at Stanford is to require university MDM on any endpoint which may be used to access sensitive data, interpreted very broadly.  The MDM can then track, alert on, and enforce settings such as device encryption, screen lock, OS patching, and the like.


By the way, if I had to pick just one resource for high-quality time-efficient security insights, it would be [O'Reilly's Security Podcast](https://www.oreilly.com/topics/oreilly-security-podcast). The [Root Access Podcast](https://rootaccesspodcast.com/) from OpenDNS is also great.  I'd love to know what you find similarly worthwhile.

Hope you're well!  (and fully patched on a secure platform!)
