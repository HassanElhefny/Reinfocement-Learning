# Reinforcement Q-Learning from Scratch in Python with OpenAI Gym
## We will devide this file into Five parts:                                                                                           
  ### 1- Custom q-learning to update the values of the table                                                                                               
  ### 2- SARSA q-learning to update the values in the table                                                                                                         
  ### 3- How to make our model greedy to rewards                                                                                                                        
  ### 4- Using grid-search to choose the best values for alpha, gamma                                                                                       
  ### 5- Using Deep Q-Learning                                                                                                                                  
# lets start with the code parts:        
  # We install gym library and import important libraries like numpy, pandas, ....                                                                    
  ![image](https://user-images.githubusercontent.com/58745859/172071777-6e161689-593f-4788-a4fe-d2d4b37f0db4.png)    
  # These two function using with SARSA algorithm to fill the Q-table
  ![image](https://user-images.githubusercontent.com/58745859/172071826-7037cd1d-a5ea-4327-8d50-e25603fb13f2.png)   
  # SARSA algorithm that update the Q-table
  ![image](https://user-images.githubusercontent.com/58745859/172071904-fb082d2b-1df9-4de5-b34f-87e27d550ac0.png)   
  # This function will make our agent greedy to rewards so it will perefer gain rewards than minimize penalities so this may make our agent as example of taxi-v3 know    one road and didn't want to discover new roads.
  ![image](https://user-images.githubusercontent.com/58745859/172071954-a822bb7e-c7fb-43b5-8a3c-9d643d01ae08.png)                                            
  ![image](https://user-images.githubusercontent.com/58745859/172072041-da11b7cc-4357-4b11-b9b3-638421bd7517.png)                                                   
  # this function will build the table using custom equation of Q-table depend on Q-Learning
  ![image](https://user-images.githubusercontent.com/58745859/172072107-89050210-113a-4585-8ae4-b7f4404b5e76.png)                                               
  # this the equation it use: 
  ![image](https://user-images.githubusercontent.com/58745859/172072142-07ba7d5d-ff19-4da8-9a40-b67dd3f16bfd.png)
  # this is the table looks like:
  ![image](https://user-images.githubusercontent.com/58745859/172072163-d7011f4f-a687-422b-baaf-4a01b25ae8e4.png)
  # Function to evaluate the agent
  ![image](https://user-images.githubusercontent.com/58745859/172072215-25c3e929-2846-4a53-b92c-5dd21da2281c.png)
  # Grid search [i put some values to alpha and gamma to choose the best one of them and return the best one] .. you can add some values but it will take some time to train the agent.
  ![image](https://user-images.githubusercontent.com/58745859/172072308-6ba52d71-4021-434b-bd7a-0dd546da2ad0.png)
  # Choose the environment you want and initialize the values on the table with zeros
  ![image](https://user-images.githubusercontent.com/58745859/172072380-e6e68fb9-ddb2-4009-a715-118033212d52.png)
  # Starting with SARSA and calculate the reward
  ![image](https://user-images.githubusercontent.com/58745859/172072400-deadb1ec-467e-497c-b2b6-f7fae7b17f00.png)
  # Using Greedy algorithm to update Q-table
  ![image](https://user-images.githubusercontent.com/58745859/172072444-36eabcde-dc16-40ff-908e-4a5a22fd150c.png)
  # Using grid-search to find the best value for alpha, gamma and return the results depending on the minimum penalities and average time
  ![image](https://user-images.githubusercontent.com/58745859/172072473-598f812d-111d-4784-9253-1f4ae07cb9ac.png)
  # Evaluating the model
  ![image](https://user-images.githubusercontent.com/58745859/172072497-73502c2c-9a14-40ae-87f6-4ac7c6396e20.png)
  # Tune alpha, gamma using a decay over episodes
  ![image](https://user-images.githubusercontent.com/58745859/172072529-9b741da0-ab35-4138-8300-d246b4b8e970.png)
  ![image](https://user-images.githubusercontent.com/58745859/172072543-9c2cdb1b-0a07-4bdc-8f26-59c0f8c1a854.png)
  # Deep Q-Learning
  ![image](https://user-images.githubusercontent.com/58745859/172072555-8d6ceb37-bd32-4a60-948a-92310ffe679d.png)
  ![image](https://user-images.githubusercontent.com/58745859/172072568-6ebcd51f-5c53-47e8-9e46-71a5280716f3.png)
  # All hyperparameters i use in q-learning
  ![image](https://user-images.githubusercontent.com/58745859/172072631-062ab239-8503-45cc-a52a-817180689556.png)










 
  
