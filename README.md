# notes
To kill a running process in windows
1. Find the port "8080" running process
-- netstat -ano | findstr :8080
2. You will see the porcess ID, to kill the running process
--- taskkill /PID 10600 /F 
PID-- Process ID
/F -- force
