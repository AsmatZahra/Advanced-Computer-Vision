# Unet-with-Monuseg-dataset
An implementation of [Unet](https://arxiv.org/pdf/1505.04597.pdf) with Monuseg [dataset](https://monuseg.grand-challenge.org/Data/)

# Network Architecture
  ![](/Images/UNetArchitecture.png)

# Trained Model
  Available in [repository](U-Net/)
  
# Results

|Datasets|Accuracy|Loss|MSE|Precision|
|--------|--------|--------|--------|--------|
|Train|0.91|0.20|0.06|Nil|
|Validate|0.90|0.22|0.07|Nil|
|Test|0.83|Nil|Nil|0.90|
 
## Graphs
 ![](/Images/UNetGraphs.png)

## Qualitative Results
### Results on Train-set

![](/Images/U-Net%20train%20qualitative%20results.png)

### Results on Validation-set

![](/Images/U-Net%20validation%20qualitative%20results.png)

### Results on Test-set

![](/Images/U-Net%20test%20qualitative%20results.png)

To Reproduce the results please change the file paths according to your directory setup and directly run from your druve in Google colaboratory
