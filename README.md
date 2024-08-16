# assignment2
1. What is Logging?
  Logging is the process of recording events, messages, or other types of data within a software application. It involves capturing information about the system's     
  operation, user actions, errors, and other significant events that occur during the execution of a program. 

2. Why Logging is Important

  -Debugging and Troubleshooting: Logs provide insights into what happened in an application before an error or issue occurred. They help developers and system     
   administrators identify and fix problems more quickly.
  
  -Monitoring and Maintenance: Continuous logging allows for real-time monitoring of applications and systems. By reviewing logs, you can detect unusual patterns or 
   behaviors, which might indicate potential issues before they escalate.
  
  -Auditing and Compliance: Logs serve as an audit trail, recording actions taken by users and the system. This is important for security, regulatory compliance, and 
   forensic analysis.
  
  -Performance Analysis: By analyzing logs, you can understand the performance of your application, identify bottlenecks, and optimize resource usage.
  
  -Security: Logging can help detect unauthorized access or suspicious activities, making it a vital component of security monitoring.

3. Understanding Logging Levels
  Logging levels are predefined categories that determine the importance or severity of the events being logged. Common logging levels include:
  
  -DEBUG: Detailed information, typically of interest only when diagnosing problems. This level logs everything, making it useful for developers during the 
   development phase.
  
  -INFO: General operational information about the application's progress. This level is used to confirm that things are working as expected.
  
  -WARNING: Indications that something unexpected happened, or indicative of some problem in the near future (e.g., 'disk space low'). The application is still 
   working as expected.

  -ERROR: An error occurred, but the application can still continue running. This level is used to record exceptions or other significant issues that require 
   attention but aren't critical.
  
  -FATAL: A serious error, indicating that the program itself may be unable to continue running. This level is often used to log failures that require immediate 
   attention.
