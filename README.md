LAB 2 JAN MOLLET DATA VERSION CONTROL (DVC)

During this lab, I created a bucket in Google Cloud Storage in order to use Data Version Control (DVC) which serves as a technique to save and keep track of different versions of the data.
In this lab, I decided to download a new dataset called "diamonds.csv" from Kaggle to experiment and play around with dvc and visualize how we can add, commit and push datasets to Google cloud to save different versions of the data the same way we do with code when using Github.

Using a secret key stored in a json file I was able to connect to the storage where I can already see the first version of the code.

When doing this Lab I understood the idea behind DVC and I also realized that we are doing two different things:


1. Data Storage: Offloading the heavy dataset to a Google Cloud Storage bucket to keep the repository lightweight.

2. Version Tracking: Committing a pointer file (.dvc) to Git. This identifier acts as a link, allowing us to track data versions and retrieve the exact state of the dataset associated with any specific code commit.
