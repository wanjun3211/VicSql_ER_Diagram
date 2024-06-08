# Background 
Lincoln Professional Electronics and Repairs (LEAR) is a small company that provides services to repair smartphones, laptops, tablets and MP4 players.

When a customer brings a device to LEAR for repair, data must be recorded about the customer, the device and the repair. The customer’s name, address and a contact phone number must be recorded (if the customer has used the shop before, the information already in the system for the customer is verified as being current). For the device to be repaired, the type of device, model and serial number are recorded (or verified if the device is already in the system). Only customers who have brought devices into LEAR for repair will be included in this system.

A customer might sell an older device to someone one else who then brings the device to LEAR for repair, so it may be possible for the same device to be brought for a repair by more than one customer. However, each repair is associated with only one customer. When a customer brings in a device to be fixed, it is referred to as a repair request, or just “repair” for short. Each repair request is given a reference number, which is recorded in the system along with the date of the request, and a description of the problem(s) that the customer wants fixed. It is possible for a device to be brought to the shop for repair many different times. Only devices that are brought in for repair are recorded in the system. Each repair request is for the repair of one and only one device. If a customer needs multiple devices fixed, then each device will require its own repair request.

There are a limited number of repair services that LEAR can perform. For each repair service, there is a service ID number, description and charge. “Charge” is how much the customer is charged for the shop to perform the service, including any parts used. The actual repair of the device is the performance of the services necessary to address the problems described by the customer. Completing a repair request may require the performance of many services. Each service can be performed many different times during the repair of different devices, but each service will only be performed only once during a given repair request.

All repairs eventually require the performance of at least one service, but which services will be required may not be known at the time the repair request is made. It is possible for services to be available at LEAR, but that have never been required in performing any repair.

Some services involve only labour activities and no parts required, but most services require the replacement of one or more parts. The quantity of each part required in the performance of each service should also be recorded. For each part, the part number, part description, quantity in stock and cost is recorded in the system. The cost indicated is the amount that LEAR pays for part. Some parts may be used in more than one service, but each part is required for at least one service.

Based on the information, the Crow’s Foot notation ERD has been created to support LEAR’s business operation.

<img width="862" alt="ERD 1" src="https://github.com/wanjun3211/VicSql_ER_Diagram/assets/118150417/7968188e-ce2e-4444-aff2-36f17bbd20ad">


<img width="620" alt="ERD 2" src="https://github.com/wanjun3211/VicSql_ER_Diagram/assets/118150417/6b60426b-a325-4f87-b5e7-d687f0d6bc8e">
