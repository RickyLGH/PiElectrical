#Smart Sensors

This is the working repo for smart sensors

Establish during Electrical Y9 by Seiya Ono to simplify the workspace for people who just want to Eagle.

```
(c) Pioneers In Engineering
Design by: YOUR_NAMES_HERE
This design is open source hardware.
For more information, visit:
pioneers.berkeley.edu/opensource
```

The revision number should be REV 9A for Revision A Year 9

Arduino Pro Micro Pinouts:

![Pinouts](https://cdn.sparkfun.com/assets/9/c/3/c/4/523a1765757b7f5c6e8b4567.png)


##Git Work Flow

Protocol when working on Eagle files for Smartsensor, PDB, and Yogi Bear

**WARNING**: DO NOT MODIFY PIE.LBR WITHOUT DISCUSSING IT WITH THE PROJECT MANAGER(S) 

###Initial Setup of SmartSensor repo on your computer

Steps when working on EAGLE files:

1. In Terminal (mac) or GitBash (windows), navigate to your working directory (wherever you have SmartSensors).
2. Make sure your working directory is clean: git status
3. Pull from pioneers/SmartSensors: git pull origin master
  3. If you get a merge conflict, contact PMs for help.
4. Do your work in EAGLE.
5. Once you are at a good stopping point in your EAGLE work, commit your progress:
  5. git add path/to/your/file
  5. git commit -m "Make your commit message short and with this format" 
  5. *NOTE*: Commiting is like saving your file, but for all of PiE as well as your personal computer. And just like saving, Commit Early & Commit Often!
6. Repeat Steps 4 and 5 until you are finished with your EAGLE work.
7. Once you have made your last commit, push your files to the Smartsensors github repo: git push origin master
    * If you get a merge conflict, contact the PMs for help.

###FAQ:

Q: What's the difference between commit before I pull?

A: Do you want to keep any of the changes? Then commit those (the ones you want to keep) before you pull. Or else, the things you pull might conflict with your work, and you'll have a git disaster.

Q: I worked on my stuff, pulled, and everything I did went away!

A: As long as you committed, the PMs can recover your work for you.

###COMMIT MESSAGE FORMAT CONVENTIONS:

* Present Tense ("Reroute power traces on team flag" -- NOT "Rerouted power traces on team flag")
* No period at the end: ("Reroute power traces on team flag" -- NOT "Reroute power traces on team flag.")
* Keep your message length to about one sentence.

###MERGE CONFLICTS: WHAT DO??:

    -- Contact Seiya or Tobin by (pie email or text preferred).
