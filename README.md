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
git clone https://github.com/baogiang632/your-repository.git
cd your-repository
```
### **2️⃣ Install dependencies**  
```bash
pip install -r requirements.txt
```
### **3️⃣ Run the project**  
For training:  
```bash
python train.py --dataset path/to/dataset
```
For inference:  
```bash
python predict.py --image path/to/image.jpg
```

## **📊 Results & Performance**  
_(Optional but valuable: Include accuracy metrics, model performance, or a comparison table.)_  

| Model  | Accuracy | Precision | Recall |
|--------|----------|-----------|--------|
| ResNet50 | 92% | 91% | 93% |
| EfficientNetB3 | 94% | 93% | 95% |

## **📂 Dataset**  
_(If applicable, mention the dataset used and provide links if public.)_  
- **Dataset Name:** CheXpert, COCO, KITTI, etc.  
- **Preprocessing Steps:** (e.g., Data augmentation, normalization)  

## **📖 Usage Examples**  
_(Add sample usage or demo images)_  

```python
from model import load_model
model = load_model("best_model.pth")
prediction = model.predict("sample_image.jpg")
```

## **📝 To-Do List**  
_(Optional: Mention future improvements or planned features.)_  
- [ ] Optimize model for mobile deployment  
- [ ] Improve dataset preprocessing  
- [ ] Train on larger datasets  

## **🤝 Contributing**  
1. Fork the repository  
2. Create a new branch (`feature-xyz`)  
3. Commit your changes  
4. Open a Pull Request  

## **🔗 References & Acknowledgments**  
_(Optional: Add links to research papers, datasets, or inspirations for your project.)_  

## **📜 License**  
This project is licensed under the **MIT License** – see the LICENSE file for details.
