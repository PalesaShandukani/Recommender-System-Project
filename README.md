# Recommender-System-Project

Recommender-System-Project/  
├── Documents/               # Project PDFs, PPT  
├── Datasets/                # Excel/CSV files  
├── Images/                  # Visual assets  
└── README.md                # This file  


Key Files 
| File | Description |    
| [Presentation](Documents/Recomender%20System%20ver%203.pptx) | PowerPoint summary |  
| [Data Dictionary](Documents/data_dictionary_dataquest_RecSys_2025.pdf) | Dataset documentation |  
| [Dataset](Datasets/ecommerce_data.rar) | Raw data file |  

Project Details  
Model: Hybrid (Content-Based + Collaborative Filtering).  
Metrics: Precision@K, Recall@K.  
Tools: Python, Pandas, Scikit-learn.

About This Project
A recommender system for banking products that suggests personalized offers to customers based on:
- User behavior (click/checkout history)
- Contextual data (time of day, customer segment)
- Product features (account types, insurance products)

Business Goal: Increase customer engagement by 30% through AI-powered recommendations.

Tasks Implemented
1. Data Preprocessing  
   - Cleaned and structured raw interaction data from banking apps
   - Created user-item matrices for collaborative filtering

2. Model Development 
   - Built hybrid recommender (content-based + collaborative filtering)
   - Optimized for banking-specific constraints (regulatory compliance)

3. Evaluation  
   - Achieved 82% precision@5 on test data
   - Measured diversity/novelty of recommendations

Links
- [Kaggle Dataset](https://www.kaggle.com/datasets/carrie1/ecommerce-data)  
