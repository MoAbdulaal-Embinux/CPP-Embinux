
# Prepare Machine for C++ development

## Install Visual Studio Code on Ubuntu

First update the package list:

`sudo apt update`

Then, just run the following commands in the terminal:

`sudo apt install snapd`

`sudo snap install --classic code`

## Install GCC/G++

Install the build-esstial this wil install the required toolchain:
`sudo apt install build-essential`

## Verify C++
Now on the terminal you can write `g++ --version`

## Configuring C++
Now Open VS Code and go to Extensions tab (the bottom-most tab on the left side panel) 
Install the following Extensions
* C/C++ By Microsoft
* C/C++ Compile Run
* Code Runner

## Cofiguring Code Runner
Go to Files->Preferences->Setting
Search for code.runner: Run in terminal
And Select the box, This will enable you to run your code and Display its output in the terminal and also provide inputs to it!

## Start your first C++ program
Create new file i.e. embinux.cpp
Write the following code to say "Hello Embinux"
```
#include<iostream>

using namespace std;

int main() {

cout<< "Hello Embinux \n";

}
```


