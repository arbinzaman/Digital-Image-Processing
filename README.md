# Digital Image Processing - Assignment 1

## **Objective**
This assignment focuses on fundamental image processing tasks using OpenCV and Matplotlib in Python. The two main tasks are:

1. Extracting a **100×100** region from the center of an image.
2. Converting the image to **HSV color space** and visualizing the Hue, Saturation, and Value components in grayscale.

---

## **Requirements**
Ensure you have the following installed in your Google Colab or local Python environment:

- Python 3.x
- OpenCV (`cv2`)
- NumPy
- Matplotlib
- PIL (Pillow)
- Google Colab (if using Google Drive for image storage)

To install missing dependencies, run:

```sh
pip install opencv-python numpy matplotlib pillow

````

## **Usage Instructions**
### **Step 1: Clone the Repository**
#### **Create a separate repository for this assignment and upload the .ipynb file. Then, clone it using:**


```sh
git clone https://github.com/your-username/DIP-Assignment-1.git
cd DIP-Assignment-1
```

## **Step 2: Open and Run in Google Colab**
### **If using Google Colab, upload the .ipynb file and make sure your image is in Google Drive. Then, mount your drive:**


```python
image_path = "/content/drive/MyDrive/UITS/Eight Semester/Digital Image Processing/Assigments/Class 1/pizza.jpg"
cropped_image = extract_center_region(image_path)
hsv_image = convert_to_hsv(image_path)
```

## **Expected Output**
#### **Task 1: Displays a 100x100 cropped image from the center.**
#### **Task 2: Displays three grayscale images representing:**
* Hue component
* Saturation component
* Value component
