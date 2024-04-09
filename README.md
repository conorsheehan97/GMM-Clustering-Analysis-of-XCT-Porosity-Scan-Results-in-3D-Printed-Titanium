# GMM-Clustering-of-XCT-Porosity-Scans
This project aims to implement GMM Clustering to XCT Porosity scan results in order to detect how Porosity Morphology develops with increasing Gas Flow in 3D Printed Titanium

Pore defects in Titanium bone implants can be analysed in many ways, the most comprehensive method being good old X-Ray CT scans of the final part. This gives us a fairly holistic interpretation of the geometry, and quantity of detectable pores. It also produces a boatload of data, which is fantastic. 

The situation we're in here, involves Porosity XCT data from 3 seperate builds of Titanium components each made at a different gas flow rate. We already know the amount of pores increases with less gas flow, but we want to see if the proportion of irregular (more damaging pores) changes with Gas flow rate. To this end, we're going to first see if there are any clusters within the dataset, through trialling a few cluster number evaluation methods. We're then going to implement the Gaussian Mixture Clustering Model on the dataset, and analyse how the proportions of these clusters change with respect to Gas Flow rate. Groundbreaking stuff isn't it? 

Models used: KMeans Clustering, Gaussian Mixture Model, 

Libraries used: Pandas, Numpy, Matplotlib, Seaborn, Scikitlearn, 
