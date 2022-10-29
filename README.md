# rapid-covid-test-detection
covid test detection using OpenCV

Your technical assessment will be as below.

Theme: COVID-19 Rapid Test Kit detection




Brief:
You are required to detect any COVID-19 Rapid Test Kit (RTK) in any given images.
On detection, you are required to draw line/box on the RTK to indicate the boundaries that your algorithm has detected.
Additionally, detect and draw line/box on the sample hole on the RTK and the result strip area.
For advanced challenges, you may choose to detect if the result is Positive or Negative.

Others:
There are no restrictions in usage of any libraries, framework, algorithm or programming languages to achieve to goal.
You may choose one RTK brand as a sample for detection. Also list out your assumptions to simplify your case (e.g. clear image in well lit room).
Training is not recommended for this assessment.

The bounding box size may not need to be exactly what the sample image shown, but to illustrate the idea of your program ability to detect such things.

Comment : 

There are 3 experiment done in this assesment :
1. detecting negative : detect negative in image that have both result (negative and positive). template matching
2. detecting red: detecting red to identify the result. improvement to algorithm : if detect 2 reds : positive. 1 red: negative. (need to add)
3. detecting shape : real-time shape detect. details on readme file (including youtube link for result video)
