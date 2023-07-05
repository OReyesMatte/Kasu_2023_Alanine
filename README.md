# Custom software used in "Amino acid scavenging prevents premature spore germination in sporulating populations of *Bacillus subtilis*"

## File description

The repository consists on three files:

- SporeCounter.ilp: Ilastik-trained pixel classification model used to generate segmentation masks
- Kasu_2023_Alanine.ipynb: Jupyter notebook with the Python code used for analysis of the segmentation masks
- requirements.txt: List of the Python libraries with their corresponding versions used for the analysis. Can be used for installation with the pip package manager

## Code description

The code takes the Ilastik-generated segmentation masks of phase bright and phase gray spores, processes them to obtain the percentage of these spores through time (relative to the amount when the experiment started) and generate the plot of Supplementary Figure 5 in the article

## Data link

Images used for segmentation training and analysis are available at the repository...


## Paper reference

Kasu;, I., Reyes-Matte, O., Derman, A. I. & Lopez-Garrido, J. (2023) Amino acid scavenging prevents premature spore germination in sporulating populations of *Bacillus subtilis*. *In preparation*
