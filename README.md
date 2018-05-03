# Human Computer Interaction - Interactive Prototype


Interactive Prototype for a Movie Recommender System. Diego Iriarte


## Getting Started

1. Verify that you have HCI_DIS.zip file on MacOS, Windows or Linux System.

### Prerequisites

1. Anaconda.
    1.  For MacOs you can install using GUI or just using Terminal commands

        ```
        Use instructions from: https://docs.anaconda.com/anaconda/install/mac-os#macos-graphical-install
        ```
    
    2. For Windows
          
        ```
        Use instructions from: https://docs.anaconda.com/anaconda/install/windows
        ```
    3. Verify Anaconda installation, Run from Terminal
    
        ```
        python
        ```
       
       This should appear:
        
        ```
        Python 3.6.2 |Anaconda, Inc.| (default, Sep 21 2017, 18:29:43)
        [GCC 4.2.1 Compatible Clang 4.0.1 (tags/RELEASE_401/final)] on darwin
        Type "help", "copyright", "credits" or "license" for more information.
        ```
        
        Or at least the "Anaconda" and "3.6" keywords should be present in interpreters definition

2. Jupyter Notebook
    1. For MacOs you can install:
    ```
    python -m pip install jupyter
    ```
3. Install prerequisistes:
    1.  Run:
    
        ```
        pip install -r prerequisites.txt
        ```
        
### Getting documents

1. Open Terminal and go to project file zip file

```
cd { $project_file_path }
```

2. Unzip HCI_DIS.zip file

```
unzip -a HCI_DIS.zip
```

3. Alternatively, by using github repository
```
git clone https://github.com/Diegogab16/HCI_DIS.git
```

## Running Information Visualization System

1. Go inside HCI_DIS's directory

```
cd HCI_DIS
```

2. Run Model

```
jupyter notebook
```

### Information Visualization - Infoviz
1. Open Notebook python file "0. Infoviz.ipynb"
2. Execute every cell, by clicking the "Run" button on the top bar or by pressing "shift" + "return" from the keyboard. After executing the last cell, it will display the infoviz in the same notebook.



## Folder Structure

The folder has the following structure:

 * "0. Infoviz.ipynb"
    * Python notebook that executes the information visualization system.
 * "1. ALS.ipynb"
    * Python notebook that executes the alternating least squares algorithms for matrix factorization.
 * "2. Representation.ipynb"
    * Python notebook that builds the heatmaps of the ratings and the 3D scatter plots for user and item matrices.
 * dataset
     * movielens100k.csv
        * main csv file containing the ratings.
     * movies.csv
     * uitem.csv
     * uitem1.csv
     * uuser.csv
        * Other csv files contain information about users and movies.
 * helpers.py
     * General helper methods to load and preprocess data.
 * pickles
     * final_ratings.pkl
     * item_features.pkl
     * labels.pkl
     * original_ratings.pkl
     * user_features.pkl
     * valid_moviesgenre.pkl
     * valid_moviesnames.pkl
     * valid_usersinfo.pkl
     * X_tsne.pkl
     * Y_tsne.pkl
        * python objects saved in pkls.
 * pictures
     * matrix_factorization.png
     * movies.png
        * images loaded in the Infoviz.
 * plots.py
    * Functions for plotting the data.
 * prerequisites.txt
    * Prerequisites file, it contains all packages to be installed using pip
 * README.md (README File)


## Author

* **Diego Iriarte**

