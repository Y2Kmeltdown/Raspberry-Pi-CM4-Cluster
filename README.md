# Raspberry-Pi-CM4-Cluster
A repository detailing my efforts to make a raspberry pi cluster and the use cases for spiking neural networks.

This Repository is the beginning of my venture into developing a raspberry pi cluster to research spiking neural networks.

About me

I am a University Student about to finish my last year and I want to start a project to help learn programming skills specifically in the field I am most interested in, Neuromorphic engineering. I am completing my honours thesis with the International Centre of Neuromorphic Systems at Western Sydney University. Throughout my degree I have developed some programming skills mostly within MATLAB but most of my mechatronics degree is more related to control systems and robotics and computer aided design. In my thesis I developed an algorithm for accelerating time surface computation for use in event-based cameras. After getting a taste of this field I am extremely interested in pursuing a career in Neuromorphic engineering. I have always been interested in raspberry pis and now that I am finishing my degree and have some free time before I go on to do my masters in neuromorphic engineering I thought now would be a good opportunity to start a project that will help me learn both raspberry pis and neural networks.

What I know

Honestly I feel pretty under prepared for this project as I don't even know if what I want to achieve is possible. I have a good understanding of general programming through my time programming in MATLAB and brief moments programming arduinos and STM32s. I am not really sure how to effectively use Git or Github and hope this project will also help teach me this. I know basic python and understand I will need to learn python extensively to complete this project. I completed a sub major in computer aided design so I am familiar with designing in applications like Solidworks. I spent a year volunteering in the western sydney solar car team in my first year where I designed the PCB for the headlights and breaklights for the solar car. I learned how to use altium and some design ettiquette for circuits. I am unfamiliar with designing for high speed signals and designing around differential pairs and trace lengths and hope this project will help teach this. I have some networking knowledge from an elective unit in computer networking which I am sure will be useful in clustering

Aim of the project

The project aim is to design a raspberry pi super computer for simulating spiking neural networks. The project will consist of three general stages: 
Software, where I will learn how to cluster raspberry pis to perform tasks and what the best approach is as well as learn how to use tensorflow using a coral TPU for hardware acceleration. I intend on developing this project mostly using python but I am sure it will expand to other languages. Once I have a firm grasp on both cluster computing and tensorflow I want to combine them together and cluster compute across multiple raspberry pis utilising coral tpus. 
The next stage is Circuitry. To preface none of what I am doing here is for any neccessary reason I am purely doing this as a productive hobby to learn and practice stuff I am interested in. Anyway I intend on developing a Raspberry pi CM4 board with built in POE+ and a coral TPU system on a chip. I want to develop this board in Altium and to learn about routing PCIe lanes and designing BGA footprints among other things involved in the design process. I will hopefully develop an altium schematic and footprint library of all the components I use and will document the entire process such as component design, schematic design, PCB rules, PCB trace routing, PCB exporting, Soldering and troubleshooting. After all of this I will hopefully have working boards that efficiently utilise POE and can compute spiking neural networks.
Final stage is the simple stage. Developing a case or at the very least a mounting mechanism in Solidworks to hold everything together. I am very familiar with Solidworks but I may have to switch to other software like fusion 360 or inventor because I don't know how long I will have the student license for solidworks after I graduate. I haven't put too much thought into this part as it is quite far down the line of priorities and I figure I will croos that bridge when I get to it. I will try to document this process as much as the rest of the project.

Documenting the project

As I am quite new to Github and well personal projects, I am really unsure about how I will go about documenting stuff. I will likely try and make update posts as I find more material and content that I have found useful for the project or if I make any progress on the stages. I am not going to stick to any timed updates because I suffer from ADHD and the thought of sticking to a strict update schedule for this project will absolutely destroy my interest in it. I really hope I stick to this project and I have ordered some parts to start prototyping. I know no one is going to read this but if I make some decent progress and people end up finding this I hope you find it informative and useful. I suppose this will also be a great time capsule of myself for the future.




[UPDATE 1]
My first update to this project is that I have ordered 2 1GB CM4 lite modules 2 IO boards and 2 Coral M.2 TPUs today and I am waiting for them to arrive so I can start testing. I have no idea if I can even get them to work but I remain hopeful. In the mean time I will get started on researching tensorflow and cluster computing. I am going to start with reading through the documentation from coral https://coral.ai/docs/m2/get-started and also look at a tutorial I found on clustering raspberry pis in python https://pythonprogramming.net/build-supercomputer-raspberry-pi/. The project will start slow as I am in the middle of writing my thesis which is due on the 20th. 
