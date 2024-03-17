# Easy-Clone-OS

<a href="https://github.com/johnwilliamstech/Easy-Clone-OS/blob/main/easyclone-os-demo.mp4">Download Video Here<a>

Instructions For Making Clones Of Your Operating System - For Backup &amp; Recovery

EasyClone OS Beta

An easier way to create backup copies of your computer, so you can restore it to a previous state.

Table of Contents

1\. What Is A Disk "Clone"?

2\. Cloning A Computer Hard Drive Can Be Hard

3\. Works Everywhere

4\. All You Need Is A USB Flash Drive, A Backup Hard Drive

5\. Installing EasyCloneOS on your USB Drive

6\. Booting Your Computer Into EasyClone

7\. How To Change The Password

8\. How To Create Your First Backup Clone File

9\. How To Restore A Backup File To Your Computer

10\. Best Practices

11\. Instructions For Advanced Features

12\. Disclaimer

What Is A Disk"Clone"?

The Process The Process of Disk Cloning open in a new window icon, as it relates to EasyClone OS, creates a computer file that contains an identical copy of your computer's hard drive. Since your computer's hard drive contains both your files and your operating system, cloning lets you save (and restore) literally everything on your computer. This includes your apps, your settings, your customizations, and your files, whereas other computer backup apps only backup your files.

The goal of EasyClone OS is to make cloning your computer hard drive easier to do. Apple's Time Machine software is relatively easy to use, but it does not create true clones and so it can be unreliable. Microsoft Windows has a "System Image" app, but it is hidden, not intuitive to use, and there are no instructions. Linux does not have a widely popular cloning tool, and the ones that exist are not at all easy. While all Operating Systems have good and easy file backup apps, none of them have easy hard drive cloning tools to backup your computer. EasyClone OS aims to solve this issue.

**EasyClone OS Works With Every Operating System**

Even though EasyClone OS uses the Manjaro Linux Distribution open in a new window icon (which runs on arch open in a new window icon Linux), as well as the Gnome Desktop open in a new window icon, it can be used to backup any operating system that you connect as a drive to your computer. Whether your computer operating system is Microsoft Windows, Macintosh OS, Linux Based, or something else entirely, EasyClone OS can create an exact copy or "clone" of your operating system, and allow you to save it as a ".img file". You can then use EasyCloneOS and your .img backup file, to restore your computer to its exact previous state.

**All You Need Is A USB Flashdrive, A Backup Hard Drive**

To get started with EasyClone OS, you are going to need:

1 USB Flashdrive that is 32GB or bigger

1 Separate hard drive - (internal or external) that is at least as big as your computer's main hard drive.

Note: "flash drives" sometimes also go by the name "thumb drive", "jump drive", "USB stick", "portable USB drive", "memory drive", or "storage drive". For EasyClone OS any of these should work if they are at least 32 Gigabytes (GB). It is also possible to use devices other than thumb drives such as SD Cards, MicroSD Cards, External Hard Drives, etc. but it is not recommended for computer beginners or novices to use these.

**Installing EasyClone OS On Your USB Drive**

Once you have your 32GB or bigger flash drive, plug it into your computer and follow the below instructions depending on your operating system.

If your operating system is Linux based, you may want to read the "How To Install Linux Software Using The Terminal" section, before using the commands below.

If your operating system is Microsoft Windows or Apple Macintosh, you can follow the instructions in this video open in a new window icon after downloading and installing the software using the link below.

IMPORTANT NOTE: THIS PROCESS WILL PERMENANTLY ERASE ALL OF THE INFORMATION CURRENTLY ON YOUR USB FLASH DRIVE. Please do not use a flash drive that has any data on it that you want to keep or have access to ever again.

How To Install Linux Software Using The Terminal: If your operating system has an app store, you can try using it to search and install whatever software you need. If you don't have an app store, you can follow the below commands to install software. As a first step, you will want to open the terminal on your computer. Most Linux operating systems will open the terminal with either the "ctrl + alt + t" or "super_key open in a new window icon + t" keyboard shortcut commands. Click and drag your mouse to select the text that corresponds to your operating system below. Then right click with your mouse and select "Copy" from the menu. Go back to the terminal and right click inside of it and select "Paste" from the menu, then press Enter.

**Booting Your Computer Into EasyClone**

After installing EasyClone OS you will want to access the "Boot Menu" of your computer to run EasyClone OS. Leave the EasyClone OS flash drive plugged into your computer while following these instructions.

The Easiest Way to get to the boot menu is to find your computer manufacturer's "boot menu option key"open in a new window icon and repeatedly press it when powering on the computer, until the menu appears. However, if you run into issues, you can try the below steps based on your operating system, to access the boot menu:

Microsoft Windows Boot Menu open in a new window icon

Apple Macintosh "Startup Manager" Boot Menu open in a new window icon

Your Linux Distribution's Boot Menu open in a new window icon

How To Change The Password

How To Change The Password of EasyClone OS

How To Change The Password

The first thing you should do when booting into EasyClone OS for the first time, is to change the password to something secure, and something that you will remember.

You should write your password down on paper and save it, but if you ever accidentally lose it, forget it, and can't get in, you can always reinstall EasyClone OS by repeating the steps on this page.

On the Green Settings Icon with the Wrench.

Click on the “Users” item in the left of the Settings window.

Click the arrow next to “Password” on the “Users” page.

In the “Change Password” box, click in the “Current Password box, and enter this text: changethispasswordnow

Enter your password in the “New Password” then again in the “Confirm Password” box, Then Press the Blue “Change” button in the upper right hand corner of the window.

**How To Create Your First Backup Clone File**

Once you are booted into EasyClone OS and you have changed your password, you should see an open window titled "Disks". If you do not see it, click on the grey icon with the wrench in your toolbar, it will be the second from left icon.

In the left column of the "Disks" window you should see a list of available disks. If you haven't done so already, find the (external) hard drive where you are going to keep your EasyClone backup files, and connect it to your computer's USB port. You should then see your hard drive listed in the in the left column of the "Disks" window, as well as your computer's main hard drive, and the EasyClone OS Flash Drive. As a general rule, your computer's main hard drive will be the first drive listed at the top of the left column. However, if you are not sure which drive is which, you can:

Look at the names of the disks

Read the "Starting GNOME Disk Utility" section of this tutorial open in a new window icon

Watch this video open in a new window icon from 2:08min - 3:45min

Compare the size of the drives: The EasyClone Flash Drive is likely under 100GB, your primary hard drive is likely 500GB or bigger, and the external hard drive should be at least as big as the main hard drive, but likely bigger.

IT IS VERY IMPORTANT TO KNOW WHICH DRIVES ARE WHICH, OTHERWISE YOU WILL DESTROY ALL THE DATA ON BOTH DRIVES.

Next you will left click on your primary hard drive (likely the drive at the top of the list on the left), then click on the three vertical dots on the top far-right of the window, and click on "Create Disk Image..." from the drop-down menu.

You will see a pop-up "Create Disk Image" window with three boxes: "Source", "Name", and "Save in Folder". Select the text in the "Name" box and type a name for your backup file. Best practice is to name it something like "My-Laptop-Backup-Month-Day-Year.img", in any case make sure it ends with the text ".img" or the backup won't work.

Click on the drop-down menu in the "Save in Folder" box. If you see the (external) hard drive where you are going to save your backup to, select that from the list. If you do not see the (external) hard drive where you are going to save your backup to, select the "Browse" item at the bottom of the list, this will allow you to browse for your backup drive and select it.

Now you can click the "Start Creating..." button in the bottom right of the "Disk" window. Depending on how big your computer's hard drive is, this could take a while, but you will see a thin blue progress bar at the top of the "Disks" window that will let you know how far along the backup is.

Once the progress bar disappears, your backup is done! If you open a new window by clicking on the grey "Files" icon in the toolbar, you can navigate to your backup drive to verify your backup file is there. You can then optionally verify that the backup file is the same size as your hard drive by right clicking on the file and selecting "Properties" from the drop-down menu. You will see a pop-up window with a "Contents" row that should tell you the size of your backup file.

You can now shutdown your computer by clicking on the icons in the bottom right corner of EasyClone OS by clicking on "Power Off / Log Out" and select "Power Off". Once the computer is off, you can remove the EasyClone OS USB Flash Drive, and then continue to use your computer as you normally do.

**How To Restore A Backup File To Your Computer**

Restoring a backup file to your computer is very similar to creating a backup file. The only differences are:

Instead of selecting "Create Disk Image" from the drop-down menu in the top right of the "Disks" window, you will instead click the "Restore Disk Image" drop-down menu item.

In the "Restore Disk Image" pop-up window, click on the drop-down menu in the "Image to Restore" section, and navigate to your .img backup file. Select the file and click the "Start Restoring" button in the bottom right of the pop-up window.

**Best Practices**

Don't Connect EasyClone OS to the Internet: EasyClone OS is disconnected from the internet by default because it is much more secure if it never connects to the internet. You can enable internet access, but it is not recommended

Don't store personal data on EasyClone OS: This will make it easier to switch to newer versions. Since EasyClone OS is not encrypted, it's a best practice to not have any of your personal data on it.

Don't run updates on EasyClone OS : Instead come back here for update versions.

Make an EasyClone backup before making major changes to your computer : Whether it's a software update, or you are lending your computer to a friend, or if you are installing new complicated software, having an EasyClone backup file to restore to, can free you to experiment and make any changes to your OS, without having to worry about completely loosing your data or breaking your computer.

Make an EasyClone backup At Least Once A Month Even if you have not made major changes to your computer, software updates, accidents, and hardware problems, can come unexpectedly, so it is important to have up-to-date backups before problems occur.

Keep Your Backups in A Safe Location Seperate, or better yet duplicate, your backup files from your actual computer. Using external hard drives, and/or encrypted cloud backups can be good ways to make sure you never loose your backup files.

**Instructions For Advanced Features (Coming Soon)**

Check back soon for updated instructions detailing more advanced features and uses for EasyClone OS. Some of these will include:

How To Keep Your Primary OS On A Flash Drive: Keeping your OS on a high-performance flash drive will allow you to still use it like a normal computer, but it will increase the speed of your EasyClone backups. Keeping your OS on a high-performance flash drive will also save a lot of space when storing your backup files, so you can go back further in time when restoring your computer and have more choices about when to back up your computer.

Storing your backups inside an encrypted container & on an encrypted hard drive: This will keep your backups and data much more secure.

Auto-encrypting your backup files before syncing them to a cloud backup service like Dropbox: This will keep your backups and data much more secure as not even your cloud provider will be able to see your data, but you will still have the benefit of accessing your backup files from anywhere, as well as allow you to more easily recover in the event of hardware theft or damage. Many cloud storage providers also have a version history of the backup files you upload, which can come in helpful.

Using an internal hard drive with EasyClone OS: This will save physical space and may help to keep your backups and files more organized and easier to access. Having easier access increases the chances of making more backups, and having system restores go more smoothly.

Backing-up your Android or Linux smartphone: This will save physical space and help keep your backups and files more organized and easier to access. Having easier access increases the chances of making more backups, and having system restore processes run more smoothly.

Disclaimer

EasyClone OS is a hobby project by John Williams Digital and is intended for personal hobby use. EasyClone OS is not intended for highly important, or business-related data backups. If your data is of high importance, you should take your data to a computer store to have your data professionally backed-up and/or restored. EasyClone OS and John Williams Digital TAKES NO RESPONSIBILITY AND IS NOT LIABLE for any lost data, damage to software, or damage to hardware.

EasyClone OS Works With Every Operating System

Even though EasyClone OS uses the Manjaro Linux Distribution open in a new window icon (which runs on arch open in a new window icon linux), as well as the Gnome Desktop open in a new window icon, it can be used to backup any operating system that you connect as a drive to your computer. Whether your computer operating system is Microsoft Windows, Macintosh OS, Linux Based, or something else entirely, EasyClone OS can create an exact copy or "clone" of your operating system, and allow you to save it as a ".img file". You can then use EasyCloneOS and your .img backup file, to restore your computer to its exact previous state.
