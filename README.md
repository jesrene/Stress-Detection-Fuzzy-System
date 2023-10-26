# Stress-Detection-Fuzzy-System


## YouTube Link

Watch demo of our system at:
https://youtu.be/pWY1dZkjLSI 


## System Overview
The stress detection fuzzy system was designed with the intention of detecting the stress levels of
individuals with the use of their heart rate (HR) and electrodermal activity (EDA) as parameters. In
line with SDG goal number 3, this system would be used to improve the health of high stress
individuals by suggesting activities that allay stress.
As mentioned previously, the system takes in two inputs from the user which are HR and EDA.
The system would then run the inputs provided into the fuzzy inference engines in order to process
the input data. Each of the parameters have their own fit vectors that would correspond to the
values “low”, “medium” and “high” depending on the values inputted. The fuzzy inferencing
engines would then give us the stress state based on the predefined rules.
The GUI of our fuzzy system design is designed with user intentions in mind. It incorporates
sliders for inputting HR and EDA data. We opted for sliders over text inputs to ensure users don't
input inappropriate values, such as zero for heart rate, and to prevent non-numeric data entry.
To present the output, we display the 'stress rating' linguistic variable's fit vectors and the resulting
output value, as depicted in the figure below. 

![image](https://github.com/jesrene/Stress-Detection-Fuzzy-System/assets/86104103/913dd460-b6d5-410c-913d-0790ed0719c4)

In addition to showing the user’s stress rating, a recommendation is also displayed, as shown
below.


![image](https://github.com/jesrene/Stress-Detection-Fuzzy-System/assets/86104103/9d9fe824-10a5-4045-9493-cb5947d02bec)


## Fit Vector

Heart Rate (0 to 160 BPM)

![image](https://github.com/jesrene/Stress-Detection-Fuzzy-System/assets/86104103/927a8de7-eda1-4e83-8cb5-25db10cf852a)

Electrodermal Data (0 to 16 µS)

![image](https://github.com/jesrene/Stress-Detection-Fuzzy-System/assets/86104103/15141ca1-b520-4df9-9575-5265f1525426)

Stress Level (1 to 5)

![image](https://github.com/jesrene/Stress-Detection-Fuzzy-System/assets/86104103/cebb5815-02ee-4aea-92d3-e1cbc559f038)


## Rules Definition 

The rules for this system are displayed in the following fuzzy association memory (FAM)
representation table: 

![image](https://github.com/jesrene/Stress-Detection-Fuzzy-System/assets/86104103/8e36a7fe-f9e8-4488-9b40-e0141e1297c7)


## Poster Design

![Poster - Stress Detection Fuzzy System](https://github.com/jesrene/Stress-Detection-Fuzzy-System/assets/86104103/2ca78f12-6d30-4599-b777-5168c7949435)
