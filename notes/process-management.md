# Process Management Notes

## Commands Used

### View Processes

```bash
ps aux
```

### Sort by CPU Usage

```bash
ps aux --sort=-%cpu
```

### Kill Process

```bash
kill -9 PID
```

### Kill by Name

```bash
pkill process_name
```

## Learning

Process management helps in:
- troubleshooting server issues
- stopping stuck processes
- reducing resource usage