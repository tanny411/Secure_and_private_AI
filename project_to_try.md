### Berenice 6:23 PM
EmoAR
Facial expression recognition and Augmented Reality (AR)
Watch our demo video of the Android AR app: https://www.youtube.com/watch?v=Ezcn6U7Bz2U
Get the Android app: https://www.dropbox.com/s/sp8fc47jjhfs009/EmoAR_beta1_0.apk?dl=0
(Check first if your device supports ARCore)
Try our web app EmoAR: https://emoar.herokuapp.com/ (without AR)
Go to our GitHub
https://github.com/aksht94/UdacityOpenSource/blob/master/EmoAR/README.md
Project summary:
EmoAR is a mobile Augmented Reality (AR) application that aims to recognize human facial expression in real time and to overlay virtual content according to the recognized facial expression.
1. EmoAR may help people with Asperger syndrome and autism in learning about the expression of a face and will enhance robotic projects related to therapies that help autistic people to socialize.
2. In social media apps like Instagram, this could be used to suggest emojis, avatars, artistic visual content which suit the detected facial expression, so that the user can take a selfie with overlaid emojis, avatars and/ or artistic visuals.
3. It may be used as a HR tool.
The live AR camera stream of an Android device is input to a segmentation tool (using tiny YOLO) that detects faces in the video frames in real time. The detected areas with a face are fed into a model that was trained on the public FER dataset from Kaggle. The facial expression of the detected face is determined in real time by using our trained model. 
Depending on the model prediction, different virtual content overlays the face and adapts to the face's position. This virtual augmentation of a face is done with Augmented Reality (ARCore).
A project by team #sg_speak_german:
Mateusz Zatylny, @Mateusz (study group moderator)
Berenice Terwey, @Berenice (co-moderator)
Akash Antony, @Akash Antony
Calincan Mircea Ioan, @Calincan Mircea Ioan
      
Special thanks to @Joanna Gon for her valuable help during the project preparation.

### Vee 6:43 PM
1.Project Title: Using Embeddings and CNN for document classification
2.Project Summary: The project employs three methodologies. First, pretrained word embeddings were loaded. Second, entire news articles were classified by fine-tuning the pretrained embedding. Finally, a convolutional neural network  was used to capture the spatial relationships between words. 
3. Link of Project: https://github.com/aksht94/UdacityOpenSource/tree/master/Vee

### Ingus Terbets:penguin_dance: 7:48 PM
 :cloud: Project: Smog detection
 :cloud: Project Summary:
Smog Detection project was a collaborative team effort between Facebook Secure and Private AI Scholars on #sg_planetearth.
The sudden appearance of smog and/or fog on the highway often causes serious and sometimes fatal accidents. Smog is an agent for severe air pollution. It can aggravate health problems including problems with breathing and sleeping, as well as it can inversely damage plants and forest cover.
Future applications
Our model is already deployed live and can be tested here: https://smog4000.onrender.com/.
By using traffic cameras and training a model to recognize the smog/fog patterns, we can automate the alert and send a notification promptly. When smog/fog appears, the system notifies drivers who are within specified range about an upcoming “obstacle”.
In any practical situation, other components need to be taken into consideration as well. For example, the presence of flying birds and any type of material that will block the camera view. To identify the range of vision, sensors need to be added to the solution.
Results:
* Creating a unique Smog/Clear dataset with 4000 images
* PyTorch smog detection model,  accuracy 0.99
* Keras smog detection model, accuracy: 0.99
* Fast.ai smog detection model, accuracy: 0.995
* Web app: https://smog4000.onrender.com/
 :cloud: Team Members :
  Shudipto Trafder,    @Shudipto Trafder
  Berenice Terwey,    @Berenice
  Agata Gruza    @Agata [OR, USA], [OR, USA]
  Ingus Terbets,    @Ingus Terbets
  Akash Antony,    @Akash Antony
  Alexander Villasoto,    @Alexander Villasoto
  Pooja Vinod,    @Pooja Vinod
  Ramkrishna Acharya,    @Viper
  Sourav Kumar,    @sourav kumar
  George Christopoulos,    @George Christopoulos
  Sayed Maheen Basheer,    @Sayed Maheen Basheer
  Abhishek Lalwani,    @Abhishek Lalwani
  Laura Truncellito,    @LauraT
 :cloud: Project related images: Images of our dataset and the web app interface are attached.
 :cloud: Link of our project:
Project showcase repository: https://github.com/aksht94/UdacityOpenSource/tree/master/SmogDetection

### Shubhendu Mishra:tensorflow_pytorch: 8:21 PM
Project Title : Real Time Sign Language Gesture Recognition
Team Members: @Shubhendu Mishra @Munira Omar @Bhadresh Savani @Anju Mercian @Ruchika Khemka @Aarthi Alagammai @Marwa
Project Summary: This project involves detecting of Sign Language Gestures from a video and translating them. Existing works are doing this on pre-recorded videos, whereas we are trying to detect gestures in real time from a mobile front camera. The raw videos for training of gestures will have the faces of people, we have to use Federated Learning , i.e. train the model on the mobile devices and upload the updated weights to the server.
Project Related Images:
Link to the project: https://github.com/aksht94/UdacityOpenSource/tree/master/Real%20Time%20Sign%20Language%20Gesture%20Recognition

### Diganta 9:06 PM
Project Title: Echo
Team Members - @Aleksandra Deis and @Diganta
Project Summary - With advancement in theoretical mathematical and deep learning based research, new and more optimized algorithms are being proposed which beat benchmarks, however, these algorithms are not available in the trending deep learning frameworks to easily use in models. Echo is a package containing all SOTA machine learning algorithms starting from activation functions (Mish, Mila, Beta Mish, Swish, SQNL and 30 more) , Optimizers (Ranger, RADAM , Superconvergence, AdamW) and many more which are not available in Keras, TensorFlow and Torch. Echo allows lazy one line import for all these algorithms in any of the models in Keras, Torch or TensorFlow. We have just released the version 1 containing all activations. You can simply install using pip.
pip install echoAI
Upcoming releases will contain Optimizers, Loss Functions, Custom Layers, Custom Metrics, Encrypted Weights, SOTA models, etc.
Readthedocs here - https://echo-ai.readthedocs.io/en/latest/
PyPi page - https://pypi.org/project/echoAI/
Link - https://github.com/aksht94/UdacityOpenSource/tree/master/EchoAI 

### Seeratpal K. Jaura 9:34 PM
:udacity:     Project Title:
         Face Detection Project (Wonder_Vision)
:udacity:     Team Members  :
          Abhishek Tandon (@Abhishek Tandon )
        Alejandro Galindo (@Alejandro Galindo )
        Seeratpal K. Jaura (@Seeratpal K. Jaura)
        Sourav Das (@Sourav)
        Agata Gruza (@Agata [OR, USA])
        Rupesh Purum (@Rupesh Purum )
        Joyce Obi (@Joyce Obi)
:udacity:     Project Summary:
               In this project, one-shot learning with Siamese Network is implemented using PyTorch. The objective of the project is to calculate the similarity between two facial images. Face detection and face recognition is being employed by many companies in various applications. We built this project with a focus toward the education domain. The application would work as a visual attendance/login system allowing it to Carry out the classroom attendance by recognizing students present in the class. Allowing students to use their face for logging in to online course platforms, such as Udacity.
The next update on our application would allow it to track students as they access  the online course platform, enabling to gather metrics such as student attentiveness. These metrics would then be passed back to the course platform administrators. These metrics can be used to redesign course material so that it is better suited to students, providing a more of a 'personalized education'.
While collecting metrics is beneficial to both parties, student privacy is a major concern here. Using differential privacy we can make sure that student privacy is protected.
:udacity:     Project Video :
           https://github.com/JauraSeerat/Wonder_Vision_Face_Detection/blob/master/assets/code4.gif
:udacity:     Link to project:
           https://github.com/aksht94/UdacityOpenSource/tree/master/Wonder_Vision_Face_Detection

### SusanW 10:07 PM
:hospital:1. Project Title:
         Depression Detection using Twitter Data (and PyTorch)
:hospital:2. Team Members:
          @SusanW, @Marwa, @Labiba, @Mohona, @Aarthi Alagammai, @Munira Omar
:hospital:3. Project Summary:
          Our goal is to create a tool that will predict depression based on users' tweets and incorporate strategies to help alleviate their mood while maintaining privacy.
It can be applied in the following aspects:
          1. Can be used into mobile input devices such as GBoard where our tool will predict based on users' tweets while using already applied federated data of GBoard
          2. Later,  if depression is detected, GBoard may trigger the display of advertisement for self-care chatbots such as Woebot, a medically recognized tool to assist users in recovery from anxiety and depression.
         We are deeply inspired by this blog by @anne :sparkling_heart: : (https://towardsdatascience.com/you-are-what-you-tweet-7e23fb84f4ed?gi=94b619b96dbe)
:hospital:Our contribution so far:
          1. create a high-quality dataset containing 2500+ tweets and their target labels, indicating the likelihood of depression based on the text. This involved scraping twitter for tweets based on depressive hashtags search, applying pre-processing techniques to remove false positives, removing the hashtags (to force the model to evaluate tweet content) and manually review the resulting dataset. This dataset is concatenated with another twitter dataset based on specific emotional categories, resulting in a final dataset that is purpose-built for depression identification.
          2. create a deep learning model based on PyTorch, using Glove word embedding, bi-directional GRU and Concat-pooling (ave and max pool)
:hospital:Future work:
          1. experiment with different text classification models to achieve higher accuracy
          2. increasethe size of the twitter depression dataset
          3. investigate ideas on how to incorporate the model into an end to end pipeline and ensure user privacy is preserved through federated learning
:hospital:4. Link of our project
         (https://github.com/aksht94/UdacityOpenSource/tree/master/depression-detection)

### Venkatesh 10:34 PM
1. Project title: Deep Galaxy
2. Team members: @Venkatesh @Diganta @Anshu Trivedi @Mushrifah Hasan @Arka @Disha Mendiratta @sourav kumar @Shivam Raisharma @Xerous
3. Project Summary: Deep Galaxy is a Computer Vision based project hosted as a Web API where an user can input the valid image of any galaxy and the Web API shall classify the Galaxy into it's specific shape-variant class which includes: E0, E3, E7, S0, Sa, Sb, Sc, SBa, SBb, SBc. (E- Elliptical, S - Spiral, SB - Barred Spiral)
The Classifier will also provide additional information regarding the mass/ density of the Galaxy and the Galaxy Name along with it's year of discovery. Furthermore, based on the spectrum of the Image being in either SHO/ SHN/ SHHe*, it will also provide information regarding the max chemical gaseous composition of the galaxy.
SHO - Sulphur, Hydrogen, Oxygen SHN - Sulphur, Hydrogen, Nitrogen SHHe - Sulphur, Hydrogen, Helium
4. Project images: Uploaded in the thread.
5. Link to the project: https://github.com/aksht94/UdacityOpenSource/tree/master/Deep%20Galaxy

### Shaistha 1:39 AM
1. Project Title:  Real Time Object Detection Using Pytorch
2. Project Summary:
   This project is an attempt, to implement Real Time Object Detection using Yolo v3 and OpenCv and Pytorch from scratch. The aim is to create an android app which can be used to detect object in real time with an option to detect specific object from within the set of images or video, and maybe on later stages use the object to reverse search the internet for information and facial recognition.
Social Impact
This app is mainly designed for research purpose and for learning. The featured audience is any developer interested in Computer Vision and also for AI Security/Data researchers as this can be used to find the images or video for specific object from the pile of images and videos! Thus, helping in large data segregation tasks or identification tasks related to forensics etc.
3. Link: https://github.com/aksht94/UdacityOpenSource/tree/master/Shaistha/real_time_object_detection_using_pytorch

### Oudarjya Sen Sarma 2:08 PM
:torch_heart_changing_slow: 1. Project Title: Lane Detection(#sg_wonder_vision)
:torch_heart_changing_slow: 2. Team Members :
@Astha Adhikari
@Oudarjya Sen Sarma
@Mohammad Diab
@shivu
@Vigneshwari
:torch_heart_changing_slow: 3. Project Summary: This project focuses on identification of lanes of the road which we achieved through using various approaches and frameworks including but not limited to OpenCV, PyTorch etc. This model can be used in drones , self driving cars, surveillance systems , so its is primarily related to 'Safety'. We've also tried implementing Car Detection & YOLO Object Detection.
:arrow_right: We built a web app using flask and built an end to end system.
:arrow_right: Pytorch Transfer Learning for car detection: We tried using vgg model for detecting the car using transfer learning.We could not completely integrate it, we have a kept a small notebook for that.
:arrow_right: Yolo object detection in video: We also tried the object detection in a video using yolo.
:arrow_right: We want to merge this project with other projects in #sg_wonder_vision channel to create a mass useful project.
:torch_heart_changing_slow: 4. Attach project related images/videos (if any):
:arrow_right: Data we collected ourselves: https://drive.google.com/drive/folders/104dm38NWxzktm2aPwB2hjAg7aAtzkltj
:arrow_right: Original Image: https://gyazo.com/1502175addbef38f5ec230f95bc410cc
      Detected Image: https://gyazo.com/d617effcc953f61a98abaf1e8e1b8dad
:arrow_right: YOLO Object Detected video: https://drive.google.com/file/d/1_A4do0xXHP3PGEHGgjqDUz1Igm8H9bos/view?usp=sharing
:arrow_right: Workflow: https://gyazo.com/457aa87002915d955d4f24ed751662cf
:arrow_right: Use Case: https://gyazo.com/f2548b6c37802a3427a3aa89e448cf27
:torch_heart_changing_slow: 5. Link of your project (link of your project in the main repo): https://github.com/aksht94/UdacityOpenSource/tree/master/wonder_vision_lane_detection

Samuela Anastasi 10:23 PM
Project Title: YelpMeKnow
Project Summary:
YelpMeKnow is a text classifier model, which leverages the power of Google's BERT pretrained models through the Hugging Face Pytorch implementation.
Specifically the model used is: BERT-Base-Uncased: 12-layer, 768-hidden, 12-heads, 110M parameters.
The model performs a Sentence Classification analysis of the customer satisfaction, (positive vs. negative reviews), contained in Yelp Review Polarity Dataset.
The dataset containes 560,000 training samples and 38,000 testing samples, but due to limited resources and time I'm training/validating and testing on a really small subset of it.
Project data:
Train data size: 20000 ~ 3.6% of training samples
Test data size: 2000 ~ 5.3% of testing samples
Epochs: 1
Matthew's correlation coefficient: ~ 0.86
The accuracy of predictions is evaluated using Matthew's correlation coefficient, a metric used by the wider NLP community to evaluate performance in similar tasks.
The Matthew's correlation coefficient is in essence a correlation coefficient value between -1 and +1. A coefficient of +1 represents a perfect prediction, 0 an average random prediction and -1 an inverse prediction.
Project link: https://github.com/aksht94/UdacityOpenSource/tree/master/Samuela_Anastasi

### Dharmendra Choudhary 2:52 PM
1. Project Title: T-shirt Design Using GAN and Neural Style Transfer
2. Team Members (if it is a team) : @Dharmendra Choudhary
3. Project Summary:
My Aim with project was to training different GAN architectures and learn about GAN. I have implemented basic version of GAN ( vanilla GAN and DCGAN) as part of reading papers in #reading_paper_discuss. Then in #sg_project-t-shirt I have implemented neural style transfer and conditional GAN and CycleGAN ( work in progress, need to train more for getting better results). I have worked on computer vision 2 year back and it gave opportunity to learn new things happening computer vision.
While implementing this project I have gone through more than 6 papers and 5 GitHub repos. It was very challenging to stabilize training in GAN specially CycleGAN, But many medium blogs and repo by Soumith Chintala helped me lot.
Fast neural style transfer gave really good results and I trained using existing repo and explored. It really inspired me to implement other GAN architectures for getting better results. I will continue my journey of GAN design in future
4. Attach project related images/videos (if any):
5. Link of your project (link of your project in the main repo): https://github.com/aksht94/UdacityOpenSource/tree/master/Dharmendra_Choudhary/GAN_design
