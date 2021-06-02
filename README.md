# Document-detection-and-Skew-correction
At first I'm doing image alignment then doing document detection,Here i'm using google vision api to detect document and parse content from samples with 100% accuracy.Then parse specific content from invoice samples. 

# Dependency
  python 3.7  
  pip install tensorflow=2.0.0   
  pip install pandas  
  pip install numpy 
# alined samples,Detect Document and Parse content
Run above command  
_image_alignmnet-2 (1).ipynb_

 __Result__:  
 1)non_aligmnet_sample  
 ![invoice-8](https://user-images.githubusercontent.com/45398575/120427565-f1d7e980-c393-11eb-8a12-a77f6d4edb67.jpg)  
 2)detected sample    
 ![Capture-2](https://user-images.githubusercontent.com/45398575/120430415-cf949a80-c398-11eb-97ec-eae16d03f96b.PNG)  
 3)alignment_sample  
 ![Capture](https://user-images.githubusercontent.com/45398575/120428072-d3beb900-c394-11eb-8975-2a661dafd388.PNG)
 
# Parse specific content 
Run above comment:  
_parse_shop_name.ipynb_   
 __sample__:   
 ![net_1](https://user-images.githubusercontent.com/45398575/120429407-2600d980-c397-11eb-8754-3b31cfe71d2c.png)  
 __Result__:  
 Like parse shop name from invoice samples  
 ![Capture-1](https://user-images.githubusercontent.com/45398575/120428934-5f851500-c396-11eb-9f4e-b4f74ff0c306.PNG)

  



