# Minishell

The existence of shells is linked to the very existence of IT. At the time, all coders agreed
that communicating with a computer using aligned 1/0 switches was seriously
irritating. It was only logical that they came up with the idea to communicate with
a computer using interactive lines of commands in a language somewhat close
to english.

## Compilation

`make`

## Build-in Features

- `echo` with option -n
- `cd` with only a relative or absolute path
- `pwd` with no options
- `export` with no options
- `unset` with no options
- `env` with no options or arguments
- `exit` with no options
- ’ inhibit all interpretation of a sequence of characters.
- " inhibit all interpretation of a sequence of characters except for $.
- < redirect input.
- > redirect output
- >> redirect output with append mode.
- Pipes | The output of each command in the pipeline is connected via a pipe to the
input of the next command.
- Environment variables ($ followed by characters) expand to their values
- $? expand to the exit status of the most recently executed foreground
pipeline.
-  ctrl-C ctrl-D ctrl-\ work like in bash.
- Historic of commands implemented with termcaps
- Search and launch the right executable (based on the PATH variable or by using
relative or absolute path)
