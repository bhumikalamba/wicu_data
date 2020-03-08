# wicu_data
pre-processing, EDA, modelling scripts on WICU data

# Contents
WICU_Singapore/WICU_COMBINED_OUTPUT: 
Contains: 
1. Activity_20s_window: 
* Desc:contains Accelerometer data colected for unique session and badges. Sessions are 10 hour shift (7AM-7PM) on a particular date. Each raw csv has data for Session #X collected from unique badge B-XXXX. 

Component Sheets:
* Summary: session number and badge id metadata.
* t_BM_bm1: 20 sec interval data for overall body movement. Refer to A1. 
* t_BM_activity1: 20 sec interval data for overall boy movement.
* r_export_settings1: other metadata

2. Detections_Prox_F2F
3. Audio_20s_window
4. Speech_Profile_Pitch
