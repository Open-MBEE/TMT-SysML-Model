# TMT-SysML-Model for CSM Testing
### This branch of the model is for CSM testing ONLY!

The necessary information needed to test is provided below.

How the model is structured
	- The model overall is split into two parts, the TMT PO and the JPL side.
	- Each of these sides again contains the various aspects and sub-systems relevant for the respective side.
  		o The TMT Observatory side contains the Operational Domains and Flow Analyses as well as its WBS.
    		o The JPL side contains the APS and CS System Model (including its domains and analyses)
	- The structure is also documented in the “00 Start Here” package, specifically in the “TMT Overview Diagram”	

Which simulations can be used and what are the expected results and how to understand they work as expected:
	There are many complex simulations in the TMT model on both, the JPL and the TMT PO side.
 	The most illustrative simulation son the JPL side are shown below, the respective simulation configs are found in the marked folder in Screenshot 1. 

<img width="433" alt="Screenshot 2023-06-22 at 1 08 07 PM" src="https://github.com/Open-MBEE/TMT-SysML-Model/assets/131720106/e88a3fe5-5028-41c3-8b7b-f8d0075c81de">

	Screenshot 1	
	
 These simulations can be run and assess a variety of times.
    	All results are recorded in tables in the package folder marked below in Screenshot 2.
     
<img width="430" alt="Screenshot 2023-06-22 at 1 09 56 PM" src="https://github.com/Open-MBEE/TMT-SysML-Model/assets/131720106/3cf23cea-12f5-4dad-bab7-4967f46a2cff">

	Screenshot 2

	
 The most important time, ranging from 100 to over 30,000 in "Warping Harness Influence Function Analysis Timing Analysis Results" is the tFinal value, which should be recorded properly in each simulation.
       	Recording of these times has to checked and ensured

Which branches and versions to use
	The ‘se’ branch is used by the TMT Observatory and the ‘aps’ branch is used by the people at JPL. This is analogous to the structure described above.
 	Here on GitHub, the APS branch is provided in testing/aps, the se branch will follow


