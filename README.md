# System Design

System design is the process of designing the elements of a system such as the architecture, modules, and components, the different interfaces of those components, and the data that goes through that system.

The purpose of the System Design process is to provide sufficient detailed data and information about the system and its system elements to enable the implementation consistent with architectural entities as defined in models and views of the system architecture.


# 1) Requirements Clarification:
the beginning point of software development activity. Software requirement is one such area to which little importance was attached in the early days of software development, as the emphasis was on coding and design. The main assumption was that the developers understood the problem clearly when it was explained to them, generally informally. Therefore, the need for a more rigorous requirement analysis phase arose. Now, for large systems

# 2) System Interface Definition:
Interface = System ∩ Environment
A System interface can be thought of as a contract between the system and the environment. the 'environment' is the rest of the project. The interface formally describes what can pass between the system and the environment. An 'implementation' can be defined as the system minus the interface. The types of interfaces used can affect the amount of technical debt that is created (a mathematical formula is provided), and programmer productivity.

# 3) Back-of-the-envelope estimation:
How many servers would we need?
Back-of-the-envelope calculations are estimates you create using a combination of thought experiments and common performance numbers to get a good feel for which designs will meet your requirements.
if the architecture can fulfill the functional requirements, for example, the number of supported users, response latency,
the resource requirements.

# 4) Defining data model:
Data modeling (data modeling) is the process of creating a data model for the data to be stored in a database. This data model is a conceptual representation of Data objects, the associations between different data objects, and the rules.
Data Model is like an architect's building plan which helps to build a conceptual model and set the relationship between data items.
The two types of Data Models techniques are
Entity Relationship (E-R) Model
UML (Unified Modelling Language)

# 5) High-level design:
Design is not just what it looks like and feels like. Design is how it works.
The high-level design provides a view of the system at an abstract level. It shows how the major pieces of the finished application will fit together and interact with each other.
A high-level design should also specify assumptions about the environment in which the finished application will run. For example, it should describe the hardware and software you will use to develop the application and the hardware that will eventually run the program.

# 6) Component Design:
Abstraction and divides the problem into sub-problems
Component design is viewed as a set of one or more cooperating classes. Each problem domain interface (analysis) and infrastructure entity (design) are explained to identify all attributes and operations that apply to its implementation. It also involves defining the interfaces that enable classes to communicate and cooperate.
the development cost by reusing existing components.
Increased reliability with the reuse of the existing components.

# 7) Identifying and resolving bottlenecks:
Bottlenecks are setbacks or obstacles that slow or delay a process, knowing that you've got a bottleneck, however, it doesn't necessarily mean that you'll know where it is. You may not be aware of what goes on at each stage of a process, or you might be the bottleneck yourself!
There are two basic options for unblocking bottlenecks:
Increase the Efficiency of the Bottleneck Step: Assign your most skilled team members to the bottleneck. They'll likely be the most productive, too. Or find ways to add capacity in the bottleneck. As the saying goes, many hands make light work!
Decrease Input Into the Bottleneck Step: Decreasing input is an appropriate response if one part of a process has the potential to produce more output than you ultimately need. An alternative way to decrease input may be to reallocate tasks where there is more capacity.
