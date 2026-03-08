```md
# minishell - 42 Firenze Project

## Overview

**minishell** recreates a simplified Unix shell in C, matching bash behavior for core commands. This project teaches process management, signal handling, and command parsing.

## Features

- Prompt display (`$ ` or `> ` for quotes)
- Command execution via `$PATH`
- Builtins: `echo`, `cd`, `pwd`, `export`, `unset`, `env`, `exit`
- Pipes (`|`)
- Redirections (`>`, `>>`, `<`, `<<`)
- Variable expansion (`$VAR`)
- History (`↑↓` arrows)
- Signals (Ctrl+C, Ctrl+D)

## Tech Stack

- **Language**: C
- **Libraries**: readline, libft
- **Key concepts**: fork/execve, pipes, signals, env vars

## How to Run

```bash
make
./minishell
