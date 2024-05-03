****How to Start:****

1. Download the dataset from roboflow - https://universe.roboflow.com/majorproject-25tao/american-sign-language-v36cz/dataset/2/images?split=train​ in Pascal-Voc(.xml) format
2. Run the feature Extraction code first and please replace the path directories according to your path.
3. I created train_images, test_images and valid_images folders which are for the images and extracted features for objects saved in txt.
4. Point path in code to these above directories.(Not the starting cells).
3. save the output.csv for later Evaluation.

****Training the YOLOv5****

1. upload the train_images,valid_images in drive and open the collaboratory file and run the following commands.
2. It took me 11 hrs for training, you can use collab pro to have a smooth experience



****Testing the Model****

1. Download the exported model in ONXX format and point the file in Test_images.ipynb file.
2. Don't forget to point the output.csv file in code.
3. Second from last is to generate the text from the labels created either by images or videos.
4. Last cell will convert genrated text to audio.  



https://github.com/MST-369/Sign-Language-Interpreter/assets/145525421/376dff8f-0bb0-432c-9e61-925617de7fba

