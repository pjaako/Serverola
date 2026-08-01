# What is Serverola?
Serverola is a home server that blends into the living room interior camouflaging itself as a standard living room appliance.
## So, Serverola is just another PC in an amplifier case?
Yes and no. On one hand, it is a PC in an amplifier case, on another hand, it is still a fully functioning integrated amplifier, plus any functionality one can get from the amp+computer duo.

## How is it possible to shove PC hardware into an amp without disturbing the amp hardware?
It is not. Well, not in the case of Onkyo A-3220 amplifier, which is my case. Forty-year-old A/B class audio boards had to go to give way to an Intel N100 motherboard, two 3,5" HDDs and  modern Class D amplifier hardware. The only exception is the original japanese passive Baxandall circuit board, since it is the most efficient way to retain original tone and volume controls and keep their functionality too.

## Why anybody would do this?
I don't know. For me, it was the following:
- High WAF due to the virtue of not looking as a piece of rack-mounted IT stuff
- Saving scarce and precious space under the TV with a 2-in-1 solution.
- Full control and upgradeability at both hardware and software levels
- A DIY audio that looks better than 99% of DIY projects
- A lot of fun and experience through messing things up and making every possible mistake

## Isn't it cheaper and easier to by a nice HTPC case or the whole NAS/miniserver?
Yes, it is. However, the solutions I know of do not check one ore more boxes in the least above. They are either ugly, or vendor-locked, or not safe, or too weak, or all of the above. I use to have a  QNAP “silent" NAS. No, it wasn't silent. It just didn't have fans, which is not enough. No proper HDD damping + IronWolf drives “health-checking” forever made the noisy barely bearable. It wasn’t powerful (good luck running containers on 2 GB of RAM), and got [wave](https://www.qnap.com/static/landing/2021/qlocker/response/en/) after [wave](https://www.qnap.com/en/security-advisory/qsa-22-21) of ransomware incidents. Still, it looked less ugly than other solutions and I kept putting up with it until the [Intel LPC clock bug](https://www.reddit.com/r/qnap/comments/klbogi/warning_many_qnap_nas_are_dying_due_to_a_cpu_bug/) bricked it and I had to jump through hoops to rescue my data. That was the birthday of Serverola.

# Why does Serverola got a public repo?
I know all too good I need to document everything to make my Serverola remotely maintainable in a year, and a git repository is fine to store the details. However good a reason that can be, it is often not enough a motivation for a human being. I hope a semi-public status will work as a commitment device. Besides, a public repo is free on GitHub.

## What does the Serverola repository contain?
- BOMs to reorder parts for repairs (the most important part)
- 3D Models to not start from scratch when I need a bigger case
- Schematic diagrams for custom wiring I made. 
- A log as a kind of comments, which are crucial not only for the SW development.


