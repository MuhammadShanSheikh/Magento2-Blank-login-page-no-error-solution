### In this guide we do:

## Magento2 Blank login page no error: solution

Go to the directory link below
**Your Project Path**
C:\xampp\htdocs\your-project-name

**Current Example Project Path**
C:\xampp\htdocs\magento2\vendor\magento\framework\View\Element\Template\File\Validator.php

**Copy this below code and paste into "Validator.php" on line 140**
$directory = $this->fileDriver->getRealPath($directory);
add this code on line 140 inside of foreach loop before if{--} condition
Reload your admin login page and enjoy.

**Social Link:**

Link: https://www.youtube.com/channel/UCUM5ExJR36MfbTiETdcCJGg
Github: https://github.com/MuhammadShanSheikh/How-to-boost-programming-speed

**Tags:**

Magento2 blank login
Magento2 blank login page 
Magento2 blank login page no error 
Magento2 blank login page no error solution
Magento2 login page not working
Magento2 login page not shown
Magento2 login page not showing

**Contact For Personal Training, Assignments and Projects**

**Sr. Web Developer
Muhammad Shan Sheikh
Mobile/Whatsapp: +923336747574
Skype: sheikh.shan28**

Keep learning and Sharing :)
