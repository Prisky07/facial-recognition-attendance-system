# facial-recognition-attendance-system

To run this code on your local system with your own training images, follow these steps:

**Prepare Your Dataset:**

Organize your personal images in the following folder structure:

text
dataset_folder/
├── train/
│   │   ├── img1.jpg
│   │   ├── img2.jpg
│   │   └── ...
│ 

**Update the Code:**
Replace the dataset path with your own folder path:

python
dataset = "path/to/your/dataset_folder"  # Replace with your actual dataset path

**Run the Training:**
Execute the script to train the model on your custom images.

**The model will automatically:**

Load your personal images for training 

Apply necessary preprocessing 

Train the code to classify your images

Make sure your images are properly labeled and organized in the correct folder structure for the ImageFolder loader to work correctly
