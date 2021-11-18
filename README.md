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

1.Frame size	
2.Epoch time
3.Complete length	
4.Time since preceding frame in the TCP stream
5.Time delta from earlier packet
6.Coloring rule name
7.Size
8.File data
9.TCP payload	


Free use of the VIT_SPARC20 dataset for academic research purposes is hereby granted in perpetuity. The authors have to cite the following paper that has the dataset’s details: .

Ikram, Sumaiya Thaseen, Cherukuri, Aswani Kumar, Poorva, Babu, Ushasree, Pamidi Sai, Zhang, Yishuo, Liu, Xiao and Li, Gang. "Anomaly Detection Using XGBoost Ensemble of Deep Neural Network Models" Cybernetics and Information Technologies, vol.21, no.3, 2021, pp.175-188. https://doi.org/10.2478/cait-2020-0037

For more information about the dataset and code, please contact the author,

Dr.I.Sumaiya Thaseen, (isumaiyathaseen@vit.ac.in)
