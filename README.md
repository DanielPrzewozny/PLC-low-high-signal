# PLC program for controlling the time of low and high signal

LAD language program. The program checks the signal [Trigger_1]. Each rising and falling edge of the signal is saved in the database with the current time stamp and the time of the previous state. The database holds 50
records. Each change of state results in writing to the database in the next position. In case of saving the last record, the [Database_Full] blinking is turned on.
![ZadProg](https://user-images.githubusercontent.com/34861787/222790971-47673df2-e594-46f8-ab41-7e6f023f1b6d.jpg)
