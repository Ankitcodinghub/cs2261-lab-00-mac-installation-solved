# cs2261-lab-00-mac-installation-solved
**TO GET THIS SOLUTION VISIT:** [CS2261 Lab 00-Mac Installation Solved](https://www.ankitcodinghub.com/product/cs-2261-lab-00-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;109936&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS2261 Lab 00-Mac Installation Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Mac Installation

Provided Files

● Makefile

● main.c

● tasks.json

● visualboyadvance-m-Mac.zip

Files to Edit/Add

● tasks.json

Instructions

Part 1: Docker Desktop

First, you’ll need to download Docker Desktop. In order to do this, you’ll need to sign up for Docker Hub. Sign up for Docker Hub here: https://hub.docker.com/signup

Once you’ve signed up, follow the detailed Docker Desktop download instruction here:

https://docs.docker.com/docker-for-mac/install/

Here, you’ll click on the “Download from Docker Hub” button (as seen above) and, granted you’re logged into the Docker Hub account you created, you’ll be taken to a new page that looks like the following:

Press the “Download Docker Desktop for Mac” button. In your downloads, you’ll see “Docker.dmg”.

Now, follow the “Install and run Docker Desktop on Mac” instructions on the Docker

Desktop download instructions page (https://docs.docker.com/docker-for-mac/install /) .

Great, you’ve got Docker Desktop on your machine! 🙂

Go to your applications, and click Docker.app, as seen below.

You should see, in the top right of your screen, a little icon that looks like the following:

This icon indicates that Docker Desktop is running on your machine! YOU MUST BE RUNNING DOCKER IN ORDER TO BUILD YOUR CODE. Otherwise, when you attempt to build your code, you will see the following error:

If you see this, you’ll know you forget to open the Docker Desktop application.

Part 2: VisualBoyAdvance-M

Let’s get the GBA emulator setup! VisualBoyAdvance-M is the emulator for this class. If you already have a GBA emulator that you are comfortable with, I still highly recommend you use this one for this class. It has some special features that will come in handy for debugging.

Unzip the “visualboyadvance-m-Mac.zip” and put the unzipped application in a folder. I recommend creating a CS2261 folder that will contain all of your homework, labs, etc. and keeping the “visualboyadvance-m.app” in this folder. Lab00 should be in this folder, too. Keep a note of the exact path of the “visualboyadvance-m.app”. In the image below, you’ll see a recommended folder setup. The exact path to

“visualboyadvance-m.app”, in my case, is

/Users/mariezimmy/CS2261/visualboyadvance-m.app

You can verify the directory location of the “visualboyadvance-m.app” on your machine by simply opening Finder, opening the CS2261 folder where you placed the “visualboyadvance-m.app”, and dragging the “visualboyadvance-m.app” icon into the terminal. The output in the terminal is the exact path to the “visualboyadvance-m.app”. The sequence of images below shows this process.

In my case, as stated before, the exact path is

/Users/mariezimmy/CS2261/visualboyadvance-m.app. Copy this exact path and paste it into your task.json, on line 9 in between “open” and “./Project.gba”. Make sure there is a space after “open” and before “./Project.gba”

The image below outlines what my task.json looks like. Your exact path on line 9 will be different!

Part 3: VSCode

Visual Studio Code is the text editor of choice for this class. We highly recommend you use this editor. If you do not already have VSCode, you can download it here: https://code.visualstudio.com/download

Open VSCode, and in the Welcome tab, under Start, select “Open Folder…”. Open the Lab00-Mac folder which has the Makefile, main.c, tasks.json, etc.

In the top toolbar, under Terminal, select Configure Tasks and then select “Create tasks.json file from template”.

Then, select others. You’ll see a new and different tasks.json exists under a .vscode folder. Replace the contents of this tasks.json file with the contents of the tasks.json file you edited earlier (i.e. copy and paste all of the contents of the tasks.json you edited into this new tasks.json file). Save and press cmd + shift + b. This should build your project.

This first compilation process will take some time because a Docker image is being downloaded from Dockerhub (don’t worry about the nitty gritty details of this). All subsequent builds will not take this long ( whew). In the terminal output in VSCode, you should see something like this for the very first time you build:

Once the build is complete, you should see something like the following pop up:

Submission Instructions

Zip up the entire sample project folder, including all source files, the Makefile, the Dockerfile, and everything produced during compilation ( including the .gba file). Submit this zip on Canvas.

Name your submission Lab00_FirstnameLastname, for example:“Lab00_MarieZimmerman.zip”.
