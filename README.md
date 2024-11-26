# System-Health-Check-Repo

System Health Check Script (Shell Version)

Introduction:

The System Health Check Script is a menu-driven Bash tool designed to perform essential system monitoring tasks. It provides users with the ability to check disk usage, monitor running services, assess memory usage, evaluate CPU usage, and send comprehensive system health reports via email. This script is lightweight, easy to use, and focuses on simplicity and reliability, making it ideal for beginners and system administrators alike.


Features:

1]Disk Usage Check: Reports disk usage percentages and available disk space.
2]Running Services Monitoring: Displays the status of active services (requires systemctl or an equivalent tool).
3]Memory Usage Assessment: Displays total and used memory along with usage percentage.
4]CPU Usage Evaluation: Monitors and reports current CPU utilization.
5]Email Reports: Automatically generates and sends a comprehensive system health report every four hours via email.
6]Error Handling: Incorporates basic error handling to manage unexpected failures.
7]Debugging Logs: Outputs logs to a file for debugging and monitoring execution.

How to Use:
1]Clone the repository:
https://github.com/testaaditya/System-Health-Check-Repo.git
cd System-Health-Check-Repo.git

2]Set Permissions: Ensure the script is executable:
chmod +x health_check.sh

3]Run the Script: Execute the script:
./health_check.sh

Follow the Menu:
1]Select the desired option from the menu.
2]The script will display the requested information.
 

Configure Email:
1]Update the script with your SMTP server details and credentials to enable email functionality.

Challenges
1. Handling Email Setup
Problem: Sending emails from a shell script required configuring mail or sendmail utilities.
Solution: Provided instructions to install and configure mailutils or sendmail for the system.

2. Cross-Platform Compatibility
Problem: Commands like systemctl and free vary across distributions and operating systems.
Solution: Added conditional checks for commands and provided alternative implementations when necessary.

3. Debugging and Error Logs
Problem: It was hard to debug without proper logging in place.
Solution: Redirected script outputs and errors to a log file for tracking.

1]Shell Scripting Basics:
Improved skills in writing shell scripts for system monitoring.

2]System Administration:
Understood key aspects of disk, memory, and CPU monitoring using Linux utilities.

3]Cross-Platform Adaptation:
Learned to write scripts compatible with multiple Linux distributions.

4]Debugging in Shell:
Gained experience in logging and debugging shell scripts.

Key Commands Used
1]df: To check disk usage.
2]systemctl: To monitor services.
3]free: To assess memory usage.
4]top or mpstat: To evaluate CPU usage.
5]mail or sendmail: For sending email reports.

