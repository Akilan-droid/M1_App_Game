# Report 
# Requirements
## Introduction
   I developed a Restaurant Billing System using C Programming Language. This program allowed the user to choose a dish from the menu and during checkout the bill along with GST was calculated and displayed. Use Codeblocks to run the code.
## Objective
   The main objective of the project is to let the customer to order the food online and pay for it along with GST .
## Features
   The project has the following feature
   
    1. Increased Bandwidth
    2. No of orders in different outlets
    3. Offline Data Storage
    4. GST support 
    5. Increased CRM
   
 # FooooD
    
  ## Then
  ![Then](https://user-images.githubusercontent.com/85438544/143285352-afbfe102-f585-4135-a387-a478476c81a7.jpeg)

  ## Now
  ![image](https://user-images.githubusercontent.com/85438544/143285230-393fb1bd-e8fa-4d94-8ebb-746cd8f33aa8.png)




 # 4W'S and 1H's
  ## Why:
      - To reduce the complexity of Multiple order Billing in Restaurants.
      - I made this to receive multiple orders and payments from many customers by sitting in one place.
      - This Project is to reduce complexity of Restaurant workers.
  ## Where:
      - This can be used by many reputed large Restaurants to reduce their business complexity.
      - This can also be used in small scale Restaurants to kickup their Business.
  ## Who:
      - The project can used by any business organisation which serves the Restaurants with Solutions.
      - It connects customers and Consumers Digitally.
  ## When:
      - The user can access it anytime , anywhere.
      - Used when complexity can't be solved.
  ## How: 
      - By giving different orders , one can find desired total amount.
      - Customers can choose their items & amount of items .
 # SWOT Analysis
  ## Strengths
      - Performs Billing calcualtions Easily.
      - It can be updated as per the Goverment GST Norms.
 ## Weakness
      - It's can't be accessed while the updation happening.
 ## Opportunities
      - It can be updated as per the needs of Restaurants.
      - Startups and small scale restaurants can be attracted cause of efficient.
 ## Threats
     - Advanced softwares are available in the market.
     - Customer cannot go back to change their priority of choosed items.
 # High Level Requirements
 
   | ID   |      Description     |  Status |
|----------|:-------------:|------:|
| HLR_1 |  Customer can choose their meal | Implemented  |
| HLR_2 |  The discount will be given if applicable  | Implemented  |
| HLR_3 |   Customer can add more items after choosing items   | Implemented  |
| HLR_4 |   GST updation happening gradually  | Implemented  |

 # Low Level Requirements
 
 
  | ID   |      Description     |  Status |
|----------|:-------------:|------:|
| LLR_1 |  List of meals and items displayed | Implemented  |
| LLR_2 |  Customer can choose their items | Implemented  |
| LLR_3 |  Input from the user  | Implemented  |
| LLR_4 |  Exit the program  | Implemented  |

# Behavioral diagrams
   ![BEHAVIOUR STRUCTURE (1)](https://user-images.githubusercontent.com/85438544/142774503-9ffae601-b12a-4f07-9668-9308c3425d40.jpg)
   
# Structural Diagrams 
  ![STRUCTURE DIAGRAM](https://user-images.githubusercontent.com/85438544/142774936-3717520a-d086-4f72-8004-d5fbe12ed31f.jpg)

    


# Folder Structure
| Folder | Description |
| ---- | ---- |
| 1_Requirements | Documents detailing requirements and research |
| 2_Design | Documents specifying design |
| 3_Implementation | All codes and Documentation |
| 4_Testplan | Documents with test plans |
| 5_Imagesandvideos | All the images of this project |
| 6_Report | Documentation of whole project |
| 7_Others | Other Details |
  
  # Test Plan

# High Level Test Plan
| ID | Description | Expected I/P | Expected O/P | Actual O/P | Type Of Test |
|---|---|---|---|---|---|
| HLTP_1 | BreakFast Calculation | Choice | SUCCESS | SUCCESS | Requirement Based |
| HLTP_2 | Lunch Calculation | Choice | SUCCESS | SUCCESS | Requirement Based |
| HLTP_3 | Dinner Calculation | Choice | SUCCESS | SUCCESS | Requirement Based |


# Low Level Test Plan
| ID | Description | Expected I/P | Expected O/P | Actual O/P | Type Of Test |
|---|---|---|---|---|---|
| LLTP_1 | BreakFast Calculation | ( A,3,2,2 ) | Rs.40 | Rs.40 | Requirement Based |
| LLTP_2 | Lunch Calculation | ( B,3,2,1,5,2,2 ) | Rs.560 | Rs.560 | Requirement Based |
| LLTP_3 | Dinner Calculation | ( C,2,2,2 ) | Rs.140 | Rs.140 | Requirement Based |
| LLTP_4 | Invalid Entries | (G) | "Sorry Invalid Decision Entered, Enter again" | "Sorry Invalid Decision Entered, Enter again"| Requirement Based |
| LLTP_5 | Invalid Entries | (A,9) | "Sorry Invalid Decision Entered, Enter again" | "Sorry Invalid Decision Entered, Enter again"| Requirement Based |
     
  

