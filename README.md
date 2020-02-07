# Leakage-Detection-in-Smart-Water-Distribution-Systems

This project was done in CSIR-CEERI, Pilani in the Cyber Physical Systems department under the mentorship of Principal Scientist [Dr. Bhausaheb Ashoke Botre](https://www.ceeri.res.in/profiles/bhausaheb-ashok-botre/). 

A major chunk of project involved the study of Leakage Detection techniques, and then, conducting experiments on a physical testbed (existing in CSIR-CEERI, Pilani) which has a pipeline network with all relevant sensors installed, which mimics the arrangement of a typical water distribution network. PLC and SCADA system is installed for control and data collection.

Thereafter, data was collected by conducting experiments by simulating various types of leak and studying the behaviour of the system.

Further, the data was carefully analysed to study the dependence of various parameters at various nodes on a leak, and study of how these parameters are interdependent. Further, an ANN based model was trained to after carefully deciding the features which classifies a state of operation as leak or not a leak.

The files in this respository include -
- Data
- Analysis_and_Model.ipynb : Analysis of Data, Training the model, Testing the model

Results obtained -
- Accuracy: 92%
- Precision - 92.5%
- Recall - 90.7%
- F1-score - 91.4%
