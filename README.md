<div align="center">
  <div id="user-content-toc">
    <ul>
      <summary><h1 style="display: inline-block;">KYC-Streamline</h1></summary>
    </ul>
  </div>
  
  <p>KYC system</p>
    <a href="https://kyc-frontend-c55789bd2cfd.herokuapp.com/" target="_blank">Live Preview</a>
    🦷
    <a href="https://github.com/Hamagistral/TeethSeg/issues" target="_blank">Request Feature</a>
</div>
<br>

## 📝 Table of Contents

1. [ Project Overview ](#introduction)
2. [ Key Features ](#features)
3. [ Project Architecture ](#arch)
4. [ Usage ](#usage)
5. [ Team ](#team)
6. [ Contact ](#contact)

<a name="introduction"></a>
## 🔬 Project Overview

**KYC Verifier** is an advanced system designed to enhance security and user verification through a streamlined process. Developed as a part of a summer internship project In ** Devtospace ** , this system integrates several cutting-edge technologies to ensure efficient and reliable user authentication. The KYC Verifier system simplifies the verification of users in various applications, providing a robust solution for managing and validating user identities.

### 🔌 Key Features

- **Streamlined User Verification:** Organization admins can manage and initiate user verification directly from a dedicated admin panel. This centralized approach simplifies the process and ensures efficient management of user verification tasks.

- **Liveness Detection:** Users receive a verification email and are redirected to the application to begin the verification process. They complete a liveness detection step by performing specific movements—turning left, turning right, and smiling—via webcam. Successful completion of these movements triggers the capture of a screenshot for further processing.

- **Live Selfie Comparison:** Following the liveness detection, users take a live selfie, which is compared to the previously captured screenshot. This step ensures that the user undergoing verification matches the person in the screenshot.

- **Document Scanning and Verification:** Users scan their identity card or residence permit directly within the app. The system extracts information and the user’s image from the scanned document, verifies the extracted details against existing records, and checks if the document’s image matches the live selfie. Successful verification grants access to services, while unsuccessful attempts require users to request a new verification link if the original one expires.

- **User-Friendly Interface:** The application’s frontend is designed with user experience in mind, providing an intuitive and accessible platform for users to complete the verification process. Built using modern web technologies, the interface ensures ease of use and smooth navigation.

- **Seamless Cloud Integration:** The backend infrastructure is hosted on AWS Cloud, leveraging services such as Amazon S3 for storage and EC2 for computation. This architecture ensures scalability, reliability, and high availability, making the system robust and responsive.

- **Data Security and Privacy:** The KYC Verifier system prioritizes data security and privacy, adhering to industry standards and regulations. This focus is crucial for handling sensitive personal and identification data, ensuring that user information is securely managed and protected.


The KYC Verifier system provides a comprehensive and user-friendly solution for verifying user identities, ensuring security, and enhancing the overall user experience. Its integration of modern technologies and streamlined process makes it an invaluable tool for organizations requiring robust user authentication.

<a name="arch"></a>
## 📝 Project Architecture

### ⚙️ Back End

![architecture-backend](https://github.com/Hamagistral/TeethSeg/assets/66017329/3eddbe6e-1afb-4a52-8128-006367c0d670)

### 🎨 Front End

![frontendarchitecture](https://github.com/Hamagistral/TeethSeg/assets/66017329/2fb117b5-8dc9-4ac6-a9f0-7f7a2a15e122)

For more see the [front end branch](https://github.com/Hamagistral/TeethSeg/tree/frontend).

### 🛠️ Technologies Used

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-%23000000.svg?style=for-the-badge&logo=opencv&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-%23000000.svg?style=for-the-badge&logo=flask&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%2347A248.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![MediaPipe](https://img.shields.io/badge/MediaPipe-%2347A248.svg?style=for-the-badge&logo=mediapipe&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Git](https://img.shields.io/badge/Git-%23F05032.svg?style=for-the-badge&logo=git&logoColor=white)
![Heroku](https://img.shields.io/badge/Heroku-%23430098.svg?style=for-the-badge&logo=heroku&logoColor=white)

![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Bootstrap](https://img.shields.io/badge/Bootstrap-%23563D7C.svg?style=for-the-badge&logo=bootstrap&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-%232F6C8F.svg?style=for-the-badge&logo=json-web-tokens&logoColor=white)
![Git](https://img.shields.io/badge/Git-%23F05032.svg?style=for-the-badge&logo=git&logoColor=white)
![Heroku](https://img.shields.io/badge/Heroku-%23430098.svg?style=for-the-badge&logo=heroku&logoColor=white)

<a name="usage"></a>
## 💻 Usage

1. Open the [KYC Verification System](https://kyc-frontend-c55789bd2cfd.herokuapp.com/) web application.
2. Sign In to your account.
3. Navigate to the "Start Verification" page.
4. You will receive a verification email with a link to initiate the process. Click the link to start the verification.
5. Complete the liveness detection by performing specific movements (turn left, turn right, smile) via your webcam. If all movements are successfully achieved, a screenshot will be captured.
6. Take a live selfie when prompted. This image will be compared to the captured screenshot.
7. If the images match, proceed to scan your identity card or residence permit directly within the app. However, if you did not access the app via the link sent by an admin or do not belong to the organization, the verification will fail, and you will not be able to proceed.
8. If verification is successful, you will gain access to the services. If not, you must request a new verification link from the organization if the original one expires.
<a name="team"></a>
## 👥 Team

![image](https://github.com/Hamagistral/TeethSeg/assets/66017329/3608dd52-6d3f-4f88-8da8-f3592bc7d42e)

<a name="contact"></a>
## 📨 Contact Me

[LinkedIn](https://www.linkedin.com/in/ibtissam-ech-chaibi/) •
[Website](https://ibtissamportfolio.netlify.app/) •
[Gmail](hamza.echchaibi@gmail.com)
