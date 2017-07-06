# Value Investing Studies
#### [by Euclidean Technologies, LLC](http://www.euclidean.com)

This repo is a collection of data anaysis studies that examines the performance and characteristics of value investing over long periods of time. Each directory is a study dedicated to a particular form of data analysis on value investing. The studies depend only on the code herein and publicly available stock market and economic data. We would like to thank [Kenneth R. French](http://mba.tuck.dartmouth.edu/pages/faculty/ken.french/) and [Robert Shiller](http://www.econ.yale.edu/~shiller/) for making this data available through their websites [here](http://mba.tuck.dartmouth.edu/pages/faculty/ken.french/data_library.html#Research) and [here](http://www.econ.yale.edu/~shiller/data.htm), respectively. 

The studies in this repo are:
- [Value and Inflation](https://github.com/euclidjda/value-investing-studies/tree/master/value-and-inflation): 
	- Characterizes the relationship of value stock performance with respect to inflation as measured by the consumer price index
- [Value and Interest Rates](https://github.com/euclidjda/value-investing-studies/tree/master/value-and-interest-rates):
	- Characterizes the relationship of value stock performance with respect to long-term interest rates 
- [Value is Hard](https://github.com/euclidjda/value-investing-studies/tree/master/value-is-hard)
- [Value vs. Growth](https://github.com/euclidjda/value-investing-studies/tree/master/value-vs-growth)


# Installing and Executing the Studies

### Cloning the Git Repository

To clone our repository, make sure you’re in a directory on your computer that you want to hold our files. Use the command 

```bash
$ git clone https://github.com/euclidjda/value-investing-studies.git
```

to copy our repository “value-investing-studies” into your current directory. 

### Executing the Code

Choose a chart from our README to reproduce.

Suppose we want to run the script “value-cpi-decade-chart.R”. To run this script, make sure you’re in the directory that is holding our cloned repository, and use the command: 

```bash
$ cd value-investing-studies/value-and-inflation
```

This will place you in the “value-investing-studies” directory that contains all of our files, and then in the “value-and-inflation” directory, which contains the script we want to run. Lastly, to run the script, use the command: 

```bash 
$ Rscript value-cpi-decade-chart.R
```

After doing so, this chart should pop up:  

![alt text](/value-and-inflation/value-cpi-decade-chart.png)


# Contributors and Acknowledgement

This repository was developed and is maintained by [Euclidean Technologies, LLC](http://www.euclidean.com/). Contributors include [David Tran](http://github.com/dtran24) and [John Alberg](http://github.com/euclidjda). We would like to thank [Kenneth R. French](http://mba.tuck.dartmouth.edu/pages/faculty/ken.french/) and [Robert Shiller](http://www.econ.yale.edu/~shiller/) for making this data available through their websites [here](http://mba.tuck.dartmouth.edu/pages/faculty/ken.french/data_library.html#Research) and [here](http://www.econ.yale.edu/~shiller/data.htm), respectively. 

# License 

This is experimental software. It is provided under the [MIT license][mit], so you can do with it whatever you wish except hold the authors responsible if it does something you don't like.

[mit]: http://www.opensource.org/licenses/mit-license.php
