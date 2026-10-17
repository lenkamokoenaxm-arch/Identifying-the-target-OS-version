# Identifying-the-target-OS-version
A Blue Team investigation documenting the process of identifying a targeted operating system version by examining system logs and analyzing command-line output. Includes investigation steps, commands, findings, and supporting screenshots.

## Objective
Identify the version of the operating system targeted during the investigation.

## Investigation

I examined the `dmesg` logs because they contain kernel and system messages, including information recorded during system startup. To inspect the beginning of the log output, I used the `head` command.

### Command Used

```bash
head dmesg
```

**Screenshot 1: Command Execution & Output**

This screenshot shows the command used during the investigation.

![Command Execution]()

## Findings

The command was used to inspect the beginning of the available `dmesg` file. The output must be reviewed to determine whether it contains evidence identifying the targeted operating system version.

## Conclusion

The investigation involved examining system-related messages to look for information that could help identify the targeted operating system. The final version should be recorded based on the evidence obtained.
