<<<<<<< HEAD
*This is a template repository for this organization. Start by replacing the placeholder for the project name with its actual title.*

# [Demonstration Project title]

## Summary
| Company Name | [Company](https://website.link) |
| :--- | :--- |
| Development Team Lead Name | [Dr. John Smith](https://profile.link) |
| Development Team Lead E-mail | [email@example.com](mailto:email@example.com) |
| Objectives of the Demonstration Project | ... |

### Each project has an alternative for documentation
1. Fill in the [description](#description) directly in the README below *OR*;
2. make a [custom agreement with the AIRE team](#custom-agreement-with-the-AIRE-team).

# Description
## Objectives of the Demonstration Project
*Please describe your project objectives in detail.*

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

## Activities and Results of the Demonstration Project
### Challenge
*Please describe challenge addressed (i.e, whether and how the initial challenge was changed during the project, for which investment the demonstration project was provided).*

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

### Data Sources
*Please describe which data was used for the technological solution.*  
- [Source 1],
- [Source 2],
- etc... .

### AI Technologies
*Please describe and justify the use of selected AI technologies.*
- [AI technology 1],
- [AI technology 2],
- etc... .

### Technological Results
*Please describe the results of testing and validating the technological solution.*

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

### Technical Architecture
*Please describe the technical architecture (e.g, presented graphically, where the technical solution integration with the existing system can also be seen).*
- [Component 1],
- [Component 2], 
- etc... .

![backend-architecture](https://github.com/ai-robotics-estonia/_project_template_/assets/15941300/6d405b21-3454-4bd3-9de5-d4daad7ac5b7)


### User Interface 
*Please describe the details about the user interface(i.e, how does the client 'see' the technical result, whether a separate user interface was developed, command line script was developed, was it validated as an experiment, can the results be seen in ERP or are they integrated into work process)*

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

### Future Potential of the Technical Solution
*Please describe the potential areas for future use of the technical solution.*
- [Use case 1],
- [Use case 2],
- etc... .

### Lessons Learned
*Please describe the lessons learned (i.e. assessment whether the technological solution actually solved the initial challenge).*

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

# Custom agreement with the AIRE team
*If you have a unique project or specific requirements that don't fit neatly into the Docker file or description template options, we welcome custom agreements with our AIRE team. This option allows flexibility in collaborating with us to ensure your project's needs are met effectively.*

*To explore this option, please contact our demonstration projects service manager via katre.eljas@taltech.ee with the subject line "Demonstration Project Custom Agreement Request - [Your Project Name]." In your email, briefly describe your project and your specific documentation or collaboration needs. Our team will promptly respond to initiate a conversation about tailoring a solution that aligns with your project goals.*
=======
**SMART BRACE UI PROTOTYPE DOCUMENTATION**

The aire-smart-corset-dashboard is a user interface prototype aimed at real-time monitoring and guidance of the patients using a smart scoliosis brace. The final purpose of this app is to support both patients and medical personnel during the scoliosis treatment process by providing both real-time data visualization and brace usage statistics.

The interface is in a demo state and constitutes only an interactable mock-up of the future final application.

**Software requirements for testing**

- Unity Hub.
- Unity, version 2021.3.3 f1.
- Required Unity modules for Android build.

**INSTALLATION**

Before cloning or downloading the repo make sure Unity is installed on your PC. To do so first install Unity Hub available at this [link](https://unity3d.com/get-unity/download). You might need to register first, and activate a free individual, Personal or Student,
license on the Unity website. More info about Unity licenses and usage are available [here](https://store.unity.com/#plans-individual).

After installing Unity Hub, locate the required Unity version (2021.3.3f1.) in the *Install* tab on the left. Alternatively, you can access it at this [page](https://unity3d.com/get-unity/download/archive) and press on the *Unity Hub* button to start the installation.

Before initiating the installation procedure, make sure you flag all the options related to the Android modules installation and include Android Built support with Android SDK & NDK Tools and OpenJDK.

<img src="readme-files/Install-Packages.png" height="150">

After installation, locate the project you cloned or downloaded on your PC from the Unity Hub *Open, Add project* *from disk* option.

<img src="readme-files/Open-from-disk.png" height="150">

After locating the repo folder on your PC the project will appear in the available projects in Unity Hub. Click on the project name to open it. This might take a few minutes.

![Open](readme-files/Open-project.png)


**PROJECT SCENES**

Unity game engine scenes are assets containing all or parts of the components and elements necessary for a specific application to run. These include interface components, 3D objects, scripts, audio and video sources, input sources, physics components etc. For more basics on the Unity features and UI please refer to the info provided [here](https://unity.com/learn/get-started).

There are a few scenes involved in the current application demo. The first set is constituted by the mobile user interface dashboard pages, including the graphical contents and navigation buttons.

- *AuthenticationScene*
- *BluetoothConnectionScene*
- *BreathingPatternScene*
- *HomeScreenScene*
- *StatisticsScene*
- *StrainPressureScene*

The second includes a 3D 'Digital Twin' visualization of the user avatar and corset, with some preliminary interactions and visualization toggles.

- *Smart Corset DT 0.1*

It is possible to open and access the scenes by navigating the project (*Project* tab in Unity) and open the *Scenes* folder.

**RUNNING ON EDITOR SIMULATOR**

To be able to visualize the editor application preview of the Mobile UI:

-   Open *AuthenticationScene*
-   Access the *Game* tab and switch to *Simulator* option

<img src="readme-files/Simulator.png" height="90">

-   Select the device you want to emulate in the drop-down menu

<img src="readme-files/Device.png" width="300">

-   Press the play button in the top center of the Unity UI
-   Interact with the UI by using the mouse to click

Follow the same steps to access the 3D corset visualization by opening the dedicated scene *Smart Corset DT 0.1.*

**BUILD**

Alternatively, it is possible to build the project in two different apps, install and test them on any android device. To be able to do this:

-   Access the *Build Settings* menu under *File*

-   Open each of the related scenes (mentioned above) and add them to the build by clicking on the *Add Open Scenes* button. Arrange the scenes in the correct order in the menu by clicking and dragging them. Make sure the necessary scenes are flagged so that they can be included in the build.

<img src="readme-files/Scenes-build.png" height="200">

-   Switch platform to Android build by clicking on the *Android* logo and pressing the *Switch Platform* on the bottom right of the menu.

-   Press *Build* button and wait until the .apk file is saved in the selected location on your PC.

-   Transfer and install the .apk file on your mobile device. You might need to grant permission to install applications from unknown sources on your mobile.

-   Open and test the application

Follow the same steps to build the 3D corset visualization app but include the *Smart Corset DT 0.1* scene only when setting up the build.
>>>>>>> smart-corset-dashboard/main
