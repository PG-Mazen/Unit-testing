# Unit-testing
This project use LLM API and Langchain to make unit testing

.env file should be put in the same folder as the code

At first, the program asks to choose whether you want to generate a unit test or exit

  type 1 -> for generating
  
  type 2 -> for exiting
  
For generating you enter the file path and the output will be in the same place as the input file and its name is unit_test.py

If the code has zero or more than one function, the unit test won't be produced and instead "Error: This tool only generates unit tests for functions." will be printed  because this is not a single file function (as mentioned in the task file)

In general, anything that drive "Error: This tool only generates unit tests for functions.", will be printed in the terminal and the unit_test.py won't be created.

If everything goes right, the unit_test.py will be created with a successful message printed in the terminal
