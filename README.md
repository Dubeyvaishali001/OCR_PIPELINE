PROJECT STRUCTURE
OCR_PIPELINE/
│── preprocessing/       # Deskew, crop, enhancement
│── models/              # EasyOCR, TrOCR, PaddleOCR usage
│── results/             # Outputs and analysis
│── notebook.ipynb       # Full pipeline implementation
│── README.md

⚙️ How to Run
1. Install Dependencies
pip install opencv-python
pip install numpy
pip install matplotlib
pip install easyocr
pip install transformers sentencepiece
pip install paddleocr

2. Open the Jupyter Notebook
jupyter notebook

🧠 Pipeline Flow
IMAGE → Preprocessing → Deskew → Crop → OCR Model → Text Output

<img width="825" height="526" alt="image" src="https://github.com/user-attachments/assets/3cbd72f7-7e4f-4506-a29c-22519250ebd2" />


<img width="952" height="284" alt="image" src="https://github.com/user-attachments/assets/b40640bd-c0cc-4429-9fb7-4708c79fb7af" />

<img width="968" height="375" alt="image" src="https://github.com/user-attachments/assets/bac55b31-ab85-4ddf-bc19-084079997763" />

<img width="1474" height="530" alt="image" src="https://github.com/user-attachments/assets/805ea799-d28f-4991-a2dd-13e7ce1a8b6c" />

<img width="759" height="350" alt="image" src="https://github.com/user-attachments/assets/f8e93b23-78dd-4679-b0e6-7a75f665ea10" />
<img width="472" height="337" alt="image" src="https://github.com/user-attachments/assets/c0f1f3c8-60ae-4345-baf9-fdccbb9a4e74" />

<img width="246" height="213" alt="image" src="https://github.com/user-attachments/assets/85719b1f-39a3-44a7-a48d-be65151dc785" />

<img width="599" height="317" alt="image" src="https://github.com/user-attachments/assets/543c8734-bf67-4837-a904-3cba0090e92b" />


word_1.png → No
word_2.png → Pain
word_3.png → No
word_4.png → Gain



