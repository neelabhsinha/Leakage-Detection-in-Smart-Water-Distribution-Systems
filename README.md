# Leakage-Detection-in-Smart-Water-Distribution-Systems

This project was done in CSIR-CEERI, Pilani in the Cyber Physical Systems department under the mentorship of Principal Scientist [Dr. Bhausaheb Ashoke Botre](https://www.ceeri.res.in/profiles/bhausaheb-ashok-botre/). 

Data - Data was collected experimentally from an IOT-based Smart Water Grid testbed and thus can't be shared publically.

### Elements of the Project -

- A major chunk of project involved the study of Leakage Detection techniques, and then, conducting experiments on a physical testbed (existing in CSIR-CEERI, Pilani) which has a pipeline network with all relevant sensors installed at various places, which mimics the arrangement of a typical water distribution network. PLC and SCADA system is installed for control and data collection.

- Thereafter, data was collected by conducting experiments by simulating various types of leak and studying the behaviour of the system.

- Further, the data was carefully analysed to study the dependence of various parameters at various nodes on a leak, and study of how these parameters are interdependent. Further, deciding features were extracted which were to be used as inputs for the classification.

- An ANN based model was trained to after carefully deciding the features (which were temperature, pressure, flow rate and vibration at different nodes of the network) which classifies a state of operation as leak or not a leak.

### Included Files with the repository -
- Data : A portion of used Data to observe the nature
- Analysis_and_Model.ipynb : Analysis of Data, Training the model, Testing the model

### Feature Dependency -

Only the % dependency of leak on various parameters are shown here. Individual Data Analysis graphs and visualizations can be seen from [Visualizations](https://github.com/neelabhsinha/Leakage-Detection-in-Smart-Water-Distribution-Systems/tree/master/Visualizations) Folder.

<img src="/Visualizations/Feature Extraction.PNG"/>

### Model -

<img src="/Visualizations/Model Block.PNG"/>


### Results -

Metric | Value (%)
-------|----------
Accuracy | 92%
Precision | 92.5%
Recall | 90.7%
F1-score | 91.4%
