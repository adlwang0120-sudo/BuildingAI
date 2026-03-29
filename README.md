<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->
# Project Title
Mushroom Species Identifier
## Summary
This project is an AI-based mushroom species identifier that helps users recognize different kinds of mushrooms from photos. 
## Background
Many mushroom species look similar, especially to beginners. This can make identification difficult and sometimes dangerous. People who enjoy hiking, foraging, nature photography, or learning about plants and fungi often struggle to tell species apart accurately.
This project aims to help solve the following problems:
1. beginners often cannot distinguish similar mushroom species
2. manual identification with books or websites can be slow and confusing
3. mistakes in mushroom identification may create safety risks
4. people may want a simple educational tool to learn about local biodiversity
My personal motivation comes from the fact that mushroom identification is my interest. Mushrooms are diverse, beautiful, and important in ecosystems, but they are also easy to confuse. 
## How is it used?
The solution is designed for people who encounter mushrooms outdoors, such as hikers, amateur foragers, students, and nature enthusiasts.
A possible use process is:
1.	the user takes a photo of a mushroom with a phone
2.	the system analyzes the image
3.	the AI suggests the most likely species or a short list of similar species
4.	the system shows basic information, such as habitat, visual features, and warning notes
5.	the user is reminded not to rely on the system alone for deciding whether a mushroom is safe to eat
The project could be used:
1. during walks in forests or parks
2. in educational settings for biology or ecology
3. by hobby users who want to learn mushroom identification
4. as a support tool, not as a final authority for food safety decisions
People affected by the system include:
1. casual users and beginners
2. mushroom hobbyists
3. teachers and students
4. people interested in biodiversity and citizen science
Their needs include:
1. simple and clear results
2. understandable explanations
3. warnings about uncertainty
4. a safe design that does not encourage risky behavior
## Data sources and AI methods
Main source: FungiCLEF
Supplementary sources: iNaturalist, GBIF, and Mushroom Observer
1.	FungiCLEF / Danish Fungi dataset
Used as the main training data source. This dataset is specifically designed for fungal image recognition and contains a large number of labeled mushroom images, which makes it suitable for species classification.
2.	iNaturalist
Used as a supplementary image source. This platform allows observation data export and is useful for collecting mushroom records with both photos and species labels.
3.	GBIF (Global Biodiversity Information Facility)
Used as a source of species records and metadata. GBIF is an open biodiversity database that can provide species occurrence information and can also support proper citation of data sources.
4.	Mushroom Observer
Used as a more specialized supplementary source in the field of fungi. This platform focuses on mushroom and fungal observations and also provides image data relevant to machine learning.
## Challenges
This project does not fully solve mushroom safety. Even a strong image classifier can make mistakes, especially when:
1. two species look very similar
2. the photo quality is poor
3. the mushroom is partly hidden or damaged
4. important features are not visible, such as gills, stem base, or spore details
5. the training data does not include enough local or rare species
Important limitations and ethical concerns include:
1. users may overtrust the AI
2. misclassification could be dangerous if people use the tool to decide what to eat
3. the model may perform worse on species or regions not well represented in the data
4. expert knowledge is still necessary in high-risk cases
Because of this, the system should clearly state:
This tool is for educational support only and should not be used as the sole basis for deciding whether a mushroom is edible.
## What next?
This project could grow in several directions:
1. add more mushroom species and more diverse training images
2. include region-based suggestions depending on location and season
3. provide explanations of why a prediction was made
4. detect key visual parts of the mushroom separately, such as cap, gills, stem, and color patterns
5. build a mobile app for real-time field use
6. collaborate with mycology experts to improve label quality and safety warnings
To develop this further, I would need:
1. a larger and better-labeled dataset
2. basic model training and evaluation skills
3. help from biology or mushroom experts
4. user feedback from real testing situations
## Acknowledgments
1. inspiration from nature observation and species identification tools
2. open-source machine learning tutorials and image classification examples
3. any mushroom image datasets, biodiversity databases, or expert-labeled resources used in the project should be credited here
4. if external code, images, or datasets are used, their creators and licenses must always be mentioned
