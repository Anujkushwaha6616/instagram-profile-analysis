# Instagram Profile Analysis 📊

A Python-based data analysis project that reads Instagram profile information from a text file, processes the data, and extracts useful insights about Instagram profiles.

##  Project Overview

This project analyzes Instagram profile data such as:

* Username
* Number of posts
* Number of followers
* Number of following
* Profile name
* Page/category type
* Bio

The raw data is stored in a text file and processed using Python.

##  Features

The project can:

* Read Instagram profile data from a text file
* Split the raw data into individual profile records
* Extract profile information
* Convert follower/following values such as `K` and `M` into numbers
* Find the profile with the maximum number of posts
* Find the profile with the maximum number of followers
* Find the profile with the maximum number of following
* Find the total number of profile categories
* Display the available profile categories

##  Technologies Used

* Python
* Jupyter Notebook
* File Handling
* Lists
* Dictionaries
* Functions
* Loops
* Sets
* String Manipulation

##  Project Structure

```text
instagram-profile-analysis/
│
├── MYinstaAnalysis.ipynb
├── initialdata 6.txt
├── finaldata 6.txt
└── README.md
```

##  How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/instagram-profile-analysis.git
```

### 2. Open the project

Open `MYinstaAnalysis.ipynb` using:

* Jupyter Notebook
* JupyterLab
* VS Code

### 3. Keep the data file in the project folder

The notebook reads the Instagram data from:

```text
finaldata 6.txt
```

### 4. Run the notebook

Run the cells from top to bottom to perform the analysis.

## Example Analysis

The project can identify:

```text
Profile with maximum posts
Profile with maximum followers
Profile with maximum following
Total number of profile categories
Available profile categories
```

##  What I Learned

Through this project, I practiced:

* Reading data from files
* Processing raw text data
* Creating functions
* Working with lists and dictionaries
* Using sets to find unique categories
* String parsing and data conversion
* Basic data analysis using Python

**##  Future Improvements**

Some possible improvements are:

* Convert the processed data into a Pandas DataFrame
* Add graphs and charts
* Calculate average followers and posts
* Find profiles with the highest follower-to-following ratio
* Add more detailed Instagram insights
* Create a simple web interface for the analysis

