**ml-fer**

This project utilizes the pre-built `fer` library to detect human emotions from images, classify them, and save the classified images into designated folders.

**Installation**

1. Clone this repository:

   ```bash
   git clone https://github.com/HeyAryaHere/ML-FER.git
   ```

2. Install the required library:

   ```bash
   pip install fer
   ```

**Usage**

1. Place your image files in the `input` folder. Ensure the images are in a compatible format (e.g., JPEG, PNG).

2. Run the script:

   ```bash
   final.ipynb
   ```

start with running from `2`  block and then run `1`

**Example**

If you have an image named `image1.jpg` in the `output` folder that depicts a person smiling, the script will:

- Detect the emotion as "happy".
- Create a folder named `happy` (if it doesn't exist already) within the `output` folder.
- Save a copy of `image1.jpg` in the `happy` folder
- Save a detail output of frame by frame detection in `output` folder

**Dependencies**

- `fer`: A pre-built library for facial emotion recognition ([https://github.com/topics/facial-expression-recognition](https://github.com/topics/facial-expression-recognition))

**Contributing**

I welcome contributions to this project! Please feel free to submit pull requests for bug fixes, improvements, or new features.
I am trying find new techniques and alternatives which you can see in `other models`

**License**

This project is licensed under the MIT License (see the `LICENSE` file for details).

**Disclaimer**

The accuracy of emotion detection using this project may vary depending on the quality and clarity of the images, as well as the limitations of the underlying `fer` library. It's intended for educational and experimental purposes only.
