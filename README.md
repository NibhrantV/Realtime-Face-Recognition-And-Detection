# Face Recognition Project using PyCharm

## Setup Instructions

1. **Install OpenCV:**
*pip install opencv-python*

2. **Create Data Directory:**
- Create a directory named "data" in your PyCharm project.
- Update `user_id` in `data_collection` for different person's faces.
  ```
  cd your_project_directory
  mkdir data
  ```

3. **Run Data Collection:**
*python data_collection.py*


4. **Install Dependencies:**
*pip install numpy*
*pip install pillow*


5. **Run Classifier:**
*python Classifier.py*


6. **Add Condition for New User:**
- In `Classifier.py`, create a new `if` condition for another user ID.
- Update the text for the person's identity (preferably the name) and user ID.

7. **Run Face Recognition:**
*python face_recognition.py*


Feel free to copy and paste these commands for a smooth setup of your face recognition project in PyCharm. Let me know if you need any further assistance!
