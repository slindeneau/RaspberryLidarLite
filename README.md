# RaspberryLidarLite
Code library for initializing and reading from a LidarLite. 


How to build
gcc -c lidarLite.c
ar -cq liblidarLite.a lidarLite.o

How to link to & use
Include the extra library folder containing the lidarLite library using -L and then build using the -l lidarLite
