# Ticket-1002-The-computer-will-not-turn-on

# Introduction
This activity simulates an IT Support ticket submitted by a user. Your task is to resolve the issue and document the process, as you would using a ticketing system.  
To troubleshoot this ticket, you will need to import and launch a Virtual Machine named Ticket #1002 using VirtualBox.

# Equipment/Requirements
Computer with internet connection and VirtualBox installed.
The Ticket #1002 VM (Open Virtual Appliance (OVA) file).



Ticket ID #
1002
User Name
Learner01
User’s email
leraner01@TechSolutions.com
Priority
High
Category
Hardware
Status
Resolved
Subject
The computer will not turn on
Asset
capstone120
Assigned to
Gregg Nicholas

# Description
Hey IT Team,

Learner01 here. My computer's giving me a black screen with a bunch of confusing text when I try to turn it on. I'm using my phone to send this 'cause I can't get past this screen.

If you could check it out and help me out ASAP, that'd be awesome. Got work waiting.

Thanks,
Learner01
# Tasks

Upon booting my Windows virtual machine, I encountered an error stating there was no bootable media. Restarting didn’t resolve the issue. To address this, I downloaded the Windows Media Creation Tool from Microsoft’s official website and used it to create a Windows 10 ISO file. I then mounted the ISO to the virtual machine’s DVD drive and restarted the system.

This launched the Windows Recovery Environment, where I selected Repair Your Computer. The repair process completed successfully, allowing me to log in. Afterward, I updated Windows to the latest version and verified the internet connection by browsing Google. Everything functioned as expected.

Issue resolved.
# Resolution (Internal-facing)
The issue began when the virtual machine displayed a message indicating that there was no bootable Windows media, preventing it from starting up properly. Despite restarting the machine, the error persisted, suggesting that the virtual hard disk containing the operating system might have become corrupted or unreadable.
To resolve the problem, I visited Microsoft’s official website and downloaded the Windows Media Creation Tool. This tool allowed me to create a bootable Windows 10 ISO file. I then inserted the ISO into the virtual machine's DVD drive, effectively mounting it as a bootable device. After restarting the virtual machine with the ISO mounted, it launched the Windows recovery options.
In the recovery options menu, I selected the “Repair” option, which initiated an automatic repair sequence. This process successfully addressed the boot issue, allowing Windows to load normally once again. The issue was likely caused by a corrupted boot sector or missing boot files on the virtual hard drive, which the repair tool restored, enabling the VM to boot correctly.
# Resolution (Client-facing)
Hi, I wanted to inform you that your issue has been successfully resolved. The problem occurred because the Windows operating system was unable to locate the necessary files to start Windows. This can sometimes happen if the boot files become damaged or unreadable.
To fix this, I downloaded a tool from Microsoft that allowed me to create a new set of startup files for Windows. I then used these files to repair the operating system, which restored its ability to boot up normally.
Your system is now working as expected, and you should be able to use it without any issues. If you have any further questions or run into any additional problems, please feel free to reach out.

Best regards,
Gregg
IT Support Specialist 

![Identifying Boot Issue](https://github.com/GreggNicholas/Ticket-1002-The-computer-will-not-turn-on/blob/main/Screen%20Shot%202024-12-01%20at%2021.51.24%20PM.png?raw=true)

![Boot from Iso -Windows Recovery](https://github.com/GreggNicholas/Ticket-1002-The-computer-will-not-turn-on/blob/main/Screen%20Shot%202024-12-01%20at%2021.52.09%20PM.png?raw=true)

![Verify Windows starup and full system functionality](https://github.com/GreggNicholas/Ticket-1002-The-computer-will-not-turn-on/blob/main/Screen%20Shot%202024-12-01%20at%2021.52.43%20PM.png?raw=true)




