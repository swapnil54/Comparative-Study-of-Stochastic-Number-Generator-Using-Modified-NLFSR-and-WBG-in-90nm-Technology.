# Comparative-Study-of-Stochastic-Number-Generator-Using-Modified-NLFSR-and-WBG-in-90nm-Technology.
we created Stochastic number generator using modified NLFSR and WBG. instead of WBG, you can also use comparator as PCC but compromising power, delay and more area (for layout). we plan to create a 16bit stochastic number generatort

we have used cadence virtuoso (gpdk90). have not done the layout fully, in sha allah will complete the layout whole for 16bit as we have planned.
i will include some files from and out of cadence which may also help you create one. 

while creating NLFSR and modified NLFSR, you might want to take special care checking the states that comes from the NLFSR. the states should be circular, meaning keep repeating over clock sequence changes. 
also we have used a positive edge D flipflop (that might create confusion later, so stating for clarification)

have also added a report in IEEE conference paper format for furthermore clarification. 

have added my cadence files, i hope you can find those for they are saved by their proper name. 
if you face any problem, please do let me know. 

good luck, have fun with vlsi
