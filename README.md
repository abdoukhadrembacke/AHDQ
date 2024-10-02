 # **Title**: AHDQ (Arabic Handwriting Dataset from Quran): Comprehensive Full Quran Handwriting Dataset in Multiple Styles for OCR

# **Description:**

**AHDQ** (Arabic Handwriting Dataset from Quran) is the first comprehensive dataset designed specifically for OCR tasks, capturing the rich tradition of handwritten Quranic manuscripts from the Wolof community in Senegal. The dataset contains 642 binarized images of handwritten Quranic verses, each consisting of multiple lines, paired with labeled text files. This dataset is ideal for training OCR models, handwriting style analysis, and Arabic text recognition tasks..

# **Cultural and Historical Background:**
In Senegal, the Wolof community has a long-standing tradition of memorizing and writing the Quran by hand. This practice has been passed down for generations, and it is estimated that there are hundreds of thousands of handwritten Qurans throughout the country. The process of writing the Quran from memory, or Hafiz, is deeply respected, and each individual's handwriting reflects their unique style while maintaining the integrity of the sacred text.

This dataset reflects six distinct Wolof handwriting styles, showcasing the diversity in script while preserving the Quranic content. The variety of handwriting in this dataset is invaluable for research in Arabic handwriting recognition, linguistic analysis, and digital preservation of cultural heritage.

# **Handwriting Styles:**
The dataset is divided into six different styles, each denoted by a prefix in the file names:

1. Darou Minan (dmn_)
2. Serigne Amidoun Lo (sal_)
3. Serigne Abdoulahat Souhaibou (sas_)
4. Serigne Bousso Imaam (sbi_)
5. Serigne Djeumb Cisse (sdc_)
6. Serigne Fallou Mbacke (sfm_)
Each file name includes the style prefix followed by a unique number (e.g., dmn_001, sal_002, etc.), allowing easy identification of the handwriting style for each image.

# **Dataset Structure:**
- Images: A total of 642 binarized images, each representing a handwritten verses of the Quran.
- Labels: A CSV file with two columns:
 - file_name: The name of the image file (e.g., dmn_001.png).
 - text: The corresponding Quranic verses in Arabic script.

# **Potential Use Cases:**
- Training OCR models for Arabic handwriting recognition, particularly Quranic texts.
- Handwriting style analysis and comparison across different Wolof Arabic scripts.
- Linguistic and cultural studies on handwritten religious texts.
- Arabic text recognition tasks and model fine-tuning.

# **Future Expansions:**
We plan to expand this dataset by adding more styles of handwritten Quranic text from the Wolof and others willing communities, further increasing the diversity of handwriting available for analysis. The Quran was chosen for this project because it offers a large dataset of over 400,000 characters, which is highly beneficial for deep learning tasks. This dataset size allows for the training of robust models capable of recognizing various handwriting styles and can serve as a valuable resource for researchers and developers in the field of Arabic handwriting recognition.

# **Citation:**
If you use this dataset in your research or projects, please cite it as follows:

@misc{ <br>
        abdou_khadre_mbacke_2024,<br>
	title={AHDQ: (Arabic Handwriting Dataset from Quran)},<br>
	url={https://www.kaggle.com/dsv/9497956},<br>
	DOI={10.34740/KAGGLE/DSV/9497956},<br>
	publisher={Kaggle},<br>
	author={Abdou Khadre Mbacke},<br>
	year={2024}<br>
}<br>

**XIDMA_AI**. (2024).

