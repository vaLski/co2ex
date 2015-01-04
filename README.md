co2ex
=====
co2ex is a basic tool that acts as a count down timer, and helps you as an reminder during your excercises to increase tollearnce to CO2 levels.

Safety first
============
This tool should be used ONLY by people fully aware with the A.I.D.A regulations and safety instructions and people that completed sucessfully at least the first level of A.I.D.A course.

Failed to comply with A.I.D.A safety regulations and instructions for static apnea training may result in serious health damage or DEATH.

You use this tool on your own risk. The author does not take any responsibilities about the consequences of using this tool.

While it helps the author it is not neccesarry that it will help you as well.

Use it on your own responsibility.

What is that
============
co2ex is a basic tool that acts as a count down timer, and helps you as an reminder during your excercises to increase tollearnce to CO2 levels.

It should be usefull to freedivers that wants to increase their apnea time while training their body to sustain higher level of CO2.

The following CO2 table principles are met by the tool:

- Make sure you know what is your maximum static apnea. Let us say that your comfortable maximal static apena is 180 seconds.
- Take 50% of the maximum (in this case 50% of 180 seconds = 90 seconds). This is the static apnea time for the whole table used by the program in other words, each apnea during the excercices should be 90 seconds
- Only the time to relax betwen each apneas is decreased with 15 seconds. See te example table below.
- You need to complete the whole table/program run. The idea behind is to excercise yourself and even it is a bit hard it should be managable/achievable to your body.
- If it is too hard for you to take/complete the whole program run and can't finish it, try to decrease the apnea time with 15 seconds to let's say 75 seconds.
- If it is too easy for you to complete the table, the load is not enough for your body and you should increase the apnea time with 10 seconds. Otherwise you are loosing the training effect.
- NEVER EVER hyperventilate during the pauses - if you do that the excercise becomes useless.
- NEVER EVER forget to quit out of each apnea with a propper recovery breathing.

Example training table
======================

Here is an example table that the program follows:

1. 90 seconds apnea, 105 seconds relax
2. 90 seconds apnea, 90  seconds relax
3. 90 seconds apnea, 75  seconds relax
4. 90 seconds apnea, 60  seconds relax
5. 90 seconds apnea, 45  seconds relax
6. 90 seconds apnea, 30  seconds relax
7. 90 seconds apnea, 15  seconds relax
8. 90 seconds apnea, 15  seconds relax
9. 90 seconds apnea,	 THE END

How to use it
=============

$ ./co2ex 
Use: ./co2ex comfortable_apnea_time [pause_decrease_offset] [draw_me_a_table]
		comfortable_apnea_time - Integer in seconds.
		relax_time_decrease_offset - Integer in seconds. Default 15.
		draw_me_a_table - String. If third argument is supplied, tool will simply draw the training table.
$ ./co2ex 90 15 draw_me_a_table
Apnea #1 - 90 seconds apnea, 105 seconds relax time.
Apnea #2 - 90 seconds apnea, 90 seconds relax time.
Apnea #3 - 90 seconds apnea, 75 seconds relax time.
Apnea #4 - 90 seconds apnea, 60 seconds relax time.
Apnea #5 - 90 seconds apnea, 45 seconds relax time.
Apnea #6 - 90 seconds apnea, 30 seconds relax time.
Apnea #7 - 90 seconds apnea, 15 seconds relax time.
Apnea #8 - 90 seconds apnea, 15 seconds relax time.
Apnea #9 - 90 seconds apnea, THE END.
$ 

Software Requirements
=====================

	bash
	espeak - for voice

COPYRIGHTS/LICENSE
==================

Whatever :)

exit 0
