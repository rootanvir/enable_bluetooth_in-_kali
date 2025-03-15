# Enable Blutooth in Kali Linux
  ### check is bluetooth adapter connected to the machine
- 
  ```  
  lsusb 
  ```
  ### Enable bluetooth
-
  ```  
  sudo systemctl enable bluetooth
  ```
  ### start bluetooth service
- 
  ```  
  sudo systemctl start bluetooth
  ```
  ### check if it's enabled
- 
  ```  
  sudo systemctl status bluetooth
  ```
  ### install bluetooth utilities

- 
  ```  
  sudo apt install bluez blueman
  ```

### bluetooth icon should be appeared in taskbar
