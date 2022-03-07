
cd ${PROJECT_SOURCE_DIR}
e.g. cd /home/cw/code/LIN_ws/C3_Homework_code

mkdir build
cd build
cmake ..
make
./app/add_rir ./../data/audio.raw ./../data/res.raw
