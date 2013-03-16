$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$

                Mt Gox Price / Density Plotting Suite
                        by Ryan Molecke 2013
                  based on code by Joel Schaerer 2011

  This code includes:

  1) scripts designed to query Mt Gox for trade info and maintain
     a local MYSQL database with integrity to the Gox DB

  2) scripts designed to plot the price density over time with many
     interval options

  3) scripts for monitoring the live Mt Gox web-stream (optional, not debugged)

  This code runs on Debian linux, tested on Ubuntu 10.04 

  Required Packages:
   mysql, mysql-client, mysql-server, 
  

  - Joel's code plotted the price-density from data files

  - Ryan added the Gox interface, in-memory optimizations, stream 
  monitoring code, debugged the plotting code, nice axis formatting by interval

  
$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$
