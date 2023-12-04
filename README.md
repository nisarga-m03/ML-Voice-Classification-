# Voice_Classification_ML
# Beginning
This project started as a team project with an aim to learn different machine learning models. The initial problem statement was to  Built a python application that analyses the sentiment behind the tone of the voice. Different features like tempo, beats, stft, mfccs, etc were extracted using Librosa from the GTZAN Genre Collection dataset.This project uses Machine Learning and  basic Deep Learning techniques.
# What next?
After this project, I went on learning more about computer vision and deep learning. Reading more and more about it, I started thinking if I could apply CNNs on the music data. Also I hoped that transfer learning would help me attain accuracy closer to the State of the art models on GTZAN dataset.
# Approach
1) Machine Learning :-
Features like  zero-crossing rate, power,tempo, beats, mfccs, loudness etc. are extracted from audio files using librosa library afterwhich the data is feed into the ML models to classify data.
2) Begining level - Deep Learning :-
Mel Spectrogram images are formed from audio files which are very strong features to discriminate the properties of two audio files. So, these images are feed into CNN model for classification into 10 genres.
# Raw data:
Download GTZAN Dataset from: https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification  
# Potray Music as Image
A very naive idea of mine was to simply plot the y values as shown below.

![image](https://github.com/nisarga937/Voice_Claaification_ML/assets/150679240/627047cc-940c-4efc-81f4-e038d54272f2)

By soon I realized that it won't just work as it doesn't give much information about tones. While going through different articles for visualizing music and decided to go for melspectograms(luckily having the same idea as mine),Fourier Transform,Spectrogram,Chroma features,Box Plot for Genres Distributions, Correlation Heatmap etc.

![image](https://github.com/nisarga937/Voice_Claaification_ML/assets/150679240/89b828e2-5dbe-4053-b8bc-29d7606bca64), ![image](https://github.com/nisarga937/Voice_Claaification_ML/assets/150679240/50ed20d2-850c-4590-ba8a-c4e3f88526cd), ![image](https://github.com/nisarga937/Voice_Claaification_ML/assets/150679240/637a3850-8e53-4026-88fa-167481c58935)
![image](https://github.com/nisarga937/Voice_Claaification_ML/assets/150679240/77988a1d-56d4-4897-b1de-81b0998d2bad)

These looked quite promising to me.

# Conclusion
In essence, this project has successfully demonstrated the viability of using machine learning for music genre classification. The findings and insights gained contribute not only to the understanding of audio feature importance but also open avenues for future research and development in the field of music informatics.

I extend my heartfelt thanks to Compsoft Technologies and TIE for the incredible opportunity to contribute to this impactful project. This experience has been instrumental in refining my skills and gaining a strong foothold in machine learning with Python. 




