# CS230
CS230 Portfolio Submission

# Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design? 

The Gaming Room is a company focused on expanding their game "Draw It or Lose It" from its current Android platform to a web-based platform that can be accessed across various devices, including desktop and mobile. The software they need must support features such as multi-team gameplay, unique identifiers for games, teams, and players, and the ability to maintain a single active instance of the game in memory. Additionally, the system should be scalable to handle high user loads, compatible across different operating systems, and secure to protect user data, all while providing a seamless, low-latency gaming experience.

# What did you do particularly well in developing this documentation?

The documentation effectively addressed The Gaming Room's requirements by clearly outlining the software's features and constraints, such as multi-team support, cross-platform compatibility, and security measures. It also provided detailed technical recommendations for system architecture, including server choice, storage management, memory optimization, and distributed systems, ensuring a comprehensive approach to scalability and performance. The use of UML diagrams helped clarify the relationships between components, while the evaluation of different operating platforms offered practical insights into deployment options. Overall, the documentation presented a well-rounded solution, aligning technical strategies with the client’s needs.

# What about the process of working through a design document did you find helpful when developing the code?

Working through a design document was helpful in organizing the development process and setting a clear roadmap for coding. It provided a structured way to break down complex requirements into manageable components, ensuring that all aspects of the system—from game logic to security—were considered before coding began. The document's detailed analysis of system architecture, constraints, and platform evaluations helped identify potential challenges early on, guiding design choices and technology selections. Additionally, having a clear outline of features and their relationships made it easier to develop modular, maintainable code that adhered to the specified requirements.

# If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?

If I could revise one part of the documentation, it would be the "System Architecture View" section. While it provides some general guidance, I would improve it by adding more detailed diagrams and descriptions of the system's physical and logical architecture. This would include specifying how different components—like the server, database, and client-side interfaces—interact in a multi-tier environment, as well as outlining network communication flows and data storage strategies. A more comprehensive architectural breakdown would give a clearer picture of the system's structure, making it easier for developers to understand the design and implementation process.

# How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?

I interpreted the user’s needs by focusing on their key requirements: multi-team support, unique identifiers, cross-platform accessibility, and scalability for a real-time gaming experience. These needs were translated into specific software design elements, such as implementing a Game Management System to handle teams and players, using a Singleton pattern to manage a single game instance, and recommending a Linux-based server for scalability and cost-effectiveness. Considering user needs is crucial because it ensures the software addresses real-world problems and delivers value. It guides the design towards features that enhance user experience, performance, and security, resulting in a solution that effectively meets client expectations.

# How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?

I approached designing the software by first thoroughly analyzing the user requirements and translating them into functional specifications, such as multi-team support, cross-platform compatibility, and security measures. I then applied object-oriented design principles to structure the system, using UML diagrams to model relationships and interactions among game components like Game, Team, and Player. The Singleton pattern was utilized to meet the requirement of a single active game instance.

In the future, I would continue using strategies like requirement analysis and UML modeling but also incorporate more iterative design techniques, such as Agile practices, to allow for continuous feedback and refinement. Additionally, leveraging design patterns more extensively for modularity and scalability, conducting risk analysis to preemptively identify potential issues, and prototyping key components early on to validate assumptions would be beneficial in the design process.
