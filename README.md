# CS-230-Operating-Platforms
Computer Science portfolio for CS 230 Operating Platforms at Southern New Hampshire University.
# CS 230 – Software Design Document

## Project Reflection

**1. Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?**

The client for this project was The Gaming Room, a company that developed a game called *Draw It or Lose It*. They originally had the game available on Android but wanted to expand it so people could play on different platforms. The game involves teams competing to guess images within a certain amount of time. The client needed a system that could support multiple teams and players while making sure each game, team, and player had a unique identifier. They also wanted the application to be reliable, secure, and accessible across different devices.

**2. What did you do particularly well in developing this documentation?**

I think one thing I did well was comparing the different operating platforms and explaining which option would work best for the client. I was able to look at Windows, Linux, macOS, and mobile platforms and consider their advantages and disadvantages. I also think I did a good job explaining why a Linux-based server would be a good choice for the application. This helped me understand how important it is to consider performance, security, and cost when designing software.

**3. What about the process of working through a design document did you find helpful when developing the code?**

Working through the design document helped me understand the importance of planning before starting to write code. Having the requirements and design laid out made it easier to understand how the different parts of the application should work together. The UML diagram was especially helpful because it showed the relationships between classes like Game, Team, and Player. It also helped me understand how design patterns, such as the Singleton pattern, could be used to manage the application more efficiently.

**4. If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?**

If I could go back and improve one part of my design document, I would focus more on the security requirements. While I included security in my recommendations, I think I could have gone into more detail about protecting user information and preventing unauthorized access. I would also include more information about authentication, encryption, and how the application would handle potential security threats. Since security is important for online applications, I think this would make the overall design stronger.

**5. How did you interpret the user's needs and implement them into your software design? Why is it so important to consider the user's needs when designing?**

I interpreted the client's needs by looking at what they wanted the application to accomplish and turning those requirements into design decisions. For example, because they wanted the game to work across multiple platforms, I recommended a web-based application that users could access through a browser. I also considered their need to support multiple players and teams by including a design that could manage games and prevent duplicate names. I think considering the user's needs is important because even if an application works correctly, it won't be successful if it doesn't do what the client actually needs.

**6. How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?**

My approach to designing the software was to start by understanding the requirements and then break the application down into smaller parts. I looked at the different platforms, considered the technical requirements, and used the UML diagram to understand how the classes would interact. In the future, I would continue using design documents and UML diagrams because they help organize the project before coding begins. I would also spend more time reviewing security, scalability, and testing requirements early in the process. Overall, this project helped me understand that good software development involves more than just writing code. It also requires planning, communication, and making decisions based on the client's needs.
