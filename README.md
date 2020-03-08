# wicu_data
pre-processing, EDA, modelling scripts on WICU data

# Folder Info: 
# # WICU_Singapore/WICU_COMBINED_OUTPUT: 
Contains: 
# 1. Activity_20s_window: 
Desc:contains Accelerometer Based data for different sessions. Sessions are 10 hour shift (7AM-7PM) on a particular day for which the data was taken. Each raw data file has data for Session #X collected from unique badge. B-XXXX.

Component Sheets:
    - summary: session number and badge id used for data collection.
    - t_BM_bm1: 20 sec interval data for overall body movement. Refer to A1. 
    - t_BM_activity1: 20 sec interval data for overall boy movement.
    - r_export_settings1
   
    
    1. Each of the excel sheet has 10 hours of 20 second interval data 
# 2. Location based data. 
    1. Detections_Prox_F2F
3. Audio Volume Data
    1. Audio_20s_window
