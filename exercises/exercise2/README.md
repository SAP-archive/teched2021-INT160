# Exercise 2 - RPA Challenge Automations

In this set of exercises, you will create the automations that will allow you to run the RPA challenge either successfully or with error.

## Exercise 2.1 First Automation

After completing this [exercise](2.1%20-%20First%20Automation.pdf) you will have created your first automation.

- Once the application is declared and the elements you want to work with have been recognized and declared, you can create your automation.
Automations are executed on the Desktop Agent of your local machine.  They are composed of a succession of steps you build in the Cloud Studio with the automation designer. An automation can orchestrate multiple activities on different applications and screens available on a specific computer.
- In this [exercise](2.1%20-%20First%20Automation.pdf), you will work on the first part of your automation. The bot you will create will open the [RPA Challenge website](http://www.rpachallenge.com), click on the Download Excel button and if the path entered in the bot (where the excel file should be downloaded) exists, will download it and store it on your computer.

## Exercise 2.2 Test Download Challenge

After completing this [exercise](2.2%20-%20Test%20Download%20Challenge.pdf) you will have tested the first part of your automation where you created a bot to download an excel file from the [RPA Challenge website](http://www.rpachallenge.com). This excel file is needed for the second part of the automation where you will use it with Excel Cloud Link activity.

- After completing the first automation, you will test it thanks to the tester side panel. This panel helps you test, troubleshoot but also display the execution flow of your automation.
- In this [exercise](2.2%20-%20Test%20Download%20Challenge.pdf), you will learn how to set breakpoints, debug your automation, check the input and output parameters. 
- This testing will allow you to ensure that the file exists and that the path to the file is given.

## Exercise 2.3 Fill Fields Automation

After completing this [exercise](2.3%20-%20Fill%20Fields%20Automation.pdf) you will have created a second automation that will be used in a loop as a sub-automation.

- In this [exercise](2.3%20-%20Fill%20Fields%20Automation.pdf), you will continue working on the automation. Now that you tested that the file exists and that the path to the file is given, you can direct the bot to open the excel file and read the information in the file.
- Next, you will create a new automation called Fill fields that you will use as a sub-automation inside the Run RPA Challenge automation. 
- The Fill Fields automation will use the Main application. You will then define which activities should be performed on the screen such as fill the fields, click start, etc...
- You will then add the Results application. Similarly you will define the activities that should be performed on the screen such as get the result rate. The result will be then saved as a screenshot on your computer.

## Exercise 2.4 Run RPA Challenge with error and Project Pane

- In this [exercise](2.4%20-%20Run%20RPA%20Challenge%20with%20error%20and%20Project%20Pane.pdf) you will create a Run RPA Challenge automation that will have an error during runtime. You will use a wrong file path to trigger an error.
- You will then create a Project Pane that will hold two attended automations:
    - Run RPA Challenge
    - Run RPA Challenge with error
- A Project Pane allows you to design the agent systray menu directly from the Cloud Studio letting you select the automation you want to launch.

## Summary

You've now completed exercise 2 with a Project Pane and all the automations needed to run the RPA Challenge in different situations: with and without error.
Get ready to experience the power of Cold debugging in the next exercise to understand the error raised during the first case with error.

Continue to - [Exercise 3 - Deployment & Cold debugging](../exercise3/README.md)
