# waveHeightGauge
这个主要是教大家怎么在自定义的波浪求解器中使用wave2foam的波高仪对波高进行监测
wave2foam waveHeightGauge
    # 方法1
    This method mainly teaches you how to use wave2foam's wave height meter to monitor wave height in a custom wave solver.
    ![image](https://github.com/byChen47/waveHeightGauge/blob/main/wave2foam%20waveGuages.png)  
    #first  
    将你的求解器复制到wave2Foam的求解器中waves2Foam/applications/solvers/solvers2206_PLUS  
      
    copy you solve to wave2foam  /waves2Foam/applications/solvers/solvers2206_PLUS  
      
    #second  
    在你自己的求解器编译文件Make/Options的EXE_INC中添加wave2foam关于监测波高的程序  
      
    add the wave2foam wave gauge program in you self solver Make/Options  EXE_INC  
      
    #third  
    在你自己的求解器编译文件Make/Options的EXE_LIBS中添加wave2foam关于监测波高的程序  
      
    add the wave2foam wave gauge program in you self solver Make/Options  EXE_LIBS  
      
    #hope this can help you  
chen  
    # 方法2
    先按照wave2Foam编译方法编译好wave2Foam  
    
    然后按照上面的图片中的步骤2和步骤3进行编译就可以了 
    
    #second  
    在你自己的求解器编译文件Make/Options的EXE_INC中添加wave2foam关于监测波高的程序  
      
    add the wave2foam wave gauge program in you self solver Make/Options  EXE_INC  
      
    #third  
    在你自己的求解器编译文件Make/Options的EXE_LIBS中添加wave2foam关于监测波高的程序  
