# Parking_information-
Parking management system for a three-level parking facility
There exist 3 levels where each level can be represents by an 8*20 rectangular grid of car slots
There are 2 enetrences and two exists located at opposite sides on the ground level
When 
When a car enters, its registration is recorded and a specific car slot is allocated, The allocation is completely random for the level the customer prefers.
Charges are calculated according to the hours of stay and paid at the exit desk.The system can also facilitate regular customers, where their accounts accumulate the charges, so they can pay when they are asked to, or have pre-paid parking time


//User operations
1-->Managers should be able to set/change tables, create/amend regular customer accounts and also credit the existing accounts of the registered customers.
2-->Entrance desk operator should be able to record the information of either registered regular customer or a casual customer. As well as the allocation of a car slot.
3-->Exit desk operator should be able to free a previously allocated car slot. charge the leaving customer according to record exit times

//logic-->
Each element is off two states empty/full 
Exit time is recorded then at the exit desk the difference in time is the hours stayed.
Customer accounts that contain account name addresses and car registration including number of entrys, if data is the same then include a discount
