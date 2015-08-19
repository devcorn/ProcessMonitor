# ProcessMonitor

A python script for monitoring a specified process. If the process hangs the tools responsibility is to try to confirm that its hanging and kill it if necessary.

A usefull autokill script for regularly hanging programs.

# Usage

python process_monitor.py [OPTIONS]

Options:
  --version             			show program's version number and exit
  -h, --help            			show this help message and exit
  -n IMAGENAME, --name=IMAGENAME    target application to monitor
  -l, --log             			enable logging