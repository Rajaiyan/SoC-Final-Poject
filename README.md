# SoC Final Project


I have done a project for the system-on-chip course, where we examine step-by-step how to implement and achieve the final results.


Requirement: Installing Ubuntu

# First Section
Download all file in folder with name of First Section. A program is written in Python language for scheduling. This program has been tested and its function is correct.
Transfer the downloaded file to your virtual machine on which the Ubuntu operating system is installed. Enter the folder. Open a terminal and type the following command.

```sh
pip install -r requirements.txt
```

The above command causes all the necessary items to run the project, whose names are stored in a text file, to be installed in your system.


```sh
python ./design.py
```

The above command will execute the written program.


After running the program, the following figure should be displayed.
<div align="center">
  <img align="center" src="First Section/First Section.png" width="500px" />
  <figcaption><b><br>Figure 1: First Section.</b></figcaption>
</div>


An arbitrary scheduling has been implemented for 10 tasks, the result of which is shown in the image below.


After running the program, the following figure should be displayed.
<div align="center">
  <img align="center" src="First Section/10task.png" width="500px" />
  <figcaption><b><br>Figure 2: First Section.</b></figcaption>
</div>


# Second Section
Download all file in folder with name of Second Section. A program is written in Python language for Ant Colony Optimization (ACO). 

How to run it? Transfer the downloaded file to your virtual machine on which the Ubuntu operating system is installed. Enter the folder. Open a terminal and follow the follwing steps.

You should flow the four step below:

first: write the below comman in terminal.
```sh
source ACO_project/bin/activate
```

second: write the below comman in terminal.
```sh
source ACO_project/bin/activate
```

third: Use the experience you gained in the First Section to install the required modules.
```sh
pip install -r requirements.txt
```

Fourth: Run the main program.
```sh
python main.py
```

After running the program, the following figures should be displayed.
<div align="center">
  <img align="center" src="Second Section/results/ACO_cycles_results.png" width="500px" />
  <figcaption><b><br>Figure 3: Second Section.</b></figcaption>
</div>

<div align="center">
  <img align="center" src="Second Section/results/execution_gantt.png" width="500px" />
  <figcaption><b><br>Figure 4: Second Section.</b></figcaption>
</div>



# Third Section

In this section we should practice how to change other people's codes. To do this part of the project, try to change the Second Section program in such a way that the timing in Figure 3 changes.

To do this, you need to prepare text files for testing. These files have been prepared and are located in Third Section folder. What you need to do is download all the files in the Third Section, and then move them to the test_instances folder you downloaded in the second part of the project.

Finally, it is only necessary to change the line of the project (Main.py) that is highlighted in the image below and replace it with the name of one of the files that you placed in the test_instances folder. Now you just need to run the Main.py


<div align="center">
  <img align="center" src="Third Section/Figure_5.png" width="500px" />
  <figcaption><b><br>Figure 5: Third Section.</b></figcaption>
</div>


One of the possible changes is that the output of the program is changed from Figure 3 to Figure 4. Pay attention to the differences between these two Figures. You can also get your unique output.

<div align="center">
  <img align="center" src="Third Section/Figure_6.png" width="500px" />
  <figcaption><b><br>Figure 6: Third Section.</b></figcaption>
</div>


# Fourth Section

In this section i write a program in Python language that receives the number of tasks, task name, task arrival time and the time required to execute the task as input from the user and displays the scheduling of the tasks in the output using the First Come First Serve (FCFS) and Shortest Job First method (SJF). Be careful that the results should only be displayed in the Ubuntu terminal and  unlike the First Section, a user interface is not designed.




