## Why you Should use Linux for this Course

Before you start doing the installations, let's talk about the operating system you'll be installing everything *on*. Your choice of operating system makes no difference whatsoever when you're learning HTML, CSS, and Javascript. However, problems may arise when you start learning Ruby on Rails if you're using a Windows system. The programmers who created Rails had a preference for Unix-based operating systems (OSX, Linux), which means learning Rails on a Windows machine is a recipe for major frustration. If you use an Apple system or already have Linux, you can skip this lesson and proceed to the Installations project.

If you use Windows, here are some of the main reasons for using Linux when learning Rails:

* Because of the fundamental differences between Unix-based operating systems and Windows, installing Rails on a Windows machine is likely to give you problems that you would not encounter if you were installing on a Linux system and these can be a real pain to solve. Don't give yourself unnecessary headaches.

* The above point extends to the different gems you will be using with Rails in the future. Most of the latest updates to gems will be targeted at Unix-based systems. They may eventually get patches to make them work with Windows but some may never get updated to work on Windows.

* Because of the instability of Rails on Windows you will probably find yourself second-guessing whether some of the errors and bugs you encounter when developing are being caused by your system or the code you have written.

* Most of the examples throughout the learning process will assume you are using a Linux or OSX based system, you will have to translate these into the equivalent Windows commands yourself if you stick with Windows. *(Windows Command Prompt commands can vary greatly from Unix terminal commands, and they are often less intuitive.)*

* Most of the Rails community (and development community in general) use Unix-based systems, so this will make finding help with set up and configuration problems very difficult if you are installing on Windows. In fact the most common response you are likely to get is "install Linux".

* **Bonus**  Experience with Linux will look great on your CV.

We at Odin don't have anything against Windows, we simply want you to succeed at your goal of learning to program. We don't want to see you get majorly frustrated and give up on this first hurdle of getting everything installed. Therefore we unequivocally recommend using Linux or a Mac for this curriculum.

### Options for Installing Linux
The good news is installing Linux is not as hard as you might have imagined. Unlike Windows and OSX, Linux is free and open source so you don't have to pay for anything. Yay!. Secondly there are three options available that allow you to run Linux alongside your current Windows system, so you can choose the one that suits your situation best.

There are many different versions of Linux out there and many people who have used Linux for any length of time will have different opinions on which one is best. We wont go into any of that here and will simply recommend you use Ubuntu which is generally known as one of the most beginner-friendly versions as well as having a very similar graphical user interface to Windows.

We will review the three ways to run Linux on your system with the pros and cons of each, and then we will provide installation instructions afterward for each option.

####Option 1 - Dual Booting
You can install Ubuntu alongside Windows on your machine by dual booting. This essentially means when you boot up your computer you will brought to a screen that will allow you to choose which operating system you want to use, either your Windows operating system or your new linux operating system. 

**Pros**

* Gives you access to both Windows and Linux
* Yields the best performance from Ubuntu as it will be installed directly on your hard drive.
* Allows you more customization by having access to Ubuntu's package (program) manager and ability do download and configure programs (namely text editors) and utilities directly.

**Cons**

* Messing up your Windows installation is a possibility when setting your computer up to dual boot (this is difficult to do)
* To switch between your two operating systems you will have to reboot your computer.

####Option 2 - Use a Virtual Machine
A Virtual Machine is essentially a program that runs on your computer that emulates another computer system. If you have any experience of using emulators to play games that were released for old games consoles, this will be familiar. If not [here](http://www.makeuseof.com/tag/virtual-machine-makeuseof-explains/) is a very good explanation of what a virtual machine is. 

**Pros**

* You can access Windows and Linux, with the extra benefit of being able to switch between the two instantly.
* No risks to messing up your Windows installation by doing something wrong with a dual boot
* You can customise as you like with different text editors, etc.

**Cons**

* Performance with Ubuntu won't be as sharp as a dual booting

#### Option 3 - Using an Online IDE
There have been some great online IDEs (Integrated Development Environment) released in the past few years. These are similar to Virtual machines; in fact that's how they are set up in the background. The difference is they are websites so you can only use them in your browser. Of course this means you can log in from any computer and start coding from your browser when you have access to the internet. [Cloud9](https://c9.io/) and [Nitrous](https://www.nitrous.io/) are two of the most popular online IDE's.

**Pros**

* You don't have to install anything on your local machine 
* Your coding environment will be available from any machine with internet access.

**Cons**

* You have to use the text editors that their services provide, which generally are not as good as the text editors you can install locally. (e.g., Atom, Sublime Text, etc.)
* The free tiers of these services have a memory limit, normally 1GB. This can be a major limitation after a while.

###Installation

Once you've chosen your preferred method of installation, follow the appropriate instructions below. If you get stuck, try reading documentation, FAQs, Google it, or ask for help in our [chat](https://gitter.im/TheOdinProject/theodinproject). 

####Dual-Boot Windows and Linux

This option allows you to install a full Linux operating system onto your hard drive. You can install alongside Windows so you don't lose all your current files. **WARNING:** Before you do this process, its not a bad idea to create a back-up of your current hard drive in case you make a mistake. We will walk you through how to install the Ubuntu flavor of Linux since its one of the most popular versions, its versatile, and easy to use. 

You can watch a video [here](https://youtu.be/SOfnvbdWhrs) of how to set this up. **Note:** You will need either a **DVD**-R[W] or a USB stick to perform this installation.

* Go to [Ubuntu's](https://www.ubuntu.com/download/desktop) website and click "Download". (This will take a while so go grab a coffee or something while you wait.) During this time, you can also decide whether you want to install via an installation disc (DVD-R[W]) or USB stick/drive. Once download is complete, its not a bad idea to [verify the download](https://www.ubuntu.com/download/how-to-verify).

* If you want to install from disc, [burn your DVD](https://www.ubuntu.com/download/desktop/burn-a-dvd-on-windows). Make sure you use a DVD with a larger capacity than the file size of your download.

* If you want to install from USB stick/drive, follow [these instructions](https://www.ubuntu.com/download/desktop/create-a-usb-stick-on-windows) to download the installation utility and then write your ISO image to disk. **Note:** You *must* write in ISO image mode or subsequent steps won't work properly and your install will fail.

* Reboot your computer, making sure either your DVD is in your disc drive or your USB drive is plugged in. Follow [Ubuntu's installation instructions](https://www.ubuntu.com/download/desktop/install-ubuntu-desktop) to setup and install. *This step will take some time.*

**CAUTION:** Unless you have significant experience installing operating systems, make sure you follow Ubuntu's installation instructions very carefully and don't mess around too much with the partitioning and advanced setup options. Doing so has the potential to cause (possibly major) problems with your hard drive. Ubuntu's installer and instructions are pretty simple and straightforward; don't deviate from them and your setup should be a breeze.

* Once installed, you can mark this lesson complete and continue to the Installations project.

####Installing Linux with VirtualBox

If you don't wish to commit to a total installation of Ubuntu on your computer, you can install a Virtual Machine to run Ubuntu directly from your Windows desktop. 

* Before beginning, it is advisable to check system requirements for adquate RAM and hard drive space. VirtualBox is relatively lightweight, but you will essentially be running two operating systems *at the same time* so you'll need enough system resources/RAM to avoid lagginess in VirtualBox. Additionally, VirtualBox will create a 'virtual hard drive', which will require sufficient space on your hard drive for a file system.

* [Download VirtualBox](https://www.virtualbox.org/wiki/Downloads) and the [Ubuntu](https://www.ubuntu.com/download/desktop) ISO image.

* Follow instructions in [this video](https://www.youtube.com/watch?v=9_DpFhT_euI) to install VirtualBox and then to install Ubuntu into Virtual Box.

*You're all up and running!

####Getting Stuck

If you get stuck and aren't sure what to do, here are a few resources to consult for help:
* Ubuntu [Forums](https://ubuntuforums.org/) / [Ask Ubuntu](https://askubuntu.com/?_ga=1.127204421.931567303.1471565801)
* [VirtualBox Documentation](https://www.virtualbox.org/wiki/End-user_documentation)
* [Stack Overflow](http://www.stackoverflow.com/)
* Google the problem
* Ask for help in our [chatrooms](https://gitter.im/TheOdinProject/theodinproject)