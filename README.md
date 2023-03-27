# CVRP_DHL

![Alt text](https://github.com/atasbh/CVRP_DHL/blob/main/CVRP_DHL-1.png)

The Capacitated Vehicle Routing Problem (CVRP) is a well-known optimization problem in operations research and logistics. The problem involves determining the most efficient way to route a fleet of vehicles to deliver goods or services to a set of customers, subject to capacity and distance constraints.

In CVRP, a set of vehicles with limited capacities are available to serve a set of customers who have demands for goods or services. The objective is to find the optimal routes for the vehicles to minimize the total cost, which is usually a function of the distance traveled and the number of vehicles used.

The CVRP is a complex problem due to the large number of possible routes and the constraints involved. Some of the main constraints in CVRP include:

Vehicle capacity constraints: Each vehicle has a limited capacity that cannot be exceeded, so the total demand of the customers assigned to each vehicle cannot exceed its capacity.

Time window constraints: Each customer may have a specific time window during which they can receive the delivery or service, and the vehicles must arrive within these time windows.

Distance or travel time constraints: The vehicles have limited travel distances or times, which can be affected by factors such as traffic or road conditions.

This project pertains to the optimization of delivery routes for three Vans with 3 tons capacity and 2 lorries with 10 tons capacity of DHL in Rome. The objective is to identify the shortest path for the vehicles to collect cargos from the branches and deliver them to the Airport warehouse. The OpenStreetMap API is utilized to obtain accurate distance measurements between the relevant locations, and the CVRP algorithm, implemented through Google OR-Tools, is employed to determine the optimal route.

The demand for each branch is as below:

[0.5, 0.5, 1, 2, 1, 0.5, 2.5, 1.5, 0.3, 2, 0.2, 2.5, 1, 3, 2.5, 2, 1.8, 2, 0.7]
