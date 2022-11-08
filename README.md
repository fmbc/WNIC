# WNIC

1. Connect 2 HackRF one (Radio half-duplex Transceiver) using [GNU Radio](https://github.com/gnuradio)

2. Repeat the abnormal behavior (nodding of the head) between 2 HackRF one and extract the .wav file<br />
    <img width="60%" src="/rpic/environment.jpeg"/>

3. Analyze .wav files using [Audacity](https://github.com/audacity)

4. Use [wav2csv.py](http://wav2csv.py/) to convert .wav files to .csv files and analyze them<br />
    <img width="60%" src="/rpic/wav2csv.png"/>
    
5. Analyze .wav files with Python using Colab<br />
    <img width="60%" src="/rpic/colab.png"/>
    
6. Based on step 5, write anomaly detection code

7. Use piezo buzzer for the Alarm sound , [twilio](https://www.twilio.com/) for text transmission<br />
    <img width="60%" src="/rpic/buztwi.gif"/>
