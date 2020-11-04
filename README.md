# Speech Measure Project Application

This is part of speech rate measure project. <br />
In this client-server web-application , you can upload/record audio file , and check speech rate.
Speech rate in this app is measured in SPS (Syllables Per Second). <br />

The calculated speech rate is the output prediction of trained neural network, design to detect vowels in audio files contains speech.
More information can be found [here](https://github.com/Jenny-Smolensky/ML-SpeechRateMeasure.git). <br />

## Sub Modules
This project contain the client and server applications:

* ### speech-rate-client
    Code for the client side of the web-application. <br />
    For further documentaion go to [README](https://github.com/Jenny-Smolensky/speech-rate-client/blob/7e65288626a45d93b674ddae7826989c4198dcb5/README.md). <br />
    The application can be seen [here](https://speech-rate.firebaseapp.com/) Or download windows installion file [here](https://github.com/Jenny-Smolensky/speech-rate-client/blob/main/desktop_installer/SpeechRateAppInstaller.exe).

* ### SpeechMesaureServer
    Code for the Server side of the web-application - get the audio file from client and run the model to predict SPS.  <br />
    For further documentation about the server go to [README](https://github.com/almog1/SpeechMeasureServer/blob/main/README.md) <br />
    Or directly download windows installion file  [here](https://drive.google.com/file/d/1HmAMrjYERSt3YRbyx6ZYC2FXN5vFjewn/view?usp=sharing). <br />

## Authors

**Jenny Smolensky** , **Almog Gueta**
