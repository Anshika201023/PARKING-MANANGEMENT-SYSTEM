# PARKING-MANANGEMENT-SYSTEM
PROJECT ON PARKING MANAGEMENT SYSTEM BASED ON HTML, CSS AND JS.

Used HTML - for the basic structure of parking management system web page.
Used CSS - for styling the web page.
Used JavaScript - for defining the functioning of the parking management system.

Assumptions in this project:
1) There are 7 parking slots available. If all are full, then no car could be parked.
2) Time is calculated as 1 min = 3 sec in back end.
3) For fine payment, for every 1 minute overstayed 10 ruppee is charged.

Following are the functioning of the system:
1) First the system will ask for the user's car number and for how much time duration will it be parked.
2) A unique slot will be alloted to the car and a notification will pop up for the same showing car number, slot number and time duration.
3) Time will be calculated for that slot and a remove button is there for every slot and also red color for slot indicate the reserved slot. If the user wants to remove the car, it will be removed and the slot will be vacanted again showing green color.
4) In the meantime, other cars can come for parking. When the parking system is full a notification will show that there are no available slots.
5) After the time has reached 0 min, a notification will pop up asking the user to remove the car otherwise will have to pay the fine. If not removed at 0 min then the time will reach in minus indicating overstaying.
6) When removed after overstaying, a notification will pop up that you have a fine to pay, the user will click ok and then the immediate next notification will show the fine calculated that they have to pay. When clicked ok then then the fine has paid and the spot will be vacanted again.
7) Simultaneously, the time will be calculated for different slots who are reserved.
