# Swift-basic-Egg-Timer-App
Simple Swift Egg timer app will show progress animation depending how you prefer your egg with UIProgressView bar animation.

_*App demo Egg Timer App!_

![Simulator Screen Recording - iPhone 11 - 2023-05-07 at 16 24 32](https://user-images.githubusercontent.com/60531747/236671998-569e5e28-8efb-4df7-8860-f9658a8cb7b4.gif)

## Development Step by Step
- Create IBOutlet to linking the UILabel and **UIProgressView** in the Main.storyboard file to ViewController file.
- Create Constant named eggTimes who contain **Dictionaries** to store key & value pair depend on hardness level in each Egg.
- Create IBAction called hardnessSelected and link it with Soft, Medium, & Hard egg Button.
- Inside IBAction use Timer func and get the value hardnessSelected using sender.currentTitle! using **Unwrapping**
- Set the default progressBar value to 0.0
- Create objc func named updateCounter() who contain **IF ELSE conditionals** and Calculate Formula to update the Progress time and if the time was complete the label will change to become “DONE” using ELSE condition.

## What have I Learned
- **Swift IF/ELSE conditionals statements.**
- **Swift Switch conditionals statements.**
- **Swift Dictionaries.**
- **Swift Optionals & Unwrapping.**
- **Create UIProgressView to keep track of  the time.**
- **How to debug App.**

>This is a project From iOS & Swift - The Complete iOS App Development Bootcamp by Dr. Angela Yu, check out the full course at https://www.udemy.com/course/ios-13-app-development-bootcamp/
