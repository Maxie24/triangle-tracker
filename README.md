# Triangle Tracker
#### This is a project of triangle tracker website, 10th August 2018
#### By **Maryann Gitonga**
## Description
This project is a triangle tracker that prompts the user to input three dimensions of their choice and the website decides on what type of a triangle it is by going through logical conditions in its js file and alerting the using of what type of triangle it is.
## Setup/Installation Requirements
To start using this project use the following commands:

* `git clone https://github.com/MaryannGitonga/triangle-tracker.git`
* `cd triangle-tracker`
* `atom .`
* `code . `(this is if Visual Studio Code is your preferred text editor)
##Behavior Driven Development
* The program should return this when the input is not a number:
**Input Example**: a
**Output Example**: Please enter a valid dimension

* The program should return this when the input is a negative value:
**Input Example**: -1
**Output Example**: Please enter a valid dimension

* The program should return this when the sum of any two sides is less than or equal to the third side:
**Input Example**: first side = 1, second side = 1, third side = 3
**Output Example**: It's not a triangle

* The program should return this when all sides are equal:
**Input Example**: first side = 4, second side = 4, third side = 4
**Output Example**: It's an equilateral triangle

* The program should return this when at most two sides are equal:
**Input Example**: first side = 4, second side = 4, third side = 5
**Output Example**: It's an isosceles triangle

* The program should return this when all sides are not equal:
**Input Example**: first side = 4, second side = 5, third side = 6
**Output Example**: It's an scalene triangle

## Link to Live Website
http://maryanngitonga.github.io/triangle-tracker
### License
MIT License

Copyright (c) 2018 Moringa School

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
