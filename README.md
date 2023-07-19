# ACE_NLP_Jul23
NUS Advanced Computing for Executives<br>
Professional Certificate in Text Processing<br>
Advanced Deep Learning<br>
July 20-21 2023


<br><br>


### Cloud Machine : Google Colab (Free GPU)

* Follow this Notebook installation :<br>
https://colab.research.google.com/github/xbtrainings/ACE_NLP_Jul23/blob/main/codes/installation/installation.ipynb

* Open your Google Drive :<br>
https://www.google.com/drive

* Open in Google Drive Folder 'ACE_NLP_Jul23' and go to Folder 'ACE_NLP_Jul23/codes/'<br>
Select the notebook 'file.ipynb' and open it with Google Colab using Control Click + Open With Colaboratory



<br><br>

### Local Installation for OSX & Linux

* Open a Terminal and type


```sh
   # Conda installation
   curl https://repo.continuum.io/miniconda/Miniconda3-latest-Linux-x86_64.sh -o miniconda.sh -J -L -k # Linux
   curl https://repo.continuum.io/miniconda/Miniconda3-latest-MacOSX-x86_64.sh -o miniconda.sh -J -L -k # OSX
   chmod +x miniconda.sh
   ./miniconda.sh
   source ~/.bashrc

   # Clone GitHub repo
   git clone https://github.com/xb-trainings/ACE_NLP_Jul23.git
   cd ACE_NLP_Jul23

   # Install python libraries
   conda env create -f environment.yml
   source activate deeplearn_course

   # Run the notebooks
   jupyter notebook
   ```




### Local Installation for Windows 

```sh
   # Install Anaconda 
   https://repo.anaconda.com/miniconda/Miniconda3-latest-Windows-x86_64.exe

   # Open an Anaconda Terminal 
   Go to Application => Anaconda3 => Anaconda Prompt 

   # Install git : Type in terminal
   conda install git 

   # Clone GitHub repo
   git clone https://github.com/xb-trainings/ACE_NLP_Jul23.git
   cd ACE_NLP_Jul23

   # Install python libraries
   conda env create -f environment_windows.yml
   conda activate deeplearn_course

   # Run the notebooks
   jupyter notebook
   ```







<br><br><br><br><br><br>