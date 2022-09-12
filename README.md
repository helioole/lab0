# lab0

## Installing UNIX-based operating system.
I've installed Manjaro LInux with the following steps:

### Step 1. Partition the space.
I had to make space for installing Manjaro. Since I had a free disk D, I've decided to dedicate it to installing LInux.
So, it looked like this on Windosk disk manager in the end of installing:
![Screenshot from 2022-09-12 18-19-55](https://user-images.githubusercontent.com/113358365/189692384-cf6ed65e-2895-462d-8462-c1705830747b.png)

### Step 2. Downloading the ISO in live USB
I've downloaded the ISO from the Manjaro webside and burnt it to a USB flash drive. 
![Screenshot from 2022-09-12 18-21-56](https://user-images.githubusercontent.com/113358365/189693599-0f40db56-550a-46de-bdb2-97c2d0d8a855.png)

###  Step 3. Booting into a Live Environment
I've restarted my computer and was pressing F2 key comtinously, so I could get it in BIOS settings. After changing Boot priority, I had Windows on UEFI and LInux on Legacy.

Once the USB flash card is connected to the laptop, I could start the Manjaro installation.

### Step 4. Installing Manjaro Linux.
*(The next screenshots will be provided as examples since i couldn't make screenshots during installation)*

I could launch the installer after clicking the "Launch Installer" button:
![Manjaro-Installation-Language](https://user-images.githubusercontent.com/113358365/189696996-2be33f4c-ee97-4beb-8bda-4bb9216df4a0.png)

Then I clicked "Continue" and had to set my location, time zone and click "Next" again. After this the next option was "Keyboard" where you have to set language and layout.
I've faced problems with "Partition", since I could use the free space which included the whole disk D and had more than enough storage for installing Manjaro. Therefore, I had to divide it manually. The result was shown on the first screen above.

Afterwards, the hardest past left I just had to set all the users settings such as my name, name of the computer and password. Then I could see "Summary" and finally "Install" and after it "Finish" which looked like this:
![Screenshot from 2022-09-12 18-52-06](https://user-images.githubusercontent.com/113358365/189699642-d3bd7116-44f4-45c0-b4ff-c1ed7bebaa02.png)
![Screenshot from 2022-09-12 18-52-06](https://user-images.githubusercontent.com/113358365/189699660-b936e6fd-72d3-4762-b609-a8ca0378c8c3.png)



## Installing essential tools
The first essential tool was zsh shell. I had it already after installing Manjaro so I skipped this step:![Screenshot from 2022-09-11 21-28-02](https://user-images.githubusercontent.com/113358365/189700030-ea8309ec-0c6a-4250-9170-221a7dbe03b6.png)

Then I installed oh-my-zsh which is the most popular framework for managing Zsh configuration, plugins, and themes:
![Screenshot from 2022-09-12 14-59-52](https://user-images.githubusercontent.com/113358365/189700685-be76574a-a8b5-48db-a0d4-4efffc4b93a1.png)

Also had to install Git:
![Screenshot from 2022-09-11 21-30-40](https://user-images.githubusercontent.com/113358365/189700854-27c71afa-9b3e-477e-a011-ccef41e01ea1.png)

I downloaded base-level grub that included gcc:
![Screenshot from 2022-09-11 21-56-46](https://user-images.githubusercontent.com/113358365/189701181-9781a8a4-d413-4116-a13f-666874e49fe7.png)

And my favorite IDE - Visual Studio Code

## Creating a Git repository
I made a folder named "lab0" whewe my C program is supposed to be:
![Screenshot from 2022-09-12 16-07-44](https://user-images.githubusercontent.com/113358365/189703641-f0410605-275d-483f-a263-2d3b7a0ea162.png)

The main.c file included the "Hello, World!" program:
![Screenshot from 2022-09-12 16-20-05](https://user-images.githubusercontent.com/113358365/189703839-f570af9a-bb2b-4277-9f1e-eb008f34fb54.png)

Further, I made a new repository on GitHub and named it "lab0". Therefore, I had to connect my GitHub account and Git on my laptop so I could I have acces to my program in this folder from GitHub website. Entered my user email and user name, added my first commit and changed branches from "master" to "main":
![Screenshot from 2022-09-12 16-58-46](https://user-images.githubusercontent.com/113358365/189706702-a8012b7c-8e42-4f89-b541-02f4feb7d208.png)

and pushed it:
![Screenshot from 2022-09-12 17-12-10](https://user-images.githubusercontent.com/113358365/189708771-7132ce9c-74e5-48e2-8bb2-da3cfdc2c0a8.png)

The result on GitHub webpage:
![Screenshot from 2022-09-12 17-09-29](https://user-images.githubusercontent.com/113358365/189707229-4998034a-0cb6-45fe-ac6f-4bfcb553a536.png)

Now it's time for a Makefile, adding the second commit, compiling and running the program:
![Screenshot from 2022-09-12 17-26-08](https://user-images.githubusercontent.com/113358365/189709172-5fe20646-72c0-4b0e-8e9b-7d29430748fc.png)
