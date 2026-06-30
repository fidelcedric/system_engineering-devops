# System Engineering & DevOps

A comprehensive collection of **Linux system administration and Bash scripting** exercises covering the fundamentals every DevOps engineer needs to master.

## Project Structure

| Directory | Topic | Key Skills |
|---|---|---|
| `0x00-shell_basics` | Shell navigation & file operations | `pwd`, `ls`, `cd`, directory traversal |
| `0x01-shell_permissions` | File permissions, users, groups | `chmod`, `chown`, `su`, `sudo` concepts |
| `0x02-shell_redirections` | I/O streams, pipes, filters | `>`, `>>`, `|`, `tee`, `/dev/null` |
| `0x03-shell_variables_expansions` | Variables, aliases, shell expansions | `$VAR`, `${}`, `alias`, `PATH` |
| `0x04-loops_conditions_and_parsing` | Control flow in Bash | `for`, `while`, `until`, `if`, `case` |
| `0x05-processes_and_signals` | Process management, signals, PIDs | `kill`, `trap`, `SIGTERM`, `SIGINT` |

## Highlights

- **Signal handling** — Scripts that demonstrate `trap` for graceful cleanup on interrupt
- **Process introspection** — PID discovery, parent-child relationship analysis
- **File permission matrix** — Comprehensive coverage of `chmod` numeric and symbolic modes
- **Shell expansion mastery** — Brace expansion, parameter expansion, command substitution

## Usage

```bash
git clone https://github.com/fidelcedric/system_engineering-devops.git
cd system_engineering-devops/0x05-processes_and_signals
./0-what-is-my-pid
```

All scripts are standalone Bash executables with proper shebangs.

## License

MIT
