# HS-WF-dataset
Dataset for "Deanonymize Tor Hidden Services Using Remote Website Fingerprinting"
The data is divided into three directories, client, hs and beta, which correspond to the traces collected on client-side and hs-side and mixed randomly with alpha=0.1 respectively. 
We collected a total of 318 hidden service traces, corresponding to subdirectories 0 to 317. We use the first 100 categories for dataset for classification, and the other 218 categories as dataset for feature extraction. 
Each trace is saved as a .pkl file, and is represented as a sequence consisting of {+1, -1, 0}, as described in the paper.
