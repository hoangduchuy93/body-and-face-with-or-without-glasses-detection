![image](https://user-images.githubusercontent.com/91864024/181544878-d0cf98ac-c9d9-42e3-bb40-6e946e5ccfee.png)

# Body and Face Detection (With/ Without Glasses)
## I. Outline
- Detecting human or part of body have become very popular in nowadays reseraches. Detecting human accurately in a visual surveillance has became a very promised filed that AI can find the most useful
- There are lots of application from the studies such as abnormal event detection, human gait characterization, congestion analysis, person identification, gender classification and fall detection for elderly people.
- In this project, we will detect body and face (with or without classes). The application for this project can be vary, such as count number of people on the street, count number of student wearing classes, ensure employee wearing safety glasses in industry, ..

## II. Project implementation
There are 2 small problems in this project:
- Full body detection
- Face detection (with or without glasses)

## III. Build model
### 1. Full body detection
**- Load image and convert to gray image:**

![image](https://user-images.githubusercontent.com/91864024/181559118-e0a28601-2fe2-49d9-ae51-db63b7035194.png)

**- Load cascade classifier training file for haarcascade, draw rectangle for body**

![image](https://user-images.githubusercontent.com/91864024/181560792-25879ee5-ebbe-4c10-92fd-56e11b9d6f37.png)

**- Save image**

![image](https://user-images.githubusercontent.com/91864024/181561884-34ec0663-aec4-4d7e-ac33-4df47a24d924.png)

### 2. Face detection
In this problem, there are 2 small requirements:
- Detect the eyes
- Detect the face

#### A. Detect the eyes
**- Load image with glasses, convert to gray image**

![image](https://user-images.githubusercontent.com/91864024/181564174-63cd58df-d938-45dd-8a44-13572ef0a6e1.png)

**- Load cascade classifier training file for haarcascade**

![image](https://user-images.githubusercontent.com/91864024/181564695-49d9755e-dce0-4c46-983e-69733526c4c1.png)

**- Draw rectangles for the eyes, convert to color image, save image**

![image](https://user-images.githubusercontent.com/91864024/181565126-62db2f8b-43f9-4397-a707-fc4582d7963e.png)

#### B. Detect the face after detecting the eyes
**- Load the eyes detection image from last step, convert to gray image**

![image](https://user-images.githubusercontent.com/91864024/181565595-941aba40-b509-4b62-bb13-c6af4458b5bd.png)

**- Load cascade classifier training file for haarcascade**

![image](https://user-images.githubusercontent.com/91864024/181565791-4c88f57c-f34c-4392-8f46-3e9279c7902e.png)

** Draw rectangle for the face, convert to color image, save image**

![image](https://user-images.githubusercontent.com/91864024/181566078-159e1754-e8a6-4627-9136-f6229fe28f5a.png)

#### C. Detect a human without glasses
**- Load image without glasses, convert to gray image**

![image](https://user-images.githubusercontent.com/91864024/181566435-ab2a5bf3-256b-427d-b4fc-2fb34e37701a.png)

**- Load cascade classifier training file for haarcascade**

![image](https://user-images.githubusercontent.com/91864024/181566676-9e7506d8-d28b-4a14-9f07-1dba87f4958e.png)

**- Draw rectangles for the eyes, convert to color image, save image**

![image](https://user-images.githubusercontent.com/91864024/181566822-34e8bbec-d442-4110-8c5a-e6f341c275df.png)

#### D. Detect the face after detecting the eyes
**- Load the eyes detection image from last step, convert to gray image**

![image](https://user-images.githubusercontent.com/91864024/181567080-af929404-c6df-41ee-947e-d0da8854e3fc.png)

**- Load cascade classifier training file for haarcascade**

![image](https://user-images.githubusercontent.com/91864024/181567251-d9d0afb8-a5f1-4d20-b0ba-5b77b0174572.png)

**- Draw rectangles for the eyes, convert to color image, save image**

![image](https://user-images.githubusercontent.com/91864024/181567390-24e2d640-db30-4a6a-b5bf-2e1fcd8591c6.png)
















