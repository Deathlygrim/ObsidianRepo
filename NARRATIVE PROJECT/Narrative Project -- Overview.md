#NarrativeProject

The main objects that I am aware are 
- characters
- the world
- the player
- the narrative
The first three interact with the narrative and, at least the way I think about it, their internal state are equivalent to the state of the narrative. Each of these three may be singular or multiple, discrete or more of something amorphous, omnipresent or not, etc.

I am writing this here more because this needs to be made into different subparts. 

The narrative will in turn define how the different objects change. Effectively, the way I think about it is a state machine composed of these three different types of state machines.

Main advantage is, easy and very efficient to implement. But it also raises an interesting question. Technically these systems do not require an action from the player to do a state change. They can interact with one another independent from the player. Other sialogue actions can be made to simulate this but I don't think it's intentional or integral. Most of this is characters reacting to a different state of the world. Maybe of each other but they won't change from that.
In principle this is against the principle that the player drives the actions. But its an interesting thought experiment. Anyway our goal should probably be a more linear story. Describing a story in an abstract set of states as for example failbetter does with fallen london of sunless sea is incredibly complicated imo. We would probably need an editor alongside this.

