![软件图标](https://foruda.gitee.com/images/1751104375576115618/0a2c3c96_12357965.jpeg)

# Reward Yourself

**Software Name:** Reward Yourself

**Slogan:** When you're tired from working hard, don't forget to reward yourself properly.

## Introduction

Do you often feel that after working or studying hard, you forget to give yourself the rewards you deserve? *Reward Yourself*  is an app designed for hardworking individuals, encouraging users to appropriately reward themselves after achieving set goals, so as to maintain motivation and happiness.

## Core Functions

- **Effort Table:** Users can list their tasks or goals, such as completing a project, finishing a book, or sticking to a fitness routine for a month. Each time a task is completed, users can record it in this table and earn corresponding points. These points represent your efforts and achievements.
- **Reward Table:** Once enough points are accumulated, users can choose to redeem pre-set rewards in this table. All rewards are defined by the users themselves, which can be a short trip, a delicious meal, a leisurely afternoon tea, etc. The platform does not directly provide material rewards but encourages users to fulfill these little joys by themselves.
- **Point System:** Earning points is not easy and requires users to truly put in effort and time to complete tasks. This setting ensures the value of rewards, preventing them from becoming too easily obtainable and losing their motivational significance.
- **Personalized Settings:** Users can set the difficulty of rewards according to their own situations. For example, if the reward is allowing themselves 20 minutes of gaming time, they should usually stick to staying off the internet to ensure that this reward is attractive enough to themselves.

## Priority Calculation Rules  

To help users better manage tasks, the application introduces the concept of task priority. The priority of each task is comprehensively calculated based on the following factors:  


### Importance  
Users can select the importance of a task on a scale from 0 to 5, where:  
- 0 indicates "Not Important"  
- 3 indicates "Important"  
- 4 indicates "Very Important"  
- 5 indicates "Extremely Important" (corresponding to infinity), recommended for non-negotiable tasks (such as going to work or school)  


### Urgency  
Users can select the urgency level of a task on a scale from 1 to 3, where:  
- 1 indicates "Not Urgent"  
- 2 indicates "Moderately Urgent"  
- 3 indicates "Urgent"  


### Value  
Users can select the value of a task on a scale from 1 to 3, where:  
- 1 indicates "Low Value"  
- 2 indicates "Medium Value"  
- 3 indicates "High Value"  


### Time  
Users need to input the time required to complete the task, in minutes.  


### The priority calculation formula is as follows:  
**Priority = Importance × 4 + Urgency × 2 + Value × 3 − Time ÷ 10**  

Specifically, if a task is marked as "Extremely Important," its priority is infinity (i.e., the highest priority).  

This approach allows users to more intuitively understand which tasks deserve top priority, thereby enhancing work efficiency and quality of life.

## Operation

1. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
2. Initialize the database:

   ```bash
   python init.py
   ```
3. Run the app:

   ```bash
   # For local development environment only
   python app.py
   ```
   **If you are running it for the first time, the program will automatically end after creating the data file. Just start it again.**
4. Access the app: Enter `localhost:8080` in your browser (if using local development server)

Through this app, we hope users can realize that while working or studying hard, they should not ignore caring for and rewarding themselves. Remember, appropriate rest and rewards can make you go further. Download "Reward Yourself" now and start your rewarding journey!

## Special Thanks

- [Hitokoto Service](https://hitokoto.cn/) for providing quote support

- The icons and background images of this work are ["Open Book on Selective Focus Photography on a White Surface"](https://www.pexels.com/zh-cn/photo/46274/).Thanks to the websites that provide copyright-free image materials: [pixabay](https://pixabay.com/) and the photographer [Caio](https://www.pexels.com/)