# Plant_disease_detection  
### Creating a model which classifies a given leaf as healthy or diseased and determining the disease it contains from the symptoms.
Over the years, many events of plant diseases have inflected suffering on untold millions of people worldwide by causing an estimated annual yield loss of 14% globally. Plant pathology is the science of plant diseases that attempts to improve the chances for survival of plants under unfavorable environmental conditions and parasitic microorganisms that cause disease. Current disease diagnosis is time consuming, expensive and based on human scouting.
This project is an attempt for automated disease prediction through machine learning concepts like Deep Convolutional Neural Networks.
#### A. DATA ACQUISITION
The Apple leaves dataset has about 3600 real life images of apple foliar diseases with variable angles,illumination and surfaces.
#### B. DATA PREPROCESSING
Before training and fitting the model, all the unlabelled entries from the training set are removed. The incorrect labels are corrected. This pre-processed data is augmented using annotation and augmentation techniques and then split into training and validation dataset.
#### C. EXPLORATORY DATA ANALYSIS
Analysis of the number of images of apple plant leaves for different classes[19] reveals that 34.2% of total images in the training data have Rust, 32.5% have Scab, 28.3% are Healthy and just 5% in Multiple class.
#### D. DATA AUGMENTATION
To avoid overfitting of the model, data augmentation is done either through separate algorithms[10] or through Keras ImageDataGeneration Class[18] which will perform flip, rotation, brightness variation, blurring and skew operations at once on each image and will generate the required number of augmented images for each original.
#### E. MODEL BUILDING AND TRAINING
#### F. COMPARING WITH OTHER MODELS
