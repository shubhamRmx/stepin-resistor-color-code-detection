# introduntion
-Education is very vast, their countless formulas and especially in Engineering branch which is itself subdivided into many subjects/fields. Hence, it becomes very difficult to remember them all.
A resistor is one of the basic Electrical devices used in our day-to-day life and almost every Electronic circuit so it becomes necessary to calculate the resistance of a physical resistor on regular basis for an Engineer.
This project aims to reduce the burden or effort and save the time which was to be put to calculate and remember the formula to find the resistance value of a five-band physical resistor.
## 1. How does the resistor color code work?
Resistor esteems are frequently demonstrated with shading codes. Essentially all leaded resistors with a rating of up to one watt are set apart with shading groups. The coding is characterized in the global standard IEC 60062. This standard depicts the stamping codes for resistors and capacitors. It incorporates likewise mathematical codes, concerning models frequently utilized for SMD resistors. The shading code is given by a few groups. Together they indicate the obstruction esteem, the resistance, and in some cases the unwavering quality or disappointment rate. The quantity of groups differs from three to six. As a base, two groups show the opposition worth and one band fills in as a multiplier. The obstruction esteems are normalized, these qualities are called favored worth.
## 2. Resistor Color Code Chart
The chart below shows the resistance and tolerance for resistors. The table can also be used to determine color of the bands when the values are known.
![68747470733a2f2f6565706f7765722e636f6d2f75706c6f6164732f656475636174696f6e2f7265736973746f725f636f6c6f725f636f6465735f63686172742e706e67](https://user-images.githubusercontent.com/48181111/132511217-93b0a372-5c36-4f03-ac4d-8b09a4015b70.png)
##3. Tips for Reading Resistor Codes
The reading direction may not generally be clear. Here and there the expanded space between band 3 and 4 provides away the understanding guidance. Additionally, the primary band is normally the nearest to a lead. A gold or silver band (the resistance) is consistently the last band.
It is a decent practice to check the producer's documentation to make certain about the pre-owned coding framework. Surprisingly better is to gauge the obstruction with a multi-meter. At times this may even be the best way to sort out the opposition; for instance when the shading groups are singed off.
## 4. Five Band Resistor
Resistors with high quality have an additional band to show a third critical digit. In this way, the initial three groups demonstrate the critical digits, the fourth band is the increase factor and the fifth band addresses the resistance. There are special cases for this. For instance, here and there the additional band shows disappointment rate (military detail) or temperature coefficient (more seasoned or concentrated resistors). If it's not too much trouble, read the segment "Color code exception for more data.
## 5. Color Code Exception (NOT INCLUDED IN PROJECT)
Five band resistor with a 4th band of gold or silver :
Resistors with high quality have an additional band to show a third critical digit. In this way, the initial three groups demonstrate the critical digits, the fourth band is the increase factor and the fifth band addresses the resistance. There are special cases for this. For instance, here and there the additional band shows disappointment rate (military detail) or temperature coefficient (more seasoned or concentrated resistors). If it's not too much trouble, read the segment "Shading code special cases for more data.
## 6. Purpose and Benefits
Physical :
There are many clear benefits to utilizing a shading coding framework on electrical and electronic segments. The benefit of utilizing shaded rings or groups around a resistor's body is that they can be effortlessly seen and perused regardless of the position or direction of the resistor on board. These shaded groups can likewise be perused regardless of whether the body of the resistor is somewhat grimy or seriously consumed.
Program :
The implementation is done while aiming to reduce the effort and time required to calculate the resistance and provide a seamless experience.
# Cost and Features
![table](https://user-images.githubusercontent.com/48181111/132505384-63345b18-1b3c-45d6-89e7-98846bd9ae04.png)
# Defining Our System
Assumptions :
User have read the resistance color table mentioned in Research part.
User understands and is able to enter color band as asked in program.
The program is limited to five band resistors only.
The exception in five band register discussed in Color Code Exception part of Research is not supported by program.
## Flow Chart :
![Flow chart 1](https://user-images.githubusercontent.com/48181111/132505366-fa2a3576-6870-4a54-9352-5346223eb653.png)
1. INPUT: Take input of 5 color bands from user
2. FindColor: Function which will further call UpperToLower and CompareColor function and will return address of found colors
3. UpperToLower: Function which will convert all uppercase char in a string to lowercase
4. CompareColor: Function which will check if the inpput is invalid or not
5. If error is found Jump to step number '8' else pass value to UnitFinder
6. Get tolerance for respective input
7. Combine tolerance and resistance together and print them
8. Ask the user if he want to start over again
9. If user enters 'Y' then go to step '1' else end the program

## SWOT ANALYSIS :
![SWOT L](https://user-images.githubusercontent.com/48181111/132505379-f59a5139-ba93-42d9-93b7-db7b3e41e66b.png)
# 4W's and 1'H
## Who:
Engineers
Technicians
Element and Circuit Manufacturers
## What:
Human error
Lot of time consumption
Tiredness after multiple calculation
## When:
While Manufacturing
While Diagnosing
During research
## Where:
In Industries
In Circuits
In labs
## How:
Manually calculating the resistance of many resistor by band method continously leads to error, tierdness and waste of time

[Readme.md](https://github.com/shubhamRmx/stepin-resistor-color-code-detection/files/7128632/Readme.md)
