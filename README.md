# Carla_recording
This program record the trajectory of manual_control of Carla python API. It can also repeat the same trajectory.

make_Driving_record.py file will make the Driving_record.csv file. You can change the file name if you want.
Drive_by_Driving_record.py file will drive using the data of Driving_record.csv file.

In the first version, respawn point is not fixed. So it will start randomly on the map. It will be fixed in second verison

*version_1 Fixed*
-------

  Car will spawn in the same location with the recorded scenario. Also it will start with the same car

*version_2 Fixed*
--------

  Now we can use macros.sh to make a lot of data. Just change the number in the loop statement of macros.sh

    ./macros.sh
    
  It will only work in linux system.

  And in version_2 collision_data.csv will be made. It shows the surrounding car's location in (x,y,z) format.
