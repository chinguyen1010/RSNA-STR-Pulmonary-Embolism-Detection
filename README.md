# RSNA-STR-Pulmonary-Embolism-Detection
Classify Pulmonary Embolism cases in chest CT scans

Description:
<img width="835" height="597" alt="image" src="https://github.com/user-attachments/assets/836ef3c0-eb81-4dd3-a4be-5328384ecac9" />


If every breath is strained and painful, it could be a serious and potentially life-threatening condition. A pulmonary embolism (PE) is caused by an artery blockage in the lung. It is time consuming to confirm a PE and prone to overdiagnosis. Machine learning could help to more accurately identify PE cases, which would make management and treatment more effective for patients.

Currently, CT pulmonary angiography (CTPA), is the most common type of medical imaging to evaluate patients with suspected PE. These CT scans consist of hundreds of images that require detailed review to identify clots within the pulmonary arteries. As the use of imaging continues to grow, constraints of radiologists’ time may contribute to delayed diagnosis.

The Radiological Society of North America (RSNA®) has teamed up with the Society of Thoracic Radiology (STR) to help improve the use of machine learning in the diagnosis of PE.

In this competition, you’ll detect and classify PE cases. In particular, you'll use chest CTPA images (grouped together as studies) and your data science skills to enable more accurate identification of PE. If successful, you'll help reduce human delays and errors in detection and treatment.

With 60,000-100,000 PE deaths annually in the United States, it is among the most fatal cardiovascular diseases. Timely and accurate diagnosis will help these patients receive better care and may also improve outcomes.


Acknowledgments
The Radiological Society of North America (RSNA®) is an international society of radiologists, medical physicists, and other medical professionals with more than 53,400 members worldwide. RSNA hosts the world’s premier radiology forum and publishes two top peer-reviewed journals: Radiology, the highest-impact scientific journal in the field, and RadioGraphics, the only journal dedicated to continuing education in radiology.

The Society of Thoracic Radiology (STR) was founded in 1982. The STR is dedicated to advancing cardiothoracic imaging in clinical application, education, and research in radiology and allied disciplines. Continuing professional development opportunities provided by the STR include educational and scientific meetings, mentorship programs, grant support and award opportunities, our society journal, Journal of Thoracic Imaging, and global collaboration activities.

<img width="805" height="439" alt="Screenshot 2025-11-06 at 11 39 08 PM" src="https://github.com/user-attachments/assets/e059356a-97fb-4a60-bc77-66c8e904ba7d" />
<img width="756" height="593" alt="Screenshot 2025-11-06 at 11 39 23 PM" src="https://github.com/user-attachments/assets/4d0144c5-2016-4074-9a13-bbb2764d1859" />


<img width="768" height="527" alt="Screenshot 2025-11-06 at 11 39 40 PM" src="https://github.com/user-attachments/assets/74b85380-472b-41f9-a4c7-5b6fa8c825ba" />

Submission Format:

id,label df06fad17bc3_negative_exam_for_pe,0.5 df06fad17bc3_rv_lv_ratio_gte_1,0.5 df06fad17bc3_rv_lv_ratio_lt_1,0.5 df06fad17bc3_leftsided_pe,0.5 df06fad17bc3_chronic_pe,0.5 df06fad17bc3_rightsided_pe,0.5 df06fad17bc3_acute_and_chronic_pe,0.5 df06fad17bc3_central_pe,0.5 df06fad17bc3_indeterminate,0.5 eb3cbf4180b5,0.5 57b93aeb1b16,0.5 ca48991fcad3,0.5 c72c1f5763d4,0.5 26c67856a1e9,0.5 3c64e5645222,0.5 d3e59334bba4,0.5 be315623c913,0.5 74941ba7b035,0.5 70589c8529fb,0.5 etc.

<img width="511" height="439" alt="Screenshot 2025-11-06 at 11 40 11 PM" src="https://github.com/user-attachments/assets/3ddfaca8-8562-4fd5-ae5d-0fd03b821973" />

Data Contributors
Five research institutions provided large volumes of de-identified CT studies that were assembled to create the RSNA-STR Pulmonary Embolism CT (RSPECT) dataset.

AlfredHealth

Alfred Heatlh, Melbourne, Australia

Meng Law, MD
Jarrel Seah, MBBS
Adil Zia, MSc
Robin Lee, BRadMedImag
Helen Kavnoudias, PhD
KocU

Koç University Hospital, Istanbul, Turkey

Emre Altinmakas, MD
Serkan Guneyli, MD
Vugar Samadlı, MD
Seval Dincler
Ersan Sener
aimi

Stanford University | Center for Artificial Intelligence in Medicine & Imaging (AIMI), Stanford, CA - USA

Matthew Lungren, MD, MPH
Stephanie Bogdan
Mars Huang
UnityHealth

Unity Health Toronto, Toronto, Canada

Errol Colak, MD
Hui-Ming Lin, HBSc
Priscila Crivellaro, MD
Oleksandra Samorodova, MD
Blair Jones, MRT(R)
Hojjat Salehinejad, PhD(C)
Muhammad Mamdani, MPH, MA, PharmD


Universidade Federal de São Paulo (Unifesp) | Escola Paulista de Medicina, São Paulo, Brazil

Felipe C Kitamura, MD MSc
Nitamar Abdala, MD PhD
Henrique Carrete Junior, MD PhD
Ernandez Santos, BIT

<img width="764" height="513" alt="Screenshot 2025-11-06 at 11 41 18 PM" src="https://github.com/user-attachments/assets/9c80a6aa-34ad-4de7-b56b-f95c23fa283b" />
<img width="735" height="320" alt="Screenshot 2025-11-06 at 11 41 32 PM" src="https://github.com/user-attachments/assets/9e994f91-1c45-4133-8f04-4ec1da84dc12" />





Data Resource Paper:

Please cite this data resource paper if you plan to use this dataset.

Colak E, Kitamura FC, Hobbs SB, Wu CC, Lungren MP, Prevedello LM, Kalpathy-Cramer J, Ball RL, Shih G, Stein A, Halabi SS, Altinmakas E, Law M, Kumar P, Manzalawi KA, Rubio DCN, Sechrist JW, Germaine P, Lopez EC, Amerio T, Gupta P, Jain M, Kay FU, Lin CT, Sen S, Revels JW, Brussaard CC, Mongan J, The RSNA-STR Annotators and Dataset Curation Contributors. The RSNA pulmonary embolism CT dataset. Radiology: Artificial Intelligence. 2021 Jan 20;3(2):e200254. URL: https://pubs.rsna.org/doi/full/10.1148/ryai.2021200254

Citation:

Anouk Stein, MD, Carol Wu, Chris Carr, Errol Colak, George Shih, JeffRudie, John Mongan, Julia Elliott, Luciano Prevedello, Marc Kohli, MD, Phil Culliton, and Robyn Ball. RSNA STR Pulmonary Embolism Detection. https://kaggle.com/competitions/rsna-str-pulmonary-embolism-detection, 2020. Kaggle.

