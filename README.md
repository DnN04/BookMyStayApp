Goal: Introduce centralized inventory management by replacing scattered availability variables with a single, consistent data structure, demonstrating how HashMap solves real-world state management problems.

Actor: RoomInventory – responsible for managing and exposing room availability across the system.

Flow:

The system initializes the inventory component.
Room types are registered with their available counts.
Availability is stored and retrieved from a centralized HashMap.
Updates to availability are performed through controlled methods.
The current inventory state is displayed when requested.