---
author: rsk0be
comments: true
date: 2010-03-16 09:38:32+00:00
layout: page
link: https://www.alsutton.blog/reference-material/advent-t9610-drivers/
slug: advent-t9610-drivers
title: Advent T9610 Drivers
wordpress_id: 466
---

I've seen some requests for drivers for the Advent T9610, as I have one of these I can post the following list of drivers which I have confirmed are compatible with the T9610;


 



	
  * Base Chipset : Intel P35/G33/G31, drivers available from [here](http://downloadcenter.intel.com/Filter_Results.aspx?strOSs=All&strTypes=All&ProductID=816&lang=eng&OSFullName=All%20Operating%20Systems).

	
  * IDE Driver : Intel ICH 9, drivers available form [here](http://downloadcenter.intel.com/Product_Filter.aspx?ProductID=2101).

	
  * Ethernet Adapter : Intel 82566DC-2, drivers available from [here](http://www.intel.com/products/ethernet/index.htm#s1=Gigabit%20Ethernet&s2=82566DM/DC/MM/MC&s3=all)

	
  * Sound : Realtek HD Audio, drivers available from [here](http://www.realtek.com.tw/downloads/downloadsView.aspx?Langid=1&PNid=14&PFid=24&Level=4&Conn=3&DownTypeID=3&GetDown=false).


 
	

**Note :**Some T9610's are shipped with incorrect processor information. When you open the device manager and look at the processors you should see four entries for a Q6600, if you see two for an E4500 and two for a Q6600 you should delete the E4500 entries rebooting between deletion. Doing this will improve how windows schedules jobs over the different cores.



