# Limited Task Features Task Providers

## Links to issue
*[Github]()
* [Youtube overview link](https://www.youtube.com/watch?v=xkHk9nHiBaU)

## Expected Behavior
* the vscode.Task api should have the same or functionality than the tasks specified in tasks.json
* I should be able to run multiple tasks just like tasks.json where new tasks open up in a new window
* I should be able to have specified tasks run on folder open
* If I run a quick action tasks that quick action task should run



## Current Behavior
* vscode.Task api has limited functionality
* cant run multiple tasks that come from the same task definition
* cant automaticcally run tasks on folder open
* tasks from the extension in the task quick action menue seem to run the first registered task and not its own task



## Possible Solution




## Steps to Reproduce

1. cd target-extension
2. yarn install
3. start debugging
4. open the target-app folder
5. [Ctrl Shift P] -> [Run task] => [windmillcode] -> [yarn install app deps] -> run the commands to install in the Angular location
6. [Ctrl Shift P] -> [Run task] => [windmillcode] -> [python app deps] -> run task to install in the flask app location
see how it needs to be sync and nothing can run at the same time
also if you try to run the task from quick action it wont run for you


## Environment

### Vscode
1.79.2
695af097c7bd098fbf017ce3ac85e09bbc5dda06
x64

### OS
OS Name:                   Microsoft Windows 11 Pro
OS Version:                10.0.22621 N/A Build 22621
OS Manufacturer:           Microsoft Corporation
OS Configuration:          Standalone Workstation
OS Build Type:             Multiprocessor Free
System Type:               x64-based PC

## Files


## Detailed Description

## Possible Implementation


## Additional Issues
