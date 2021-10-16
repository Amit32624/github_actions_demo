





## Implementation of continous integration pipeline with the help of Github Action


- The foundation of DevOps is continuous integration. Without automated testing, there is no way to move forward with DevOps.
- One of the most straightforward ways to implement continuous integration for the projects is with GitHub Action.

- In this example, I want to check a specific version of Python that runs on Azure. The continuous integration steps are trivial to implement Makefile:
  
  
- [Repo](https://github.com/Amit32624/github_actions_demo> "<github_actions_demo> Repo")


## Makefile
-  A Makefile runs “recipes” via the make system, which comes with Unix-based operating systems. Therefore, a Makefile is an ideal choice to simplify the steps involved in continuous integration.
- `Make install` - This step installs software via the make install command
- `Make int` - This step checks for any syntax eror with the make lint command
- `Make test` - This step runs test viis the make test command. 

 
## requirements.txt
- A requirements.txt file is used to install any dependencies with the help of 'pip' installation command.

## Source code and tests
- The final portion is to add a source code file and test a file hello.py
- The test file is created by using the pytest frameworl. The script should be in the same folder as the source code.
  
  
- These four files: Makefile, requirements.txt, hello.py, and test_hello.py are all that is needed to start the continuous integration pipeline except for creating a local Python virtual environment.
## 🤝 Support

  
Contributions, issues, and feature requests are welcome!

Give a ⭐️ if you like this project!
