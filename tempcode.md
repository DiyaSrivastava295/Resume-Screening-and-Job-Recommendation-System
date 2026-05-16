# resume screening and job recommendation system

import pandas as pd
import numpy as np

from sklearn.feature_extraction.text import TfidfVectorizer
from sklearn.metrics.pairwise import cosine_similarity

# sample resumes and job descriptions

resumes = [
    "Python, SQL, data analysis, machine learning",
    "Java, web development, HTML, CSS",
    "AutoCAD, SolidWorks, mechanical design"
]

jobs = [
    "Data Analyst",
    "Frontend Developer",
    "Mechanical Engineer"
]
