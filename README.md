# Mulberry_leaves_disease_prediction_CNN

 Steps to deploy and use model : 

1. Download the model from drive link :  https://drive.google.com/drive/folders/1gge1D7ik8QhZ8XspO6o_Q4bXQb89Z5M1?usp=sharing
2. Make a separate folder in Documents or Desktop
3. Move downloaded model into the folder
4. Add Apps.py file to same folder.
5. Copy the folder path.  open cmd or powerShell . change path to folder( cd folderpath )

then run the below commands

1. virtualenv venv
2.1 for cmd - 'venv\Scripts\activate'
2.2 for power shell-'.\venv\Scripts\Activate.ps1'
3. install streamlit if not installed
4. streamlit run Apps.py 

To run the colab notebook code

1. Create a new folder in your drive
2. Copy the dataset folder to it.
3. Mount the drive to colab notebook.
4. change the 
   path = "/content/drive/MyDrive/Mulbary_disease_prediction/Dataset/Mulberry_Data"
	to your folder.
