1. Summarize the project and what problem it was solving.

The main project for this course was building a smart thermostat using a Raspberry Pi and various hardware components. The thermostat could monitor room temperature, display information on an LCD screen, switch between heating and cooling modes, and allow the user to adjust the temperature set point using buttons. The project solved the problem of creating a basic embedded control system that combines hardware and software to automate temperature management. It also demonstrated how embedded systems are used in real-world devices that people interact with every day.

2. What did you do particularly well?

I think I did a good job integrating the hardware and software into a complete working system. I was able to successfully connect the buttons, LEDs, LCD display, and temperature sensor while implementing a state machine to control the thermostat’s operation. I also spent time testing each feature individually before combining everything together, which helped me identify and fix issues such as the mode button not cycling correctly and ensuring the heating and cooling indicators behaved as expected.

3. What would you improve?

If I were to continue improving this project, I would make the thermostat more feature-rich and user-friendly. I would add programmable schedules, Wi-Fi connectivity, and the ability to control the thermostat remotely through a mobile app or web interface. I would also improve the user interface by creating a menu system on the LCD display and adding better error handling for sensor failures or unexpected hardware issues.

4. What tools and/or resources are you adding to your support network?

Throughout this course I became much more comfortable using the Raspberry Pi, Python libraries such as gpiozero, and Visual Studio Code for remote development over SSH. I also learned the value of using official documentation, hardware datasheets, and online programming resources when troubleshooting problems. These are tools and resources I plan to continue using as I work on future embedded systems projects.

5. What skills from this project will be particularly transferable to other projects and/or course work?

This project strengthened my skills in Python programming, debugging, hardware integration, and designing state machines. I also gained experience testing software incrementally instead of trying to build everything at once. These skills will transfer well to future embedded systems projects, software development, and even my current work in the HVAC industry, where automation and electronic controls are becoming increasingly common.

6. How did you make this project maintainable, readable, and adaptable?

I made the project maintainable by separating the different hardware components into their own classes and using a state machine to organize the thermostat’s behavior. Giving functions descriptive names and keeping related code together made the program easier to read and understand. This modular design also makes the project adaptable because new features, such as additional sensors, humidity control, or remote monitoring, could be added without significantly changing the existing code.
