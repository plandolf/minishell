# Minishell

## Introduction

Minishell is a group project designed to replicate some of the basic functionalities of a Unix shell, specifically Bash. This project helps understand more about processes, file descriptors, and how a shell interprets and executes commands.

## Features

- **Command Execution**: Executes commands just like a typical Unix shell using PATH variable or by specifying relative/absolute paths.
- **Built-in Commands**: Includes built-in commands like `echo`, `cd`, `pwd`, `export`, `unset`, `env`, and `exit`.
- **Signal Handling**: Handles signals like `ctrl-C`, `ctrl-D`, and `ctrl-\` similar to Bash.
- **Redirection and Piping**: Supports input and output redirections (`>`, `<`, `>>`, `<<`) and piping between commands (`|`).
- **Environment Variables**: Manages environment variables and supports expansion.
- **Command History**: Maintains a history of commands that can be navigated through.
- **Error Handling**: Thorough error handling to prevent unexpected crashes.
- **Bonus Features**: As part of the bonus features, logical operators `&&` and `||` have been implemented to control command execution based on the success or failure of previous commands.

## Getting Started

### Prerequisites

- A C compiler (GCC recommended)
- GNU Make
- Readline library

### Installation

1) git clone [repository-url] minishell
2) cd minishell
3) make all


## Usage

Start the shell by running:
./minishell
