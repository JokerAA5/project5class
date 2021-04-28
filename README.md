# project5class
#### Project Goals
We will be adding 4 new skills, 1 for each of the entity's corresponding traits.\
#### Implementation
For the warrior we will be making a new skill called PointyStick that is the result of the warrior's stength times 1.5\
We will implement this in the warrior's hpp file and cpp file utilizing it like the other attack commands with our specified parameters.\
For the mage will be making a new skill called HeadExplosion which damage is equal to the mages's intelligence times 2.5\
We will implement this in the mage's hpp file and cpp file utilzing the same techniques as for the warrior only this time using GetIntelligence()\
For the priest we will be making a new skill called HolyHandGrenade which damge is equal to priest's wisdom times 3.0\
We will implemet this in the priest's hpp file and cpp file utilziing the same techniques as the other attacks only this time using GetWisdom()\
For the rogue we will be making a new skill called Parkour which damage is equal to rouge's agility times 0.5\
We will implement this in the rouge's hpp file and cpp file utiilziing the same technqiues as before only this time using GetAgility()\
We will need to make sure for each entity's cpp file we add the new spell under useaction with the required spell name.\
We may also need to create new strings and uid codes for these spells as they have not been implmented and create a new input file that will have
the four party members use their new abilites to take down a group of monsters.\