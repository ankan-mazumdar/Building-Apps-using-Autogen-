## A Beginner's Guide to AutoGen: My First Project

Hey everyone! I'm excited to share my first AutoGen project with you. AutoGen is a powerful framework that allows you to create and manage multiple AI agents to collaborate on complex tasks.

**What is AutoGen?**

Think of it like a virtual team of AI assistants. You can assign specific tasks to each agent, and they'll work together to complete the job. In my project, I created two agents:

1. **The Snake Game Agent:** This agent was responsible for generating and managing the code for a simple Snake game.
2. **The Stock Analysis Agent:** This agent fetched stock price data and provided analysis and visualizations.

**How Did I Implement It?**

I started by defining the roles and responsibilities for each agent. Then, I created a workflow to outline the steps involved in completing the task. Finally, I used AutoGen's tools to connect the agents and ensure they communicated effectively.

**Why Choose AutoGen?**

AutoGen is a great choice for beginners because it provides a structured environment for building AI applications. It's also highly flexible, allowing you to customize it to fit your specific needs.

**What's Next?**

This is just a simple prototype to demonstrate the concept of AutoGen. I'm excited to explore more complex applications and learn even more about this powerful framework.

I hope this gives you a better understanding of AutoGen. Feel free to ask any questions you may have!



![image](https://github.com/user-attachments/assets/b6b051f0-96e9-4d51-9a06-90cee89fee3f)


![image](https://github.com/user-attachments/assets/df89b28e-808e-4176-9dd6-781fc1a18d82)


![image](https://github.com/user-attachments/assets/096ad166-78d4-4eea-a21b-b18889f36228)


### Stock Price Analysis Tool Implementation

* **Agent Roles:** We defined two primary agents:
    * **DataFetcherAgent:** Responsible for retrieving historical stock price data.
    * **AnalysisAgent:** Analyzes the data and provides insights.
* **Task Flow:**
    1. **Data Fetching:** The DataFetcherAgent retrieves stock price data from a specified source.
    2. **Data Analysis:** The AnalysisAgent performs various analyses on the data, such as calculating averages, trends, and correlations.
    3. **Visualization:** The AnalysisAgent generates visualizations to present the findings.
    4. **User Interaction:** The UserProxyAgent allows the user to interact with the visualizations and request additional analyses.

**Key Benefits of Using AutoGen:**

* **Flexibility:** AutoGen's modular architecture allows for easy customization and adaptation to different use cases.
* **Efficiency:** By automating repetitive tasks, AutoGen can significantly improve efficiency and productivity.
* **Collaboration:** AutoGen enables seamless collaboration between multiple agents, leading to better problem-solving and decision-making.
* **Scalability:** AutoGen can handle complex tasks and large-scale applications.


![image](https://github.com/user-attachments/assets/78f5ec87-58fd-4ab5-8d16-f490e97dafab)


![image](https://github.com/user-attachments/assets/dbd4c52c-27be-4828-a58a-d4a3e4e41c15)


![image](https://github.com/user-attachments/assets/de9957f1-027f-40df-9e48-249a470aed4f)


![image](https://github.com/user-attachments/assets/4adb47f9-9e3d-4134-aea9-4d090b9105f1)


![image](https://github.com/user-attachments/assets/6a7199ab-9a81-49ea-adf3-7a1c98402b7b)


![image](https://github.com/user-attachments/assets/01975de1-bb18-4dda-9ba8-0e238a5b460b)


![image](https://github.com/user-attachments/assets/17d7275f-f027-486a-9f80-d32b28eaf864)




### Snake Game Implementation

* **Agent Roles:** We defined three primary agents:
    * **UserProxyAgent:** Represents the human player, providing input and receiving feedback.
    * **CoderAgent:** Responsible for generating and modifying the game's code.
    * **GameManagerAgent:** Oversees the game's progress, ensuring rules are followed and the game runs smoothly.
* **Task Flow:**
    1. **Initialization:** The UserProxyAgent initiates the game, providing the initial game parameters.
    2. **Code Generation:** The CoderAgent generates the initial game code based on the provided parameters.
    3. **Game Loop:** The GameManagerAgent controls the game loop, updating the game state and providing feedback to the CoderAgent.
    4. **Code Modification:** The CoderAgent modifies the game code based on feedback from the GameManagerAgent and the UserProxyAgent.
    5. **Game Progression:** The game continues until the player loses or wins.
* **Human Interaction:** The UserProxyAgent allows the player to control the snake's movement using keyboard input.


![image](https://github.com/user-attachments/assets/e4563984-7f8e-4e18-8dbf-ef7f42ccd4e7)


![image](https://github.com/user-attachments/assets/e8d1f15f-e791-4fd0-ad17-b3e15a40849b)


![image](https://github.com/user-attachments/assets/a705f9cb-5495-42d8-9436-822e48f9fc08)



![image](https://github.com/user-attachments/assets/9cc0eb6f-ebf9-4483-9915-2594d6e63528)
