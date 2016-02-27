# openocd
The place where I maintain Kinetis and Mac OSX fixes (until someone can get them into origin/master).

The openocd community are not much fun.  Thanks to the power of git, rather than deal with them, I can maintain Kinetis fixes here.  It's not ideal.  I suppose if they were easier to deal with, then someone could have already gotten Kinetis fixes into origin/master.  Who knows.

I started with a branch called kinetis-merge where I got the somewhat randomly introduced Freescale commits.  I got that to build and then I merged that to master. 

I have a lot going on these days, so I generally  only support the MCUs and platforms I need/use.  However, I will always try to be helpful if I can.  I may not be able to immediately respond, but I will try to make time to help.

To build this repo in Mac OSX you'll need to do the following:

./bootstrap
./configure --enable-cmsis-dap --disable-werror
make