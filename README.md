# Linux-Fundamentals-Part-3

— — — — — — — — — — — — — — — — — — — — — — — — — — — — — — — —

— — — — — — — — — — — — — — — — — — — — — — — — — — — — — — — —

Terminal Text Editors: Vim, Nano are commonly used
Download file: curl, wget are commonly used

python3 -m  http.server -used to start a simple HTTP server on your local machine


process
ps	Displays a list of running processes.

ps aux	Displays a list of running processes, including additional information such as the user ID, CPU usage, memory usage, and start time.
Below are some of the signals that we can send to a process when it is killed:

SIGTERM - Kill the process, but allow it to do some cleanup tasks beforehand
SIGKILL - Kill the process - doesn't do any cleanup after the fact
SIGSTOP - Stop/suspend a process

systemctl -- this command allows us to interact with the systemd processWe can do four options with systemctl:

Start;
Stop;
Enable;
Disable;

cron -schedule a certain action 

log- /var/log
apache2
firewall
nginx
access log
error log






— — — — — — — — — — — — — — — — — — — — — — — — — — — — — — — —

— — — — — — — — — — — — — — — — — — — — — — — — — — — — — — — —



Module - Linux Fundamentals

Linux Fundamentals Part 3

Power-up your Linux skills and get hands-on with some common utilities that you are likely to use day-to-day!

— — — — — — — — — — — — — — — — — — — — — — — — — — — — — — — —

Task1

Let’s proceed!

Correct Ans: No answer needed

— — — — — — — — — — — — — — — — — — — — — — — — — — — — — — — —

Task2

I’ve logged into the Linux Fundamentals Part 3 machine using SSH and have deployed the AttackBox successfully!

Correct Ans: No answer needed

— — — — — — — — — — — — — — — — — — — — — — — — — — — — — — — —

Task3

Create a file using Nano

Correct Answer: No answer needed

Edit “task3” located in “tryhackme”’s home directory using Nano. What is the flag?

Correct Answer: THM{TEXT_EDITORS}

— — — — — — — — — — — — — — — — — — — — — — — — — — — — — — — —

Task4

Ensure you are connected to the deployed instance (MACHINE_IP)

Correct Answer: No answer needed

Now, use Python 3’s “HTTPServer” module to start a web server in the home directory of the “tryhackme” user on the deployed instance.

Correct Answer

Download the file http://MACHINE_IP:8000/.flag.txt onto the TryHackMe AttackBox

What are the contents?

Correct Answer: THM{WGET_WEBSERVER}

Create and download files to further apply your learning — see how you can read the documentation on Python3’s “HTTPServer” module. Use Ctrl + C to stop the Python3 HTTPServer module once you are finished.

Correct Answer: No answer needed

— — — — — — — — — — — — — — — — — — — — — — — — — — — — — — — —

Task5

Read me!

Correct Answer: No answer needed

If we were to launch a process where the previous ID was “300”, what would the ID of this new process be?

Correct Answer: 301

If we wanted to cleanly kill a process, what signal would we send it?

Correct Answer: SIGTERM

Locate the process that is running on the deployed instance (MACHINE_IP). What flag is given?

Correct Answer: thm{processes}

What command would we use to stop the service “myservice”?

Correct Answer: systemctl stop myservice

What command would we use to start the same service on the boot-up of the system?

Correct Answer: systemctl enable myservice

What command would we use to bring a previously backgrounded process back to the foreground?

Correct Answer: fg

— — — — — — — — — — — — — — — — — — — — — — — — — — — — — — — —

Task6

Ensure you are connected to the deployed instance and look at the running crontabs.

Correct Answer: No answer needed

When will the crontab on the deployed instance (MACHINE_IP) run?

Correct Answer: @reboot

— — — — — — — — — — — — — — — — — — — — — — — — — — — — — — — —

Task7

Since TryHackMe instances do not have an internet connection…this task only requires you to read through the material.

Correct Answer: No answer needed

— — — — — — — — — — — — — — — — — — — — — — — — — — — — — — — —

Task8

Look for the apache2 logs on the deployable Linux machine

Correct Answer: No answer needed

What is the IP address of the user who visited the site?

Correct Answer: 10.9.232.111

What file did they access?

Correct Answer: catsanddogs.jpg

— — — — — — — — — — — — — — — — — — — — — — — — — — — — — — — —

Task9

Terminate the machine deployed in this room from task 2.

Correct Answer: No answer needed

Continue your learning in other Linux-dedicated rooms

Correct Answer: No answer needed

— — — — — — — — — — — — — — — — — — — — — — — — — — — — — — — —
