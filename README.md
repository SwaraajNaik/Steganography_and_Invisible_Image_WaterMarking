# Steganography_and_Invisible_Image_WaterMarking

# Media-steganography

**_Hiding the message in an audio file. LSB-Steganography is used in this project_**



# Pre-requisite

-   Git-Hub account

-   Python 3

-   pip

# Import

-   import matplotlib.pyplot as plt

-   import numpy as np

-   import wave

-   import sys



# Inputs

**Encoding the messgae**

  -   **Filename** - This takes the name of the file alongwith the extension where the message is to be encoded(hidden).

  -   **Message** - This is the message which is to be hidden in the audio.

  -   **audio** - the audio file in which the message is to be hidden



**Extracting the message**

- **Decode algo** - This is the secret key which is used to encode the message. Here, key is used to decide the bits where the message bits are to be encoded.



# How-to-run

  - Step-1 Open the Audio-steganography.ipynb file in colab or jupyter notebook.

      Link to the .ipynb file - 

      https://github.com/SwaraajNaik/Audio-Steganography

      

      - To open the file in colab, copy the above link and in colab page, paste it in the git-hub url.

      

      - ![6](https://user-images.githubusercontent.com/40821800/150410479-0f8ec00c-3e89-4afa-be88-9f6bb9b4fb44.png)

      

  - Step-2 Once open, run all the cells from the beginning.

  - Step-3 Finally run the **result** segment to see the results of both encoding the message in the audio file and extracting the message from the audio file.





![2](https://user-images.githubusercontent.com/40821800/150410694-bf9d15f9-9c0a-4542-af83-f1f670fc1ca0.png)

![3](https://user-images.githubusercontent.com/40821800/150410698-10c1f534-bfea-4338-8e27-097b3b823154.png)

![4](https://user-images.githubusercontent.com/40821800/150410699-44960a70-2195-4799-b6c4-deabaf510b40.png)



# DCT-BASED-INVISIBLE-WATERMARKING

DCT BASED INVISIBLE WATER MARKING WITH ATTACKS

DCT (discrete cosine transform) domain watermarking is robust against attacks such as 

noising, compression, sharpening, and filtering. ... DCT allows an image to be decomposed 

into different frequency bands, making it easy to embed watermarking information into the 

frequency bands of the image.





# Pre-requisite

-   Git-Hub account

-   Python 3

-   pip

# Import

- import cv2

- from scipy.fftpack import *

- import numpy as np

- import math

- from skimage.util import random_noise

- from google.colab.patches import cv2_imshow



# Inputs

**Embedding the watermark**

  -   **Image** - This takes the name of the image where the watermark to be embedded.

  -   **watermark** - This is the image to be embedded in the background image.

  -   **DCT** -applying dct on the image



**Extracting the logo**

- **Decode algo** - To perform IDCT to extract the logo.



**Attack**

- **geomatric attack**

- **salt and pepper attack**

- **gaussian noise**



# How-to-run

  - Step-1 Open the Audio-steganography.ipynb file in colab or jupyter notebook.

      Link to the .ipynb file - 

     https://github.com/SwaraajNaik/DCT-BASED-INVISIBLE-WATERMARKING

      

      - To open the file in colab, copy the above link and in colab page, paste it in the git-hub url.

      

      -  ![Screenshot 2022-02-03 233739](https://user-images.githubusercontent.com/40821800/152402697-73f4a30f-d5ea-4af4-969c-fd3486059798.png)



      


  - Step-2 Once open, run all the cells from the beginning.
