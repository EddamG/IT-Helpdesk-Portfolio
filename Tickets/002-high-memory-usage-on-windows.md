#Ticket 002: High Memory Usage on Windows

##Ticket Information

- Ticket ID: 002
- Category: Windows Performance
- Priority: Medium
- Status: Investigation Completed
- Environment: Windows 11
- Type: Practical troubleshooting exercise

##User Report

The computer was experiencing high memory utilization and potential performance issues.

##Initial Findings

- Installed RAM: 16 GB DDR5
- Initial memory utilization: 13.7 GB (90%)
- Opera GX usage: approximately 3 GB
- ChatGPT usage: approximately 850 MB

##Troubleshooting Performed

1. Inspected Windows Task Manager.
2. Identified high memory usage in Opera GX.
3. Closed unnecessary YouTube tabs.
4. Observed reduced browser memory usage.
5. Investigated Windows memory composition.
6. Restarted Windows to compare memory utilization.
7. Reviewed startup applications.
8. Disabled selected non-essential startup applications.
9. Rechecked memory utilization.

##Results

- Memory utilization decreased from 13.7 GB to 8.5 GB.
- Available memory increased to 6.7 GB.
- Non-paged pool decreased from 1.5 GB to approximately 993 MB.
- No confirmed memory leak or hardware failure was identified.

##Resolution

Closed unnecessary browser tabs and disabled selected applications from automatically starting with Windows.

##Final Result

Memory utilization improved during the investigation. Further monitoring would be necessary to determine whether additional optimization is required.

##Skills Practiced

- Windows Task Manager
- Memory Management
- Process Investigation
- Startup Application Management
- Performance Troubleshooting
- Technical Documentation

Disclaimer

This report documents a practical learning exercise and does not represent a professional diagnosis of a hardware or software failure.
