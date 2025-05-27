# Decoding-Digital-Deception
Running application locally on your machine 
Prerequisite 
1. Copy your trained model to the models folder. 
	You can download our trained models from the Google Drive"https://drive.google.com/drive/folders/1UX8jXUXyEjhLLZ38tcgOwGsZ6XFSLDJ-" or you can train your models using the steps mentioned in Model Creation directory. 

# Step 1 : 
Unzip the PROJECT file
# Step 2: 
    Create virtualenv  python -m venv venv 
# Step 3:
    Activate virtualenv venv\Scripts\activate
# Step 4:
    Install requirements pip install -r requirements.txt 
# Step 5:
    Copy Models 

Copy your trained model to the models folder i.e Django Application/models/ 
	• 	You can download our trained models from Google Drive-https://drive.google.com/drive/folders/1UX8jXUXyEjhLLZ38tcgOwGsZ6XFSLDJ-
Note : The model name must be in specified format only 
i.e model_84_acc_10_frames_final_data.pt. Make sure that no of frames must be mentioned after certain 3 underscores _ , in the above example the model is for 10 frames. Step 6: Run project python manage.py runserver 

