POSE ESTIMATION USING MEDIAPIPE FULL Documentation :- 

Problem statement :
	Write a robust algorithm to calculate successful rep count for knee bend exercise (Use mediapipe  pose model for this task)
	Add a holding timer limit of 8 sec
	Include feedback logic in your code, which should be triggered only when a person fails to stay in holding position till 8 sec.
	Feedback message - “Keep your knee bent”
	Run your code with provided video and upload the full recorded pose detected video in drive.


Exercise description -  
	Leg should be bent to start timer
	Slight inward bend is enough to start the timer. ( <140 deg)
	After a successful rep, the person has to stretch his/her leg straight.
	No restriction for back angle
	Consider leg closer to camera as exercised leg 

Solution:
	imported libs and essential dependencies (opencv and mediapipe using pip install)
	Created pose model using Mediapipe (POSE has 33 points of detection in a body)
	used function called calculate_angle to find location of each angle in frame (use of trignometry tan inverse)
	designed logic to show and count reps in 8 secs time period.

Instructions:
	use python jupyter notebook for platform.
	python3 programming langauge should be used.
	explicitly import video file into storage path of jupyter kernel or use a gdrive url for importing.
        used framesize as same as video
	confidence is set to 90% and can be manually implemented.

LINK FOR originial VIDEO :- https://drive.google.com/file/d/1Xpj9BICCmPqQraKq5JTTTkCx9F86K6uA/view?usp=sharing

LINK FOR result VIDEO :- https://drive.google.com/file/d/1yqOYcx267H7z5WOGthlP6e8qcgmcMaW-/view?usp=sharing
