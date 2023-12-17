Summarize the project and what problem it was solving.

The project required the creation of a task scheduler that uses the temperature sensor to compare the ambient temperature to the set point temperature to determine if the heating system needs to be turned on or off. There are two buttons on the device that are used to adjust the temperature up or down. The task scheduler checks to see if the buttons are pressed every 200ms then it checks the ambient temperature every 500ms and determines if the heat was needed to be turned on or off. This is when the device reports the status using UART.

What did you do particularly well?

I was able to break this project down into sections, work on them individually, and then bring it all together to work as a functional program. This allowed me to make sure that each section of the code was working correctly and if there was anything wrong with that part of the code, I was able to research and fix it before I brought the code together. I feel that bringing it together gave me more control over the flow of the project. This made it easier to write and debug the code.

Where could you improve?

I feel that I could do better with UART. I would like to learn more about it to find a better understanding of UART. I was able to get my LEDs to work correctly but I would like a better understanding of it before I say that I am comfortable using it.

What tools and/or resources are you adding to your support network?

Before starting this class, I had zero experience with embedded coding, but I was able to learn a lot about it. I could work with some people that had a lot of experience with embedded systems and they were able to help me understand a lot of things that I was struggling with. 

What skills from this project will be particularly transferable to other projects and/or coursework?

Since I had no experience with embedded systems before this class all that I have learned will be transferable to my future career. There are a lot of positions for embedded systems engineers, which will give me a great opportunity to advance my career.

How did you make this project maintainable, readable, and adaptable?

I made this project maintainable by using variables that closely resemble the object they are controlling. I made this project readable by separating the functions and labeling them with comments to easily recognize them. I made this project adaptable by using a state machine that would allow me to add new functionality without having to change the existing code.
