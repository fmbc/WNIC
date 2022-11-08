# WNIC

1. Connect 2 HackRF one (Radio half-duplex Transceiver) using [GNU Radio](https://github.com/gnuradio)

2. Repeat the abnormal behavior (nodding of the head) between 2 HackRF one and extract the .wav file

3. Analyze .wav files using [Audacity](https://github.com/audacity)

4. Use [wav2csv.py](http://wav2csv.py/) to convert .wav files to .csv files and analyze them
    - Files converted by [wav2csv.py](http://wav2csv.py/) could not be uploaded due to the GitHub file size limit.
    
5. Analyze .wav files with Python using Colab
    <img width="80%" src="{이미지 경로}"/>
6. Based on step 5, write anomaly detection code

7. Use piezo buzzer for the Alarm sound , [twilio](https://www.twilio.com/) for text transmission
