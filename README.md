# HuskyLens Integration

This readme file provides instructions for integrating the HuskyLens vision sensor into your projects.

## Introduction

HuskyLens is a smart vision sensor that integrates AI technology for object recognition, tracking, and detection. It is commonly used in robotics, IoT, and AI projects to add vision capabilities to devices.

![1](https://github.com/ItsRawanMoha/HUSKYLENS/assets/156599594/c7fb11e5-273a-4510-b021-41be591f2b35)


## How it Works

HuskyLens uses a combination of machine learning algorithms and image processing techniques to analyze visual input and detect objects, faces, colors, and more. It communicates with microcontrollers or single-board computers via UART, I2C, or SPI interfaces, providing real-time vision data for further processing.

![image](https://github.com/ItsRawanMoha/HUSKYLENS/assets/156599594/0339ee3e-ffdc-4604-9483-56d0d0ea1f2f)

## Resource

- DFROBOT: https://wiki.dfrobot.com/HUSKYLENS_V1.0_SKU_SEN0305_SEN0336#target_0 


## Getting Started

To get started with HuskyLens:

1. Familiarize yourself with the HuskyLens hardware and specifications.
2. Choose a compatible microcontroller or single-board computer to interface with HuskyLens.
3. Install any necessary libraries or drivers for communicating with HuskyLens.
4. Connect HuskyLens to your microcontroller or single-board computer according to the documentation.
5. Power on the system and initialize communication with HuskyLens.

![97c0591d3821b7e31b0a57c39f3f08b1](https://github.com/ItsRawanMoha/HUSKYLENS/assets/156599594/20c66e26-db47-4186-8d4a-68b03805ab4e)

![4b3186c2cee314643df303c6ee97cbe6](https://github.com/ItsRawanMoha/HUSKYLENS/assets/156599594/f95e64ea-398b-4975-89d5-a828d9955040)

## Steps

Follow these steps to integrate HuskyLens into your project:

1. Run the HuskyLens 7 built-in functions: face recognition, object tracking, object recognition, line tracking, color recognition, tag recognition and object classification
2. Initialize communication with HuskyLens using the chosen interface (UART, I2C, or SPI).
3. Configure HuskyLens settings such as object detection mode, detection range, and output format.
4. Capture images or video frames using HuskyLens and process the visual data for your application.
5. Implement logic to interpret HuskyLens output and perform actions based on detected objects or patterns.

![image](https://github.com/ItsRawanMoha/HUSKYLENS/assets/156599594/d60348a2-3e75-44e6-87d6-3ea31e6bb63c)
![image](https://github.com/ItsRawanMoha/HUSKYLENS/assets/156599594/ed127a0e-770a-4618-90c0-1288e59ac0a5)


HuskyLens: is a smart vision sensor developed by DFRobot, designed for various applications including robotics, IoT (Internet of Things), and computer vision projects. It integrates advanced machine vision algorithms and powerful hardware components to enable real-time object detection, recognition, and tracking.

![image](https://github.com/ItsRawanMoha/HUSKYLENS/assets/156599594/1d8c42d5-05e6-4e20-9810-2285c6d25448)
### HuskyLens components
![image](https://github.com/ItsRawanMoha/HUSKYLENS/assets/156599594/238ea65f-0a08-4f09-abe2-6ab66c60cf0b)

Run the HuskyLens 7 built-in functions:
-	Face recognition: This function can detect any face contour, recognize and track the learned face.
 ![1_converted](https://github.com/ItsRawanMoha/HUSKYLENS/assets/156599594/151426b8-de26-4c4a-90af-93a7918728d0) ![image](https://github.com/ItsRawanMoha/HUSKYLENS/assets/156599594/883f0395-063e-4954-b08f-864d60e5f83c)

-	Object tracking: This function can learn and track a specified object. Only one object can be tracked, and multiple objects are not supported.

 	![image](https://github.com/ItsRawanMoha/HUSKYLENS/assets/156599594/595ab2f6-4302-4733-bfac-34462ac71fba)

-	Object recognition: This function can recognize what it is and track it.
  ![WhatsApp Image 2024-02-12 at 3 41 02 PM](https://github.com/ItsRawanMoha/HUSKYLENS/assets/156599594/b5cbc3ba-ce7c-4615-bcbf-9a79734af76b)
  ![WhatsApp Image 2024-02-12 at 3 43 46 PM](https://github.com/ItsRawanMoha/HUSKYLENS/assets/156599594/b753e514-9a6f-464d-8708-43cd7ecaa27e)

HuskyLens can recognize 20 built-in objects. They are aeroplane, bicycle, bird, boat, bottle, bus, car, cat, chair, cow, dining-able, dog, horse, motorbike, person, potted lant, sheep, sofa, train, TV.

-	Line tracking: This function can track specified color lines and make path predictions. The default setting is to track only one-color line.
  ![WhatsApp Image 2024-02-12 at 3 57 19 PM](https://github.com/ItsRawanMoha/HUSKYLENS/assets/156599594/07828912-b38a-4b62-b59d-005960ac4715)

-	Color recognition: This function can learn, recognize, and track the specified color.
  ![WhatsApp Image 2024-02-12 at 4 07 13 PM](https://github.com/ItsRawanMoha/HUSKYLENS/assets/156599594/922d62b2-cc5a-4ecd-ae0d-83511185de6d)
 	![WhatsApp%20Video%202024-02-12%20at%204 25 00%20PM_converted](https://github.com/ItsRawanMoha/HUSKYLENS/assets/156599594/06a96ad8-f360-481b-a0c6-d18a86470ce9)

-	Tag recognition: When Huskylens detects the tag, the tag will be automatically selected by the white frame on the screen.
  ![WhatsApp Image 2024-02-12 at 4 31 24 PM](https://github.com/ItsRawanMoha/HUSKYLENS/assets/156599594/a21c4d3d-a77a-46da-b75a-1f10ae2baef5)

-	Object classification: This function can learn multiple photos of different objects, and then use the built-in machine learning algorithm for training.

 	![image](https://github.com/ItsRawanMoha/HUSKYLENS/assets/156599594/9407ff50-c767-48ef-914f-dd3dc4e8af38) ![image](https://github.com/ItsRawanMoha/HUSKYLENS/assets/156599594/5424eeb4-1de7-4712-a235-41d59a2b75d0)
  ![WhatsApp%20Video%202024-02-12%20at%204 37 20%20PM_converted](https://github.com/ItsRawanMoha/HUSKYLENS/assets/156599594/c3579e2f-639a-453a-adf2-3ddb6288aeab)
 	

## Communication protocols: UART & I2C

![image](https://github.com/ItsRawanMoha/HUSKYLENS/assets/156599594/46c5786d-643e-4c77-be38-d6b3ef93ba01)

Huskylens with arduino

![image](https://github.com/ItsRawanMoha/HUSKYLENS/assets/156599594/1479df97-5393-4adb-b74c-2912a4932c47)

First we need to install the library for Huskylens on Arduino IDE.

![image](https://github.com/ItsRawanMoha/HUSKYLENS/assets/156599594/735e8d4c-c646-4487-87ce-9f67999c0986)

![image](https://github.com/ItsRawanMoha/HUSKYLENS/assets/156599594/4ef35be3-7160-4acd-b739-1d49a07f62ec) ![image](https://github.com/ItsRawanMoha/HUSKYLENS/assets/156599594/0102c967-0361-4929-8f4c-a3dda3744df7)


### As we can see the UART and I2C connections.

1-	UART communication protocol.

### HuskyLens UART connection with LEDs

![WhatsApp Image 2024-03-17 at 1 20 47 AM (1)](https://github.com/ItsRawanMoha/HUSKYLENS/assets/156599594/153f07af-aa84-4532-aa99-a3f40aa2b747)


### HuskyLens UART code 

![GETStartedCOde](https://github.com/ItsRawanMoha/HUSKYLENS/assets/156599594/d2d3b957-6ed8-485c-b342-47cfb717c659)

![WhatsApp%20Video%202024-03-18%20at%202 48 49%20PM_converted](https://github.com/ItsRawanMoha/HUSKYLENS/assets/156599594/ccc0964e-b2b4-4fda-9b27-32f1b00919e7)


### HuskyLens with LEDs

![WhatsApp%20Video%202024-03-18%20at%203 11 54%20PM_converted](https://github.com/ItsRawanMoha/HUSKYLENS/assets/156599594/a617acba-feab-42b1-ad43-86bbf85040ba)


2-	I2C communication protocol 

### HuskyLens I2C connection with LEDs

![WhatsApp Image 2024-03-17 at 1 20 47 AM (3)](https://github.com/ItsRawanMoha/HUSKYLENS/assets/156599594/a9dac9b0-5a7a-4226-99ef-87bf135b40b4)


### HuskyLens I2C code 

![I2CwithLEDHusky](https://github.com/ItsRawanMoha/HUSKYLENS/assets/156599594/23991686-5ed1-431e-9b60-99b046a8eaa1)

![WhatsApp%20Video%202024-03-18%20at%202 48 50%20PM_converted](https://github.com/ItsRawanMoha/HUSKYLENS/assets/156599594/1acd5811-899d-4000-961d-7903e455769d)


- NOTE: HuskyLens with LEDs (ID0 = Green, ID1 = Red, and ID2 = Yellow)!
- You can see the code as an attachment in the file section above.


## Conclusion

Integrating HuskyLens into your projects enhances their capabilities with AI-powered vision sensing. By leveraging HuskyLens' object recognition and detection features, you can create intelligent systems for robotics, IoT, and AI applications.
