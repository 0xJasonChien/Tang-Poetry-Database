# Creation and Application of a Parallel Corpus of Tang Poetry in Chinese, English, and Japanese

The Tang Poetry Parallel Corpus Research Project is a collaborative effort among faculty members from the Department of Applied English at National Kaohsiung University of Science and Technology (NKUST), the Interdisciplinary Program of High Tech, and the Department of English at National Changhua University of Education (NCUE). 
<br>
This project is funded and supervised by the National Science and Technology Council (NSTC). It aims to develop an integrated platform that combines Tang poetry texts, corresponding translations, and a multifunctional retrieval system for research and educational purposes.
<br>

The main features of this platform include:
- Designing a database architecture tailored to research needs.
- Providing robust search and retrieval capabilities.
- Visualizing data statistics (e.g., charts and graphs).
- Establishing a user-friendly data entry interface.
- Applying a Chinese word segmentation model to reduce manual workload for data entry personnel.

The project also involves students from the Department of Applied English, who participate in practical data entry and functionality testing to ensure the system meets academic standards.


## Technical Stack & Deployment

- **Backend**:
  - Used **Django** as the backend framework.
  - Utilized **Jieba** and **CkipTagger** for Chinese word segmentation, aiding students in entering accurate translation terms.
  - Applied **pypinyin** to analyze and aggregate pinyin usage patterns across dynasties, poetry collections, and individual poets.
  - Generated word clouds (using Python's wordcloud library on the backend) to visualize the frequency of poets, dynasties, and key vocabulary for comparative literary analysis
- **Frontend**：
  - **jQuery** for AJAX data fetching and DOM manipulation, based on data provided by the backend.
  - Interactive charts for frequency data and statistical summaries are rendered on the frontend using **Chart.js**, based on data provided by the backend.
- **Database**：MySQL
- **Server Deployment**：Hosted on a university server with Apache, I handled the full deployment including configuration, testing, and optimization.



## System Features

1. Data Retrieval and Search Functionality
   - Supports multi-condition searches, including:
     - Poem title
     - Author
     - Dynasty
     - Verses
   - Advanced search functions allow filtering by translation language and text features.

2. Visualization and Analysis
   - Generates various statistical charts and graphs:
     - Verse occurrence frequency
     - Author distribution ratios
     - Statistics of translation versions

3. Data Entry and Management
   - Provides an intuitive data entry interface.
   - Automatically performs Chinese word segmentation to reduce workload for data entry personnel.
   - Supports batch import and verification.

## 系統截圖
![screencapture-tang-nkust-org-2024-12-11-07_24_01](https://github.com/user-attachments/assets/95abca4b-1fb7-4758-b7aa-ef8289d2dca3)
![image](https://github.com/user-attachments/assets/c7a3567d-7de0-4459-93b9-57ce8a19ce60)
![image (1)](https://github.com/user-attachments/assets/d2ea9ff9-fd04-4968-ae0b-80a912ebbfe5)
![image (2)](https://github.com/user-attachments/assets/53f97e03-5989-496c-8615-2c4b852ae02a)
![image (3)](https://github.com/user-attachments/assets/86a0ad17-0422-43e0-8ef7-fb9beaf26f34)
