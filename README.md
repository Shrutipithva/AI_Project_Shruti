# AI_Project_Shruti

Diet Suggestion

This is my AI Project where from the image of a person BMI is calculated based on the height and weight of the person. We first detect the person and bassed on the bounding box co ordinates we extract the foreground using the grabcut algorithm. We convert the image to a binary image. Based on the number of white pixels we consider it to be weight, based on the euclidean distance between the top most white pixel and the bottom most white pixel we consider the height. Then according to the bmi value we give the diet plan for under weight, normal weight, overweight, Obesity level 1,2,3 persons.

https://www.youtube.com/watch?v=P0tiEnF76UQ&ab_channel=ShrutiPithva
