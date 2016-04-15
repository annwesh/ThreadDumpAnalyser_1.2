 Java based Web application is running much slower(latency)  than expected, we need to analyze the  thread dumps.Different issues can arise from thread contention. To analyze such issues, you need to use the thread dumps.
  
 However to analyze a huge set of thread dump files  manually can be hectic and time taking .
 
 This is where the  thread dump analyzer will be helpful.  This tool will take in as input all the thread dump files that is contained in a specific folder  , analyse them and create a  swing based  time series stacked bar chart of all the threads present in the dump files.

 Each time series will show all the states the thread went through(ex..The time within which the thread was in runnable, blocked waiting  states etc.. ) as well as the thread call stack within that interval.
