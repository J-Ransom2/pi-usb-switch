- Setup Remote Command Acceptance
	- Set optional replies
- Setup Repo
- Setup README file
- Move Functions into a separate "Modules" file
- Move other variables into the "db.py" file
- Get current working directory using os.getcwd() of os module
- Create a setup file
	Asks for the following:
		- Which GPIO pin are you using for this switch? [8]
		- How many computers/devices can you hub connect to? [4]
		- Please enter a nickname for each port, separated by a comma(,):
		- Which port on the hub is the Pi connected to?
		- During autocalibration, how long should the program wait to see if the switch is connected to the Pi? [5]
		- What is the ID of your switch (This can be found by using 'lsusb' in terminal while the switch is plugged in)?
- Setup a "Change Nicknames" file/module
- Make wiring diagram
- Setup smart assistant integration