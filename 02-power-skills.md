# 02 - Power Skills

## Process Management

# See all running processes with full details
ps aux

# Filter processes by specific name
ps aux | grep chrome

# See only your own processes
ps -u $USER

# Live process monitor (press q to quit)
top

# Start a process in background
sleep 100 &

# Find PID of background process
ps aux | grep sleep
# NOTE: ignore the grep line itself
# your target is the other line

# Kill process politely
kill <PID>

# Force kill — no mercy
kill -9 <PID>

# Kill all processes by name
killall sleep

# See process tree (Linux/EC2 only)
ps aux --forest

## Key Concepts
# PID = Process ID — unique number for every process
# Every process has a USER, PID, %CPU, %MEM, COMMAND
# kill = polite request to stop
# kill -9 = forced termination, no questions asked
# & = runs process in background
# pipeline | = output of left becomes input of right
