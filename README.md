# CADANet
CADANet
Our complete code will be available soon.

Comprehensive Attribute Difference Attention Net-work for Remote Sensing Image Semantic Under-standing
To IEEE Transactions on Geoscience and Remote Sensing


 
![image](https://github.com/user-attachments/assets/f84192ed-5a28-4ebd-8e85-c2949588ba95)

Fig.  Architecture of the CADANet.

-----------------------------------------------------------------------------------------------------------------------
Algorithm 1: Pseudo Code of Feature Regressor ( )

Input: feature representation vector  , probabilis-tic feature representation vector  , contextual information matrix  

Output: attribute contextual information matrix  

1.	//Perform argmax on the   to get the predicted at-tribute      
2.	for b in   do 
3.	 |  for i in   do 
4.	 |   | for j in   do 
5.	 |   |   | 
6.	 |   | end for
7.	 |  end for
8.	end for
9.	Reshape   to [B, N, C] and initialize the new context information   

10.	//for each batch b and each pixel position (i, j)
11.	for b in   do
12.	 |  for i in   do
13.	 |   | for j in   do 
14.	 |   |   | 
15.	 |   |   | for c in   do 
16.	 |   |   |   | 
17.	 |   |   | end for 
18.	 |   | end for 
19.	 |  end for 
20.	end for
21.	Reshape the attribute contextual information matrix  to [B, C, H, W] 

22.	Return  
-----------------------------------------------------------------------------------------------------------------------


![image](https://github.com/user-attachments/assets/3d0da095-ca4f-4eb3-acb2-4b3ed2da2dad)

Fig. 3. Spatial domain modeling by the AFA module. (a) represents the global spatial domain modeling, (b) represents the local spatial domain mod-eling.

-----------------------------------------------------------------------------------------------------------------------

![image](https://github.com/user-attachments/assets/ed1c3e0e-6577-4e5e-9113-8dbfc137fd7b)
Fig. 4. Architecture of the CAASA module.
