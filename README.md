# Disaster-managing-system

## Basic Idea
When disaster strikes, there may be cases that rescue team might not be able to help all people stuck at different places.
So we want all the nearby people to connect so that we have information of all people in a cluster.

## Elaborated Idea
At the time of calamity, people might get stuck such that there is no one around them, there may be cases where the rescue teams are unable to reach seperate people directly.
In that case, we develop a system which allows the people to connect with other people through radio frequencies in close proximity(say 5-10 kms).
This allows the victims to form a chain of signals which acts as a flag for the rescue teams and gives more precise location for the rescue teams to help them.

## Features
* Radio transmission
  - To send signals at predecided frequencies, which works on the principle 
    of scatter gather used in FPGAs.
  - These predecided frequencies will be different for different regions.
* Radio Devices
  - The devices will be available with people in the form of mobile app or 
    any radio signal reciever/transmitter.
  - The radio signals will be sent continuously once switched on, even if 
    the power goes off.
* Central server
  - This is the part which we want to do.
  - It will manage where the clusters are located.
  - Assign the requirements for different clusters.
  - Some basic text messages will be predefined in the form of radio frequencies for the users to chat
    amongst themselves and tell the needs.
  - Basic text messages can include "Yes", "No", "Food", "Stuck", "First-Aid", and some more to 
    directly report what is required urgently.

## Description
In our idea, we are trying to unite people and make them in a cluster so that our rescue team 
will be more efficient in working and we will have good success rate. We will use radio signals
instead of mobile gps etc. so to identify the cluster location and send this data to main server
of rescue team so that they can help them with food supply and medical kit first and then arrange
a rescue team for them.

## Implementation & Requirements
We will plan to set up our radio signals transmitter and reciever and make it co ordinare with our
server to provide location of cluster and also as we se two or more signals coming from nearby range
then we can connct them by sending a alert or information signal to them regarding their surrounding
environment and convey them some important messages and notices. We will not be requiring anything
special like gps or internet as because during clamity all these services can't not be relied upon.
Thus we want all people to unite and form cluster so that efficient rescueing can be done.
