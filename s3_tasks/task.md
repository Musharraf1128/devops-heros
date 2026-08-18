# task.sh

## Code

```bash
#!/bin/sh

echo "Date: $(date)"
echo "Hostname: $(hostname) and Username: $(whoami)"

echo "Current running processes: $(ps)"
ps > process.log

echo "Name: Musharaf, Roll No: 10447, Comment: No comment"
```

## Output

```
Date: Tue Aug 18 06:03:14 PM IST 2026
Hostname: razor and Username: razor
Current running processes:    PID TTY          TIME CMD
 278902 pts/0    00:00:00 zsh
 287681 pts/0    00:00:00 task.sh
 287685 pts/0    00:00:00 ps
Name: Musharaf, Roll No: 10447, Comment: No comment
```

## Screenshot

![task.sh output](./screenshots/task.png)
