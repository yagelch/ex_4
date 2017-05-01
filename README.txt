Submitted by:
Yoel Simhovutch 303092951
Yagel Chernia	302588470

Game description:
The game simulates a scene in which a character (BroForReal) is trying to get weed for his friends.
He has a set of possible actions, including "collect weed" and "drop off weed." The police officer
character is given the goal of "smoke weed." He has a set of possible actions, including "collect 
weed" and "smoke weed." The "collect weed" is set with a randomized factor which is used in the case
of possible weed collection. The dog character is given the goal of "eating an edible object," i.e.
weed or candy. The objective of the player is to help a brother out and allow him to drop off as
many weed bags as possible on his sofa. This is done by A. planting more weed for him to collect or 
B. placing candy around the gaming field to distract the dog. As the game progresses, it becomes more
challenging because more dogs appear, making it harder for the bro to collect his weed. 


Agents:
BroForReal - his goal is making his friends happy (by dropping off weed). His actions are "collect weed"
and "drop off weed." His places of interest are the weed plant and the sofa. 
Police Officer - his goal is smoking weed (goal is rebooting every time he smokes). His actions are 
"collect weed" and "smoke weed." His place of interest is BroForReal.
Dog - his goal is eating as many things as possible. His actions are "eat weed" and "eat candy." His 
places of interst are weed plant and candy. 

Notes:
1. The player adds resources to the game by drag and drop.
2. The police officer can only approach BroForReal if he has weed and can only get his weed with a 
certain probability. 
3. Known bugs: if an action sequence was set to a character (dog or bro), and the path is now 
irrelevant, the said character cannot recalculate path.

Code credit:
None.
