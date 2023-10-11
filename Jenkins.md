
## Creating a first job
Creating new job
Click New Item
Enter a suitable name: wafa-first-job
Scroll down and click OK
Write a description (can be anything suitable)
Select Discard old builds
Scroll down to Build and write commands:

`whoami
uname -a` 

# The above command will show you which linux terminal you are in 

click Save


## Linking 2 jobs together
click on the job
On left hand navigation plane, click Configure
Scroll down to Post-build Actions
Select Build Other Project
Find the job you want to connect to
Select Trigger only if build is stable
click Save