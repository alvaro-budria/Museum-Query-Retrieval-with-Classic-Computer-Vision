# Content-Based Museum Painting Retrieval
## Technical Report
[Museum Query Retrieval with Classic Computer Vision](https://www.overleaf.com/read/dszystwqbbwc)

![Alt text](/week1/matches.png "")

## Week 1: Histograms
1. Develop image query system. Match query paintings with similar ones in database.
2. Implement background segmentation. Automatically separate background from painting.


## Week 2: Multilevel Histograms
1. Develop multilevel block histogram representation.
2. Extract text from paintings.
3. Allow for querying with images containing up to two paintings.


## Week 3: Texture Descriptors
1. Filter noise with linear and non-linear filters
2. Texture descriptors (LBP, DCT, HOG)
3. Combine color and texture descriptors


## Week 4: Matching and Retrieval
1. Detect keypoints (Harris corner detector, SIFT) and compute descriptors in Museum and query images
2. Find tentative matches based on similarity of local appearance and verify matches
3. Implement a system to discard queries not in the data set based on F1 measure


## Week 5: Retrieval and Clustering
1. Remove background, detect lines and crop images, rotate images if necessary
2. For each query image, retrieve the k most similar images in the museum dataset
3. Organize an exhibition of museum paintings: distribute (cluster) paintings in rooms


## Usage
In each `week`, run the corresponding Jupyter Notebook sequentially.


## License
[MIT](https://choosealicense.com/licenses/mit/)


## Team

- Alvaro Budria
- Alex Carrillo
- Irene Estévez 
- Johnny Núñez
