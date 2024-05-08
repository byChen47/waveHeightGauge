# waveHeightGauge
这个主要是教大家怎么在自定义的波浪求解器中使用wave2foam的波高仪对波高进行监测
# wave2foam waveHeightGauge
This method mainly teaches you how to use wave2foam's wave height meter to monitor wave height in a custom wave solver.
![image](https://github.com/byChen47/waveHeightGauge/blob/main/wave2foam%20waveGuages.png)  
#first  
将你的求解器复制到wave2Foam的求解器中waves2Foam/applications/solvers/solvers2206_PLUS  
#first  
copy you solve to wave2foam  /waves2Foam/applications/solvers/solvers2206_PLUS  
#second  
在你自己的求解器编译文件Make/Options的EXE_INC中添加wave2foam关于监测波高的程序  
#second  
add the wave2foam wave gauge program in you self solver Make/Options  EXE_INC  
#third  
在你自己的求解器编译文件Make/Options的EXE_LIBS中添加wave2foam关于监测波高的程序  
#third  
add the wave2foam wave gauge program in you self solver Make/Options  EXE_LIBS  
#hope this can help you  
#chen  
