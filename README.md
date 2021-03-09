# Inspire
​	An encouraging tool to light up your day.

​	Inspire takes the user's name and the rating of the day as two inputs. Then it will give the user different motivating messages.

## Installation

First, go to the green "Code" bar and copy the url of this repository.

Then, go to the JupyterLab and open a terminal. Direct to the destination folder that you want to install this program. Type in "git clone" and the url you just pasted to download the program to your folder.

## Usage

```python
# Takes the user's name as the first input
name = input("Please enter your name: ")
# Takes the user's rating of the day as the second input
number = input("Please rate your day, enter a number between 1-5: ")
# Convert the rating input to an integer
number = int(number)
# Displays different messages based on different rating levels
if number == 1:
    print(name + ", Everything is gonna be ok")
elif number == 2:
    print( name + ", Chin up and go")
elif number == 3:
    print( name + ", Success is waiting ahead")
elif number == 4:
    print( name + ", Great to hear! Keep up!")
elif number == 5:
    print( name + ", Have a nice day YAY")
```

## Contributing

To contribute, please fork this repository and edit on your end. Then, you can send a pull request, which we will see on our end and decide whether to add your edits to the project.

We welcome any suggestions!

## Group Members

Zhen Wu - [zhw87@pitt.edu](mailto:zhw87@pitt.edu)
Xingjian Zhang - [xiz201@pitt.edu](mailto:xiz201@pitt.edu)
Yuqing Zhang - yuz191@pitt.edu