# Qt6 FontRendering Fix for Qt6.0 - 6.6 all apps
I found problem as Thai Language font randering (normally Qt6 displaying as Angsana New)
- Normally Qt5.x and lower Thai font language Default: **Tahoma**
- is problem in Qt6 is not detect font to **"Tahoma**, this bug is fixed in Qt 6.7.x
- font is calling in "A" header name
  - solved: use tahoma is Edit Name info to "A" Header name (Example: asdf regular...)
  ![image](https://github.com/user-attachments/assets/f0b28495-a7cf-4811-a992-759ea5cd4bb2)


---
### Before
![image](https://github.com/user-attachments/assets/60a3b551-b76c-4ced-998b-c299b6417a25)

### After
![image](https://github.com/user-attachments/assets/945d6f4b-57a6-4a42-8828-61578924c636)
