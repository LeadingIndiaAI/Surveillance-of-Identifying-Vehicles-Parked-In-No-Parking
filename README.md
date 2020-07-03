# Parking-Classification

Requirements-

    python3

    opencv3

    keras

    numpy

    tqdm


Options-


Options of 3dcnn.ipynb are as following:

    --batch: batch size, default is 128.

    --epoch: the number of epochs, default is 100.

    --videos: a name of directory where dataset is stored, default is UCF101.

    --nclass: the number of classes you want to use, default is 101.

    --output: a directory where the results described above will be saved.

    --color: use RGB image or grayscale image, default is False.

    --skip: get frames at interval or contenuously, default is True.

    --depth: the number of frames to use, default is 10.

To train the model, change the dataset path and output path in 3DCNN.ipynb file and run it.
