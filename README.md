# Flag Clustering

This is my capstone project for my studies in Data Science with Digital Futures

## Project Aims

This is an explorational data science project which aims to find connections between flag designs in order to cluster them.
It is already known that many flags share designs with each other (Nordic cross, pan-Arab colours etc.) this project is my attempt to group them purely on flag design without external reference.

## Methods

The flag iamges to be analysed were scaped from Wikipedia.
They were clustered by KMeans analysis using two approaches.
The first was a simple list of what colours are present and in what percentage.
The second turned the images into monochrome shapes, which were then analysed using Principal Component Analysis to group flags into roughly similar shapes

## Conclusion

Overall this is not a great clustering set.
The problem seems to be that while shape and colour do have shared significance across similar cultures, knowing when a shared feature is due to shared history rather than a simple coincidence is rather tricky, and requires a priori knowledge of the meaning of flags.

## Further plans

For clustering to work, one idea might be to scrape pages on the meaning of flags and assign symbolism to each symbol.
This would allow clustering to differentiate for exmaple blue when refering to sea and when to sky.
Another important step would be better image recognition, particulalry the ability to separate background shape from insignia.
