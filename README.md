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

This screenshot shows the command used during the investigation with the output.

![Command Execution & OUtput](https://github.com/lenkamokoenaxm-arch/Identifying-the-target-OS-version/blob/1656c5d67863b10fbbaf20b06f0f38d1e8c3b6b9/Screenshots/OS%20%20Version-Target%20(and%20the%20command).png)

## Findings

After investigating the dmesg file, I successfully identified the version of the target operating system from the information contained in the log output.

## Conclusion

The investigation involved examining system-related messages to look for information that could help identify the targeted operating system. The final version should be recorded based on the evidence obtained.
