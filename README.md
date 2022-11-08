# WNIC

1. Connect 2 HackRF one (Radio half-duplex Transceiver) using [GNU Radio](https://github.com/gnuradio)

2. Repeat the abnormal behavior (nodding of the head) between 2 HackRF one and extract the .wav file
    <img width="80%" src="/rpic/environment.png"/>
    <img width="80%" src="/rpic/gnuradio.png"/>

3. Analyze .wav files using [Audacity](https://github.com/audacity)

4. Use [wav2csv.py](http://wav2csv.py/) to convert .wav files to .csv files and analyze them
    
5. Analyze .wav files with Python using Colab
    <img width="80%" src="/rpic/colab.png"/>
6. Based on step 5, write anomaly detection code

7. Use piezo buzzer for the Alarm sound , [twilio](https://www.twilio.com/) for text transmission
