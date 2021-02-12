# Create an ssh key
In this section we will create an ssh key. 

## Step 1
Open up your terminal on your computer.

-On a mac: 
* open finder
<p align="left" >
<img alt="Open finder" width="200" src="ScreenFindTerminal1.png">
</p>

* go to applications

<p align="left" >
<img alt="Select Applications" width="600" src="ScreenFindTerminal2.png">
</p>

* open the utilities folder
* click on terminal
<p align="left" >
<img alt="Under the uitlity folder open terminal" width="600" src="ScreenFindTerminal3.png">
</p>

...or...

* hit <kbd>command &#8984;</kbd> + <kbd>space bar</kbd> to open spotlight search
* type in "terminal"

<p align="left" >
<img alt="Spotlight shortcut" width="600" src="Terminal-Spotlight_shortcut.png">
</p>

.... and Wa-Lah!

<sub><em><sup>*</sup>generally there isn't a shorcut to do this unless it's set up with in your keyboard shortcuts
</em></sub>

Here is an example of what your computer terminal looks like:<br>
<sub><em><sup>*</sup>this is not to be confused with your terminal in your editor but you could potentially use that instead</em></sub>

<p align="left">
<img alt="Terminal"  width="600" src="Terminal-Spotlight_shortcut.png">
</p>

## Step 2 - Create the ssh key (aka RSA key pairt)
Enter in the command line of your terminal
```bash
ssh-keygen
```

The above command will create what's known as RSA key pair represented in 2048-bit encryption. 

<sub><em><sup>*</sup>alternatively, you can enter `ssh-keygen -b 4096` in order to create a 4096-bit encryption for your key.</em></sub>

```
Expected Output
Generating public/private rsa key pair.
Enter file in which to save the key (/your_computer/.ssh/id_rsa):
```

This will give you the option of where you would like to save your ssh key, or if you hit enter, it will default to creating this folder `/your_computer/.ssh/id_rsa` (as expected in the Output) and store it there.

If you already have and ssh key that's been previously generated and you attempt to create a another (knowingly or unkowingly), then this will be the expected Output:

```
Expected Output
Generating public/private rsa key pair.
/computer/your_computer/.ssh/id_rsa already exists.
Overwrite (y/n)?
```
This will then give you the option to replace the old ssh key with the new one or create another ssh key entirely. 

<sub><em><sup>*</sup> This happened to me and I hit `y` because it's too difficult to keep track of too many ssh keys. However, you may need or want multiple ssh keys for each project and or service you are entering remotely via the command line</em></sub>

## Screenshots
Include logo/demo screenshot etc.

## Step 3
A short description of the motivation behind the creation and maintenance of the project. This should explain **why** the project exists.

## Step 4
A short description of the motivation behind the creation and maintenance of the project. This should explain **why** the project exists.

## Screenshots
Include logo/demo screenshot etc.



### Why use it?
If people like your project they’ll want to learn how they can use it. To do so include step by step guide to use your project.

### Background
Give proper credits. This could be a link to any repo which inspired you to build this project, any blogposts or links to people who contrbuted in this project. 

#### Anything else that seems useful

