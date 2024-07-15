### Functionality of the Script
This PowerShell script is designed to automate the execution of Atomic Red Team tests for specified techniques, log the details of each test execution to a CSV file, and log the overall execution process to a log file. The script randomizes the order of the tests to be executed.

#### 1. Importing the Invoke-AtomicRedTeam Module
- Import-Module C:\AtomicRedTeam\invoke-atomicredteam\Invoke-AtomicRedTeam.psd1
- This line imports the Invoke-AtomicRedTeam module, which is necessary for executing the Atomic Red Team tests.

#### 2. Define the Path for the CSV Log File
- $csvLogPath = "Z:\attackLog.csv"
- This variable defines the path where the CSV log file will be stored.

#### 3. Define the Path for the Prompt Log File
- $TranscriptPath = "Z:\AtomicRedTeamPromptLog.txt"
