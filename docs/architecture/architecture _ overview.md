# System Architecture Overview
## Architectural Style
**Layered Architecture**
## Alternative Options Considered
**Monolithic Architecture**
- Definition : Everything in a single deployable unit.
- Advantage : The structure is simple to write and deploy initially.
- Disadvantage : Difficult to scale, tightly coupled and hard to manage as it grows.
  
  **Microservices Architecture**
- Definition : Divides the app into small services.
- Advantage : Very scalable, each service can have its own tech stack.
- Disadvantage :Very complicated deployment, much communication overhead.
   
## Trade-offs
- We have decided to choose Layered Architecture because the application is divided into layers: data, business logic, UI.
Easy to maintain, modular and scalable.
- Acceptable trade-off: Can be slow due to many layers if not optimally optimized.
## Potential Architectural Issues
-  Basic operations can become slower due to inter-layer communication.
-  Alterations in a layer can impact others if layers are not abstracted properly.
-  Exceptions in lower layers necessitate robust exception handling in higher layers.
## High-Level Architecture Diagram (add your real diagram)

+----------------------------+
| Presentation Layer |
| (React Frontend) |
+----------------------------+

 |
 v
 
+----------------------------+
| Application Layer |
| (Django Backend Services) |
+----------------------------+

 |
 v
 
+----------------------------+
| Data Layer |
| (PostgreSQL Database) |
+----------------------------+

**Explanation of Diagram**:

• Presentation Layer: Manages web user interface as well as dashboard
• Application Layer: Business logic and coordination between frontend and backend.
• Data Layer: Contains the database, ML modl storage as well as retrieval processes.

