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

What is a Channel?
==================

Users can create and share content from a Channel, which is always under a Zone. So, the Channel is where you publish your content and let others view it.

Like Zones, channels can be private or public. Private channels can only be accessed by the Channel followers.

Following key points should be in consideration while interacting with Channels:

* Users can share content from a Channel (also from his Profile but will come later). 
* Channels can be private or public. 
* Private Channels can only be accessed by the Channel followers.
* Public Channels are open to other Octopus members.
* Users can follow existing public Channels in Octopus.
* A user can create a content inside a Channel if he is the Channel owner or it is permitted to Channel members by the owner.

What is a Profile?
==================

By default, each user will have a profile like any site having membership functionality. Users can create content from his profile and can share it only with contacts. Contacts are very similar to people on your mobile phones. Profiles are very handy if a user does not want to create a Zone or channel but just wants to share a video content with the people he may know.

Following key points should be in consideration while interacting with Profiles:

* Users can share content from their Profiles only with their Contacts. 
* Each user can have a single Profile. 
* Users can send a Contact request to other Octopus users.
