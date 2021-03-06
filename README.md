# KineticAnalysis
<i>*2019 note: this script was the first project I completed and was what propelled me to learn programming. As such, the code is not the cleanest, but it works. I may come back and rewrite most of it in the future.</i>

Python script for calculating and plotting kinetic analysis of battery materials. Script included is specifically for Lithium Manganese Oxide (LiMn2O4), though can be easily extended to other battery materials by changing the appropriate constants in script.

Script generates CV plots of batteries materials and shifts CVs accordingly to account for peak shifting from kinetic effects during different sweep rates. Script utilizes 0.2 mV/s, 0.5 mV/s, and 1 mV/s sweep rates with CV data collected using a BioLogic VSP potentiostat. From there, the script generates and plots the capacitive portion of the CVs and calculates the percent capacitance.

Example plot:

![Example 1mVs](https://user-images.githubusercontent.com/17757035/29955642-ef4cbce0-8e95-11e7-9016-22a4f4f16be1.PNG)

Final result with calculated capacitance and plot:

![Final result with calculated capacitance and plot](https://user-images.githubusercontent.com/17757035/29955645-ef54c5fc-8e95-11e7-8d5f-c1714f4d59ae.PNG)
