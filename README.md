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


word_1_leve_Yeu.png → love you
word_2_Foio.png → plaists ,
word_2_rumma.png → " conservanoscope .
word_3_(Jill.png → devil
word_3_No.png → no
word_4_Gaio.png → gain
word_4_make.png → committee .
word_5_Yee.png → stores
word_6_pSous.png → peroudi
word_7_Sne.png → omen
word_8_day.png → was



