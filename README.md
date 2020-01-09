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

Magento2 blank login<br>
Magento2 blank login page <br>
Magento2 blank login page no error <br>
Magento2 blank login page no error solution<br>
Magento2 login page not working<br>
Magento2 login page not shown<br>
Magento2 login page not showing<br>

Keep learning and Sharing :)<br>
