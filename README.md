# system-monitoring

## Monitor System Performance
 # To monitor CPU, memory, and process usage, use
 sudo apt install htop

 ![monitoring1](monitoring1.PNG)
 htop
 ![monitoring2](monitoring2.PNG)

  # To check disk usage
   
   df -h
  ![monitoring3](monitoring3.PNG)
  
  du -sh /home
  ![monitoring4](monitoring4.PNG)

  # To search for specific entries in system logs
   
   grep "error" /var/log/syslog
  ![monitoring.5](monitoring.5.PNG)

   # To send alerts when disk usage exceeds 90%.
   
   sudo crontab -e
   ![monitoring6](monitoring6.PNG)