## Steps tp follow while building petalinux project 
- run the settings.sh
- petalinux-create -t project -n <name_of_the_project> -s <Path_of_the_bsp_file.bsp>
- cd name_of_the_project
- petalinux-config --get-hw-description <path_to_xsa_file.xsa>
- petalinux-build
