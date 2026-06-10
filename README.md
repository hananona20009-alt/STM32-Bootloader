# STM32_setup_guide
 • This Guide Explains How To program The STM32 Bootloader Using An ST-LINK Programmer.
 
**1.Connect The ST-LINK Pins To The STM32 Board As Shown Below.**
![stlink_connection](https://github.com/hananona20009-alt/STM32-Bootloader/blob/ae8d48a4974332923e0dd0246060e04a755f8698/Guide-images/stlink_connection.jpg))

**2.Install The Required Drivers.**

Step 1: Download The STM32 Package.
 •Download And Extract the STM32.zip Folder.
 
Download link: [https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqa3dfV1lobkoxYzhxaldSZTFaR1lKenlaRnhnQXxBQ3Jtc0trdmJURTdRRFBLZTFKN0UzNERXTi1VSTVVQ19KdUFWWFk0SFBfWXIzUmhwNTdUU3F3NmF3U3hLZmJ6NWFvZ0RfbHpZY09nUm5WZUwxUm4yUi1BOUJNVFJrdkczZmNKVFBmX29XYmswc2N3RWNObWktdw&q=https%3A%2F%2Fdrive.google.com%2Ffile%2Fd%2F1fVquLLnsXQLfVI3k2A7MiQdaYENsQ0Mo%2F&v=HnB7RTHa2Rw&html_redirect=1] 

 ![driver_package](https://github.com/hananona20009-alt/STM32-Bootloader/blob/09166a6de138ee114eb6ac4e3e3e38867a73488a/Guide-images/driver_package.png)

Connect the ST-LINK to your laptop.

Step 2: Install ST-LINK Drivers

Open STM32 folder STM32 Folder
                     
                     └── Drivers 
                          
                          └── dpinst_amd64.exe (install it).
.Run dpinst_amd64.exe and complete the installation.

![stlink_utility](https://github.com/hananona20009-alt/STM32-Bootloader/blob/86b09e3d48f3175248058997e60f2cd30e730548/Guide-images/stlink_utility.jpg)

Step 3: Install Additional Drivers
Open The "Win" Folder And Install The Required drivers.

![install_driver](https://github.com/hananona20009-alt/STM32-Bootloader/blob/c6740c6c98844ec55f770ee7ce5691e74fd5867b/Guide-images/install_driver.jpg)

**3.Flash The Bootloader using ST-LINK Utility**

 Step 1: Install STM32 ST-LINK Utility v4.6.0 --> Setup

![setup](https://github.com/hananona20009-alt/STM32-Bootloader/blob/32b6f10f1c7124270207aa60032682e3a6035145/Guide-images/setup.png)

Step 2: Open The Bootloader File
 Open STM32 ST-LINK utility And  follow These Steps:
 
1.Click File --> Open File

2.Navigate to The STM32 Folder

3.select: generic_boot20_pc13

4.Open Target --> Settings 

5.Make Sure That You Set Your Frequency to *4.0* MHz

![checking](https://github.com/hananona20009-alt/STM32-Bootloader/blob/a02f552d2c006a4d1e0e2a5e5230c3c6a10b79bd/Guide-images/checking.png)

Step 3: Program The bootloader
Click on "program & verify" and wait for the process to complete

![program_verify](https://github.com/hananona20009-alt/STM32-Bootloader/blob/5ac1f1734d542ad1bca4fc7e367297f982137865/Guide-images/program_verify.png)

After The Programming Process Finishes Successfully, The STM32 Is Ready To Be Used With The Bootloader👏

