# test2

A small Java command-line application used to exercise the code review workflow.

## Run

Compile and run with a JDK:

```shell
javac Main.java
java Main [name] [repeat-count]
```

Both arguments are optional. The name defaults to `World`, and the repeat count
defaults to `5`. The repeat count must be an integer between 1 and 100.

Example:

```text
$ java Main Codex 3
Hello, Codex!
Count: 1/3
Count: 2/3
Count: 3/3
```
