# System-project


Assignment : simple implementation of a Unix shell

How to use

Every parts of a command must be separated by a space. The shell supports piped commands with an arbitrary amount of pipes and single redirections ('>'). Behavior is based on bash, the shell can access every usual Linux commands but some of them have been re-implemented as part of the asignment. The use of the arrow keys to run through the history have not been implemented, aswell as the auto-completion with TAB.

Re-implemented commands

-cat [OPTION] [FILE 1]...[FILE N] : available option : -n. When no file is specified, prints the user's inputs.

-touch [OPTION] [FILE 1]...[FILE N] : available option : -m.

-cp [FILE 1] [FILE 2] : no option available. Works recursively for directories.

-find : no option available.

-cd : standard behavior with '~', '/' and no argument.

-history [OPTION] : available option : n (prints the n last lines of history), !n (execute the nth line of history).

-!! : execute the last command.

-exit
