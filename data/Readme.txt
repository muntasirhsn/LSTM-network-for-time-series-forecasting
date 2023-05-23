This folder contains 16 CSV files. Data description of each file is:

---------------------------------------------------------------------------------------------------------------------------
1. acad_build.csv:  This file contains the energy consumption data of Academic building.

2. boys_hostel_ups.csv:  This file contains the energy consumption data of backup supply to boys dormitory. Since, dormitories have both mains and UPS supply so separate meters are used to measure each type.

3. boys_hostel_mains.csv:  This file contains the energy consumption data of mains supply to boys dormitory.

4. girls_hostel_ups.csv:  This file contains the energy consumption data of backup supply to girls dormitory. 

5. girls_hostel_mains.csv:  This file contains the energy consumption data of mains supply to girls dormitory.

6. library_build_mains.csv:  This file contains the energy consumption data of Library building on campus. 

7. mess_build_mains.csv:  This file contains the energy consumption data of Dining building.

8. lecture_build_mains.csv:  This file contains the energy consumption data of Lecture building. 

9. facilities_build_mains.csv: This file contains the energy consumption data of Facilities building. 

10-12. transformer_1.csv, transformer_2.csv, transformer_3.csv: We have three transformers which supply electricity to whole campus. Each of these files contain energy parameters measured at these transformers

13. all_buildings_power.csv: This file contains only power consumption data of all the buildings.

14. all_transformer_power.csv: This file contains the power consumption data of all the three transformers.

15-16. data_present_status_buildings.csv, data_present_status_transformers.csv: These two CSVs show which data is present. 1 means data present and 0 means missing

---------------------------------------------------------------------------------------------------------------------------
Further details:
___________________________________________________________________________________________________________________________
1. Please refer to paper for further building details. Each file contains different energy parameters. The timestamp provided is in UNIX format.  While converting timestamps to Human readable format, mention timezone as "Asia/Kolkata" and set offset as +5:30 hours. 
2. The power column in different files is in terms of watts.
3. If you are using Python or R for data analysis, then use following readily available scritps for reading data
   Python: https://github.com/i-blend/i-blend.github.io/blob/master/py_scripts/read_energy_occupancy.py
    R: https://github.com/i-blend/i-blend.github.io/blob/master/r_scripts/read_energy_occupancy.R
---------------------------------------------------------------------------------------------------------------------------

For any doubts, mail me at: haroonr@iiitd.ac.in or haroon.it@gmail.com

---------------------------------------------------------------------------------------------------------------------------








