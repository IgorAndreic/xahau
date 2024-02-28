Installation PM2 and starting the script
PM2 is a process manager for node.js applications that will help you run and monitor your application.

Install PM2 globally:

npm install pm2@latest -g
Launch your node.js script using PM2:

pm2 start app.js

4. Monitoring and control of the script
View Logs:

To view the logs of a running script, use the command:

PM2 logs (/root/.pm2/logs/app-error.log)
Script stop:

To stop the script, execute:  pm2 stop app.js  

Additional PM2 teams:

Restart the script: pm2 restart app.js
Show a list of advanced processes: pm2 list
Get detailed information about the process: pm2 show app
To stop the script, execute: pm2 stop app.js 
Launch of Skipt: pm2 start app.js
