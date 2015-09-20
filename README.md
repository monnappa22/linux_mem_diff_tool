# linux_mem_diff_tool
Script to perform Linux Memory Diff Analysis Using Volatility

Configurure the tool
=======================
Before running the scrip you need to configure it. open the script  with text editor and populate the variables python_path and vol_path with the path to the Python interpreter and path to the Volatility respectively. Now the script should be ready to run

Script Options
================
# python linux_mem_diff.py -h
Usage: linux_mem_diff.py -c <path to clean image> -i <path to infected image> -p <profile> [options]

Options:
  -h, --help            show this help message and exit
  -c CLEAN_MEM_IMAGE, --cleanimage=CLEAN_MEM_IMAGE
                        path to clean memory image
  -i INFECTED_MEM_IMAGE, --infectedimage=INFECTED_MEM_IMAGE
                        path to infected memory image
  -p MEM_IMAGE_PROFILE, --profile=MEM_IMAGE_PROFILE
                        profile for the memory images
  -o OUTPUT_FILENAME, --output=OUTPUT_FILENAME
                        path to the output filename
  -v, --verbose         perfoms verbose diff analysis (slow)
  

Details of the running the script can be found here: 
http://malware-unplugged.blogspot.in/2015/09/linux-memory-diff-analysis-using.html




