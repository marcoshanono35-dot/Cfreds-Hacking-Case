# Cfreds-Hacking-Case
Documention of my solution(s) for the Cfreds "Hacking Case" digital forensics scenario which can be found here: https://cfreds-archive.nist.gov/Hacking_Case.html

The forensics software I'm using is the free version of Exterro's FTK Imager <br>
<img src="ftk_imager.png" alt="ftk imager logo" width="250" /> <br>

## Scenario:

On 09/20/04 , a Dell CPi notebook computer, serial # VLQLW, was found abandoned along with a wireless PCMCIA card and an external homemade 802.11b antennae. It is suspected that this computer was used for hacking purposes, although cannot be tied to a hacking suspect, G=r=e=g S=c=h=a=r=d=t. (The equal signs are just to prevent web crawlers from indexing this name; there are no equal signs in the image files.)  Schardt also goes by the online nickname of “Mr. Evil” and some of his associates have said that he would park his vehicle within range of Wireless Access Points (like Starbucks and other T-Mobile Hotspots) where he would then intercept internet traffic, attempting to get credit card numbers, usernames & passwords.

Find any hacking software, evidence of their use, and any data that might have been generated. Attempt to tie the computer to the suspect, G=r=e=g S=c=h=a=r=d=t.

This scenario comes with 30 questions to be answered, and the images you'll want to use are the EnCase images (note that only the first one opened in FTK imager for me, and only after downloading both).

## 1. What is the image hash? Does the acquisition and verification hash match?

To solve this, we use FTK imager's built-in verification function found on the top toolbar. <br>
<img src="toolbar-verify.png" alt="verification tool location" width="500" /> <br>
This will open a dialog box/window that will run for a few seconds (9 in my case) and then will leave you with a window containing the hashes.
