This is a simple flv format parser, which can output the info about audio tag, video tag and scriptdata tag.  

support to parse vp6/h263/h264/h265 vidoe encoder format  

All the flv files to test are located in the folder "res", and all the source codes are located in the "src" folder.

# How to compile?
Execute the "start_build.sh", then go to the folder "build", execute "make" command, then you can get one executable file named "flv_parser".

or  

mkdir build  
cd build  
cmake ../  
make


# How to use the flv_parser?
./flv_parser ../res/h264.flv 

# flv format  
https://rtmp.veriskope.com/pdf/video_file_format_spec_v10.pdf
