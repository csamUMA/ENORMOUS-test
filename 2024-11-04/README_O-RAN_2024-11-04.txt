The example 24h datasets with comma separated values on O-RAN energy consumption contain measurements from the 4th of November 2024. The datasets contain raw 1/s measurement data from Carlo Gavazzi EM111 energy analyzer devices and the measurement parameters include the timestamp, current (A), frequency (Hz), power factor (PF), voltage (V), power (W), and cumulative power consumption (kWH). There is also a fixed database name in the beginning of each row and measurement point ID in the end of each row (this information is of no value and can be discarded in the post-processing).

The data in different .csv files are collected from the following network components depicted in the measurement setup .pptx:

    - O-RAN_CU_server_2024-11-04.csv => Contains the energy measurements for a dedicated HW server running the Central Unit (CU) with 7.2x functional split, RAN Intelligent Controller (RIC), and Open5GS software.

    - O-RAN_DU_server_2024-11-04.csv => Contains the energy measurements for a dedicated HW server running the Distributed Unit (DU) software with 7.2x functional split.

    - O-RAN_indoor_RU_2024-11-04.csv => Contains the energy measurements for a Benetel RAN650 Radio Unit (RU) operating at the n77 frequency band and 100 MHz bandwidth.

All measurement results contain the idle state energy consumption of the O-RAN components listed above with some fluctuation in the values caused by site resets triggered in the system during configuration changes. Unfortunately, the datasets do not yet contain energy consumption results for different network loads or network KPIs (coming next).