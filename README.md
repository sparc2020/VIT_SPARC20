# VIT_SPARC20
Data samples are generated in VIT campus and captured using Wireshark. There are four broad categories of traffic in the data set namely unencrypted normal, unencrypted abnormal,encrypted normal and encrypted abnormal. In addition, there are total of 32 class labels which are detailed in the labels file.
Initial Number of attributes : 24. After Feature Set Reduction: 9
Attribute characteristics: Integer, decimal and nominal values.

Sl.No	Attribute	Values  - Initial Attribute Set

1	Frame size	Integer
2	Epoch time	Decimal
3	Time delta from pre-vious captured packet	Decimal
4	Time delta from pre-vious displayed packet	Decimal
5	Time since reference of first frame	Decimal
6	Frame number	Integer
7	Protocols in frame	Nominal
8	Coloring rule name	Nominal(takes value 1 or 2)
9	Coloring rule string	Nominal(takes value 1 or 2)
10	Sequence 	Integer
11	Acknowledgement	Integer
12	Length	Integer
13	File data	Integer
14	Total length	Integer
15	Identification	Integer
16	Time to live	Integer
17	Window size value	Integer
18	Calculated window size	Integer
19	Window scaling factor	Integer
20	Time since first frame in this tcp stream	Decimal
21	Time since previous frame in this tcp stream	Decimal
22	Tcp payload	Integer
23	Tcp segment data	Integer
24	Label	Nominal

After Feature Reduction:

Frame size	
Epoch time
Complete length	
Time since preceding frame in the TCP stream
Time delta from earlier packet
Coloring rule name
Size
File data
TCP payload	
