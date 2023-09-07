## Lab Zero: Decide upon Dish

### Background

This exercise is to make yourself familiar with the Camunda Modeler.
Draw the DRD and the implement the Decision table as described below.

### Instructions

1. Connect to the [Camunda Modeler](https://camunda.io)

2. Create a new folder (if you haven't one already)

<img src="createFolder.png" width="50%"/>

3. Click on the `New` button to create a `DMN Diagram`
4. Draw this Decision Requirement Diagram

<img src="simpleDishDrd.png" width="50%"/>

5. Select the Decision Table and give it a name and the following ID: "dishDecision"

<img src="renameDecisionTable.png" width="80%"/>

6.  Click the Icon in the Dish Decision and select Decision Table. This should switch the DMN Table implementation
7.  Add the inputs (by double clicking the header) as shown in the example below:

    a. Season (input expression =”season”, type= “string”)

    ![](seasonConfig.png)

    b. Vegetarian Option (input expression =”vegetarian”, type =”Boolean”)

8.  Enter the Output “Dish” (Output Expression =”dish”, type =”string”)

    <img src="renameDecisionTable.png" width="80%"/>

9.  Add some rules

10. Ensure Hit Policy is “U” (“Unique”)

### Test it

I know you're looking forward to test your decision, in the next Demo we'll see how to do it.

### Bonus

You can predefine the values for the Season on the input column. This simplifies adding new rules, avoids typos and creates an input dictionary.
