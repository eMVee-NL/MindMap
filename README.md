# MindMap
This is a collection of some of mine mindmaps in Obsidian. No I did not design all mindmaps myself, some are from other awesome people. I ported some of them to an Obsidian variant since I use Obsidian for my cheatsheets. The mindmaps which I have in Obsidian are listed below:

* AD penetration testing
* Privilege Escalation
* Webapplication penetration testing
* SSTI
* File transfer techniques
* Pivot / Tunnels
* Wireless network pentesting


-----
## AD penetration testing Mindmap
The famous AD penetration testing mind map of Orange Cyberdefense made by mayfly (@M4yFly), viking (@Vikingfr) and Sat0rryu (@Sant0rryu) is high in my favorites. I regularly use the mind map to view a certain scenario and command. Unfortunately it is not possible to copy the text from the SVG file. Sometimes to great frustration that I have to retype it and make a typing error. For several months now I have been restructuring my notes from Joplin to Obsidian. While working with Obsidian I found out that you can make a mind map (canvas) and then copy commands. A good time to convert the AD mind map to something I can copy and paste from. Of course I also want to share this with you. If there are things in it that are not correct, or something is missing. Then let me know and I can update it.

[Direct link to the Mindmap (canvas)](https://github.com/eMVee-NL/MindMap/blob/main/AD%20Mindmap/Mindmap%20AD.canvas)

![AD penetration testing mindmap - inspired by Orange Cyberdefense](image/Mindmap%20AD1.png)

-----
## AD Enumeration with PowerView
Within the AD directory I put the Obsidian minmap for enumerating AD with PowerView.
The mindmap could be used to copy and paste commands to gather information about everything in AD.

-----
## Pivot
There are several ways to pivot into a network. The mindmaps are available in the pivot directory.
One of my favourite pivot tools is [Ligolo-ng](https://github.com/nicocha30/ligolo-ng). There is an awesome video about this on youtube (https://youtu.be/DM1B8S80EvQ) 
Based on this video I created a mindmap with all commands and where it should be executed.

![Pivot with Ligolo-NG](image/Ligolo-ng%20-%20Windows%20pivot.png)

-----
## Privilege escalation mindmap
Now that I'm updating my cheat sheet, I like to also make mind maps that I put at the beginning of my category. I use this as a reference. In this case I have divided the Privilege escalation mindmaps between Linux and Windows. I am still developing this one.

The mindmap for **Linux**. [Direct link](https://github.com/eMVee-NL/MindMap/blob/main/Privilege%20escalation%20Mindmap/00%20Mindmap%20Linux%20Privilege%20Escalation.canvas)
![Privilege escaltion Linux Mindmap](image/00%20Mindmap%20Linux%20Privilege%20Escalation.png)

The mindmap for **Windows**. [Direct link](https://github.com/eMVee-NL/MindMap/blob/main/Privilege%20escalation%20Mindmap/00%20Mindmap%20Windows%20Privilege%20Escalation.canvas)
![Privilege escaltion Windows Mindmap](image/00%20Mindmap%20Windows%20Privilege%20Escalation.png)


-----
## Web Penetration Testing Mindmap
I've created this mindmap for web penetration testing. I started with this mindmap during the eWPT course and I've updated it with some other techniques.
This is something that should be updated regulary in the near future.  The mindmap was origanally created in Freemind. But since I started moving all my notes to Obsidian and I allready importerd other mindmaps in my Obsidian notes, it was time to port this one as well. The mindmap is now available for Obsidian. Now I have to update the mindmap with some extra techniques and descriptions.

The mindmap for Obsidian can be found [here](https://github.com/eMVee-NL/MindMap/blob/main/Web%20Penetration%20Testing%20Mindmap/Mindmap%20Web%20Application%20Pentesting.canvas)

The mindmap for Freemind can be found [here](https://github.com/eMVee-NL/MindMap/blob/main/Web%20Penetration%20Testing%20Mindmap/Web-Penetration-Testing-Mindmap.mm)

![Mindmap web penetration testing](image/Mindmap%20Web%20Application%20Pentesting.png)

-----
## SSTI Mindmap
A while ago I noticed a mindmap to detect which technology is used if you are looking for an SSTI vulnerability. As usual I love those mindmaps, but in this one I could not copy the code for injection and paste it on the target. Therfore I created a variant on this mindmap and added it to my notes in Obsidian. If you would like to add it to your notes in Obsidian you can download the mindmap from [here](https://github.com/eMVee-NL/MindMap/blob/main/SSTI/SSTI%20Identification%20technology.canvas).
The mindmap looks like this:
![Mindmap SSTI](https://github.com/eMVee-NL/MindMap/blob/main/image/SSTI%20Identification%20technology.png)

-----
## File transfer mindmap

#### Mindmap transfer files from attacker to victim
There are many ways to transfer files as an attacker to a victim. Sometimes there are so many options that choosing the right technique can be difficult. With this mind map I try to provide insight into the possibilities of moving files from the attacker to the victim.

The mindmap is created within Obsedian, so you could import the file within Obsedian without any problem. The file could be downloaded from [here](https://raw.githubusercontent.com/eMVee-NL/MindMap/main/File-Transfer/Mindmap%20transfer%20files%20to%20VICTIM.canvas).

The mindmap fo transfering file from the attacker to the victim looks like this:
![Mindmap File transfer from attacker to victim](https://github.com/eMVee-NL/MindMap/raw/main/image/Mindmap%20transfer%20files%20to%20VICTIM.png)

#### Mindmap transfer files from victim to attacker
As mentioned earlier, there are many ways to transfer files from one machine to another. This mindmap is to show some possibilities from the victim machine to the attacker machine. Check which technologies are used on the victim. Use those technologies firstbefore starting any other technique.

The mindmap is created within Obsedian, so you could import the file within Obsedian without any problem. The file could be downloaded from [here](https://raw.githubusercontent.com/eMVee-NL/MindMap/main/File-Transfer/Mindmap%20transfer%20files%20to%20ATTACKER.canvas)
![Mindmap File transfer from victom to attacker](https://github.com/eMVee-NL/MindMap/blob/main/image/Mindmap%20transfer%20files%20to%20ATTACKER.png)


-----
## Wireless network pentesting
While preparing for the OSWP exam I had to build my own WiFi lab until I noticed [WiFiChallenge Lab](https://wifichallengelab.com/) from r4ulcl. Based on the virtual environment he created I tested several attack methods and techniques.
I have tried to document the whole thing into a mind map so that it becomes clear which attack paths and techniques can be used. The commands are easy to use and require a little tweaking here and there to use them. I would like to thank r4ulcl, BloodyPhoenix and Nick for reviewing the mind map.

It is possible that I will add additional tools and techniques in the future, such as attacks with Kistmet/WiFite/Fluxion, etc.
The mindmap is created for Obsidian, se download the file [here](https://raw.githubusercontent.com/eMVee-NL/MindMap/main/WiFi/WiFi%20Mindmap.canvas)


![Mindmap File transfer from victom to attacker](https://github.com/eMVee-NL/MindMap/blob/main/WiFi/WiFi%20Mindmap.png)



