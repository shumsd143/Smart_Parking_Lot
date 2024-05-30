Functional Requirements
1. Create a parking floor. A parking floor consists of multiple parkingSpot
2. spots can be of multiple sizes.
3. Vehicle can be registered for parking.
4. A parking space will be allocated to vehicle if space is available
5. fee calculation according to duration.
6. Concurrency handling.


Classes and its Use
1. VehicleClass - hold different vehicle classes and its charges per hour/minutes.
2. ParkingSpot - hold the spot number, info of classes allowed for parking , availability.
3. ParkingFloor - hold the floor information and all the parking spot.
4. Vehicle - holds the vehicle info.
5. Allocation - hold the vehicle and parkingSpot allocated info. Timing and fee calcuation.
6. Transaction - holds info of amount received and mode of payments.