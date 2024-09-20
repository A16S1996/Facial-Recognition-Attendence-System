# Facial-Recognition-Attendance-System
Facial Recognition Attendence System using Python  and OpenCv  

### Sourcerer
<img src="https://avatars.githubusercontent.com/u/84435079?v=4" height="50px" width="50px" alt=""/>

### Code Requirements
- Opencv(`pip install opencv-python`)
- Tkinter(Available in python)
- PIL (`pip install Pillow`)
- Pandas(`pip install pandas`)

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
- After training click on `Automatic Attendance` ,it can fill attendance by your face using our trained model (model will save in `TrainingImageLabel` )
- it will create `.csv` file of attendance according to time & subject.
- You can store data in database (install wampserver),change the DB name according to your in `AMS_Run.py`.
- `Manually Fill Attendance` Button in UI is for fill a manually attendance (without facce recognition),it's also create a `.csv` and store in a database.

### Screenshots

### Basic UI
<img src="https://raw.githubusercontent.com/A16S1996/Facial-Recognition-Attendence-System/refs/heads/main/Screenshot%20(120).png">

### When it Recognises me
<img src="https://raw.githubusercontent.com/A16S1996/Facial-Recognition-Attendence-System/refs/heads/main/Screenshot%20(124).png">

### While filling automatic attendance
<img src="https://raw.githubusercontent.com/A16S1996/Facial-Recognition-Attendence-System/refs/heads/main/Screenshot%20(122).png">


