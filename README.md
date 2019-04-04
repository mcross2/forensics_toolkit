# Forensics Toolkit

## Disc Image Analysis
#### FTK Imager
Description: FTK Imager is used to capture an image of a machine. It duplicates the disc image and caputres the memory. It aso hashes any files pulled to ensure the integrity of the data. 
[More info](http://marketing.accessdata.com/ftkimager3.4.2)

Review: It was very easy to use and straight forward. 

Notes: No extra notes needed.

[Download](https://accessdata.com/product-download/ftk-imager-version-4.2.0)

#### Netcat
Description: Netcat is used to remote into a machine. We used it to clone a machine and it's memory from another machine.
[More info](https://www.win.tue.nl/~aeb/linux/hh/netcat_tutorial.pdf)

Review: It was pretty easy and straight forward to use.

Notes: Here is a tutorial on cloning a machine using netcat [tutorial](http://www.softpanorama.org/Tools/DD/dd_and_netcat.shtml)

[Download](https://eternallybored.org/misc/netcat/)

#### DD
Description: We used this is parallel with Netcat to clone disc image.
[More info](http://www.softpanorama.org/Tools/DD/dd_and_netcat.shtml)

Review: It was pretty easy and straight forward to use.

Notes: No notes needed

#### FTK
Description: FTK is intended to be a complete computer forensics solution. It gives investigators an aggregation of the most common forensic tools in one place. It allows you to traverse through a disc image and look at a logs stored on the computer and logs built by FTK based off the disc image. 
[More info](https://resources.infosecinstitute.com/category/computerforensics/introduction/commercial-computer-forensics-tools/ftk-forensic-toolkit-overview/#gref)

Review: I prefer Autsopsy, it is a little easier to use in my opinion than FTK

Notes: I personally didn't use this. I prefer Autopsy.

[Download](https://accessdata.com/product-download/ftk-download-page)

#### tcpdump
Description: Used for capturing the memory of a machine.
[More info](https://www.tcpdump.org/manpages/tcpdump.1.html)

Review: Easy and straight forward to use.

Notes: Make sure to do this before turning off the machine.

#### Autopsy
Description:  Autopsy is very similar to FTK in that it is most commonly used to view disc image files and create reports on a disc image that can help digital forensic investigators. 
[More info](https://www.sleuthkit.org/autopsy/)

Review: I really like Autopsy. The Timeline feature is particularly nice in Analysis of the disc image.

Notes: loading evidence in can take a long time. Have it running over night

[Download]https://www.sleuthkit.org/autopsy/download.php)

#### WinPrefetchViewer
Description: This allows you to easily see prefetch files in a way that allows more understandable description and actions that each file is doing. 
[More info](https://www.nirsoft.net/utils/win_prefetch_view.html)

Review: I really like WinPrefetchViewer. It makes going through the Prefetch files of a disc image really easy to comprehend and sort through.

Notes: Easy to use, no notes needed

[Download](https://www.nirsoft.net/utils/win_prefetch_view.html)

#### Windows Event Viewer
Description: This allows you to easily see the event logs in a way that allows more understandable description of what was going on on the machine. 
[More info]()

Review: I really like Window Event Viewer. It makes going through the exported event logs from a disc image really easy to comprehend and sort through.

Notes: Easy to use, no notes needed

Pre-loaded on Windows Machines


## Network Analysis
#### Bro
Description: Bro is a great tool that helps in network analysis. It sorts through network capture files and generates different logs that can help an investigator to more easily understand what is going through the network. [More info](https://bricata.com/blog/what-is-bro-ids/)

Review: Bro is a little intimidating at first but is a great tool once you understand what each log is saying.

Notes: Works much better on linux. Don't do it on windows.

[Download](https://github.com/bro/bro)

#### Snort
Description: Snort is similar to Bro in that it analyzes network capture and looks for suspicious traffic. It flags any suspicious packets and creates a report that can be used to track the packets and see the full exchange.
[More info](https://www.techopedia.com/definition/4114/snort)

Review: I didn't use snort a ton in this class. It's not hard to use/find tutorials online.

Notes: No notes saved. Used online tutorial the one-time I used it.

[Download](https://www.snort.org/downloads)


#### Wireshark
Description: Wireshark is an interface that allows investigators to look at all packets sent across the network within the time frame of the network capture.
[More info](https://www.wireshark.org/)

Review: I have had to use this a few times in different classes. It is a great tool and pretty intuitive to use.

Notes: No stored notes. Pretty straight forward app.

[Download](https://www.wireshark.org/#download)


## Memory Analysis
#### Rekall
Description: Rekall is a platform used mainly for memory analysis.
[More info](http://www.rekall-forensic.com/)

Review: I didn't used rekall at all so I don't have any personal preferences at all

Notes: I didn't use it so I don't have any notes.

[Download](https://github.com/google/rekall)

#### Volatility
Description: Volatility is a tool used for memory analysis. I reads a .mem file and generates reports that helps investigators notice and track suspicious programs and functions running on the machine.
[More info](https://www.investopedia.com/terms/v/volatility.asp)

Review: Volatility is kind of a pain becuase for the labs we used it for, we couldn't find an appropiate profile to use for it to successfully read through the .mem file.

Notes: 

[Download]()
