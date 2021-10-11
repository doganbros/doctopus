#########################
Design Philosophy
#########################

Octopus has hierarchical content management architecture which lies behind Zones and Channels. Like in any membership based solutions, users have their own profile. Adding to this, in Octopus, any user can create multiple Zones and multiple channels in each Zone.

What is a Zone?
================

A zone is the base for creating channels, which means a channel would always belong to a Zone. Conceptually, Channels having similar contents would exist in the same Zone. This similarity can be based on content type, content resource or any other business level differentiation. 
Following key points should be in consideration while interacting with Zones:

* Users can not share content directly from a Zone.
* Zones can be private or public.
* Private Zones can only be accessed by the Zone members.
* Public Zones  are open to other Octopus members.
* Users can join existing public Zones in Octopus
* A user can create a Channel inside a Zone if he is the Zone owner or it is permitted to Zone members by the owner.

