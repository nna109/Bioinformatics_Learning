# Module02 WSL + Visual Studio Code
## Why do I need to know this?

The cool part of Visual Studio Code (VS Code) is that it allows commands to be executed inside the Linux environment through WSL terminal, while provides a graphical interface for users. By integrating VS Code with Ubuntu, bioinformatics researchers can edit files, manage Git repositories, write Python code and run Linux-based bioinformatics tools efficiently within one single application.

The overall workflow is as below:

```
Windows
|
|__ Visual Studio Code (Editor)
|         |
|         |
|         V
|    WSL Extension 
|         |
|         |
|         V
|_______WSL 2
          |
          |
          V
        Ubuntu
            |_______ Bash (shell)
            |         |__ Linux commands
            |__ Git
            |__ Python     
            |__ Bioinformatics tools   
```

## Goal
- [ ] To understand the relationship between VS Code, WSL, Ubuntu, and bash.
- [ ] To be able to open VS Code directly from Ubuntu.
- [ ] To be able to use the integrated bash terminal.
- [ ] To understand the difference between editing files in Windows and Linux (Ubuntu).
- [ ] To learn why VS Code is preferred over Nano for large projetcs.

## What I can do after this module
- [ ] Explain how WSL allows Ubuntu to run inside Windows.
- [ ] Understand that VS Code is a code editor running on Windows.
- [ ] Run the bash terminal inside VS Code.
- [ ] Explain how VS Code communicates with Ubuntu through the WSL extension.
- [ ] Execute bioinformatics tools such as Git, Python, Conda from bash terminal inside VS Code for efficient bioinformatics analysis.

The journey was documented in the module02_journal.