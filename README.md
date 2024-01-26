**1. "OriDataFiles_BSM"**
   
The original Basic Safety Message (BSM) data can be obtained from the zip file named "OriDataFiles_BSM". 
The VeReMi-Extension datasets are available for downloading from the following link:
https://mega.nz/folder/z0pnGA4a#WFEUISyS5_maabhcEI7HQA.
The files provided by the authors are in ".json" format, and pre-processed data in CSV format has been uploaded here.

**2. "OriDataFiles_MAP_Detectors"**
   
The original Map data and Detector data can be obtained by the zip file named "OriDataFiles_MAP_Detectors".
F2MD is the simulation framework used to obtain the VeReMi-Extension dataset, and it is based on Veins (V2X Simulator).
Veins operates on OMNET++ (Communication Simulator) and has an interface with SUMO(Traffic Simulator).
Map data can be obtained from the file "lustnanoxml.csv" while Detector data can be obtained from "due.actuated.summary.xml". 
The file "due.actuated.summary.xml" needs to be re-simulated to synchronize its timestamps with those of the BSM data.

**3. Step 1 Data Fusion; Step 2 Trust Factor Acquisition**

The code files for data fusion and trust factor acquisition are not explicitly provided by the authors at this peer-reviewed stage. 
The output file of this stage, i.e., BSM with trust labels, is provided for understanding the input of trust prediction. 

**4. Step 3 Trust prediction**

The above-mentioned files are utilized for trust predictions using machine learning methods. 
Additionally, the input files are different for per-minute level and multi-minute level. 
The code files are not explicitly provided by the authors at this peer-reviewed stage. 
