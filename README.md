##  Attendance Management system using Face👦🏻👧 Recognition [![](https://img.shields.io/github/license/sourcerer-io/hall-of-fame.svg)](https://github.com/Spidy20/Attendace_management_system/blob/master/LICENSE)

### Sourcerer
<a href="https://sourcerer.io/spidy20"><img src="https://avatars2.githubusercontent.com/u/42056100?v=4" height="50px" width="50px" alt=""/></a>

### Code Requirements
- Opencv
- Tkinter(Available in python package)
- PIL 
- Pandas

### What steps you have to follow??
- Download my Repository 
- Create a `TrainingImage` folder in a project.
- Open a `AMS_Run.py` and change the all paths with your system path
- Run `AMS_Run.py`.

### Project Structure

- After run you need to give your face data to system so enter your ID and name in box than click on `Take Images` button.
- It will collect 200 images of your faces, it save a images in `TrainingImage` folder
- After that we need to train a model(for train a model click on `Train Image` button.
- It will take 5-10 minutes for training(for 10 person data).
- After training click on `Automatic Attendance` ,it can fill attendace by your face using our trained model (model will save in `TrainingImageLabel` )
- it will create `.csv` file of attendance according to time & subject.
- You can store data in database (install wampserver),change the DB name according to your in `AMS_Run.py`.
- `Manually Fill Attendace` Button in UI is for fill a manually attendance (without facce recognition),it's also create a `.csv` and store in a database.

### Screenshots

### Basic UI
<img src="https://github.com/Spidy20/Attendace_management_system/blob/master/Screenshot%20(43).png">
### When it's recognize me
<img src="https://github.com/Spidy20/Attendace_management_system/blob/master/Screenshot%20(41).png">
### When it's fill a attendance
<img src="https://github.com/Spidy20/Attendace_management_system/blob/master/Screenshot%20(42).png">
### Manually filling attendace UI
<img src="https://github.com/Spidy20/Attendace_management_system/blob/master/Screenshot%20(44).png">


### How it works? See:)

<img src="https://github.com/Spidy20/Attendace_management_system/blob/master/AMS.gif">

### Video demo

[Youtube](https://www.youtube.com/watch?v=dXViSRRydRs)


### Notes
- It will require high processing power(I have 8 GB RAM & 2 GB GC)
- If you think it will recognise person just like humans,than leave it ,its not possible.
- Noisy image can reduce your accuracy so quality of images matter.

## Just follow☝️ me and Star⭐ my repository 
