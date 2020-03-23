1) Acquire a video
2) Exctract Images from video with the script getImages from the Raw folder
3) Label them in different folders
4) Make you sure you have the same data quantity vy copying file if necessarythe augmentation will deal with it
5) Use the resizeFolder script to create the train and val folders and the data inside (with reduced size pictures, this parameter can be changed, the resulting pictures will be in the folder cleaned
6)Reduce the number of data you have, with a lost script that is similar to augmentation.py that is the augmentation folder but with no augmentation, and deleting the file as soon as it's not chosen, with some probablities (that will depend on how much data left you want)
7)Augment your data with augmentation.py, The parameters can be chosen, the augmentation is done randomly
8)zip the fodler
9)import it to G.collab or put it in the same folder as your jupyter notebook
10) train you algorithm and save it
11)Prepare your Edge device (install pytorch and pytorchvision)
12) Download your model and load it in the current machine
13)put the files in ~/Downloads/TestData/val
14)launch the script with python3, the script is currently in ~/Downloads

