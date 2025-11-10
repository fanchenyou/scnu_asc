阅读 https://www.asc-events.net/StudentChallenge/History/2024/index.html

在linux(ubuntu 22) 完成 这两个安装包

### I. HPL performance optimization:
1.Platform requirement: The runtime power consumption must remain under 3 KW. Failure to comply will result in the invalidation of the current task.

2.Goal: Obtain the correct results while achieving the highest performance.

3.Software download: http://www.netlib.org/benchmark/hpl/

测试  
```
cd hpl-2.3/bin 
./xhlp
```

### II. Performance optimization of HPCG:
1.Platform requirement: The runtime power consumption must remain under 3 KW. Failure to comply will result in the invalidation of the current task.

2.About run time: The runtime of HPCG (version 3.0) must be a minimum of 1800 seconds (30 minutes), as reported in the output file. The Quick Path option is not permitted.

3.Software download: https://github.com/hpcg-benchmark/hpcg


测试  
```
cd hpcg
./xhpcg
```

结果发送至 fanchenyou AT scnu.edu.cn