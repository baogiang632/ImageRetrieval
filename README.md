# **Celeb Face Retrieval**  
_Face recognition by using Similarity Measure and Vectorized Images_

## **📌 Overview**  
- **What does it do?** This project returns n images, which have a similar face to the input image by using the Similarity measure
- **Why is it useful?** It can find a look-alike face to the input face, which can be a face similar to a celebrity.

## **🛠️ Tech Stack**  
- **Programming Languages:** Python
- **Libraries/Frameworks:** TensorFlow, OpenCV
- **Special structure:** KD-Tree

## **🚀 Installation & Setup**  
### **1️⃣ Clone the repository**  
```bash
git clone https://github.com/baogiang632/ImageRetrieval.git
```
### **2️⃣ Install dependencies**  
```bash
pip install -r requirements.txt
```
## **📂 Dataset**  
- **Dataset Name:** Pins Face Recognition
- **Download link:** https://www.kaggle.com/datasets/hereisburak/pins-face-recognition
- After unzipping it in the _dataset_ folder, we'll have this folder: ![image](https://github.com/user-attachments/assets/bdd87e06-fd0b-4d9c-9aaa-9a32839056d1)


## **📖 Usage Examples**  
**1.** Run the "store_vectors.py" file to vectorize the data images  
**2.** Before run the "search_image.py" file, you can change input image at **search_image**:  

```python
### -------------------- Main -------------------- ###

# Định nghĩa ảnh cần tìm kiếm
#   Adriana Lima0_0.jpg | Adriana Lima cut.jpg | Adriana_Lima.jpg | output_face_face1.jpg
search_image = "testimage\Adriana_Lima.jpg" 
```

