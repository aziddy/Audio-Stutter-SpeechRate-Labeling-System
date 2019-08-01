# Audio-StutterSyllable-Labeling-System
Audio Stutter/Syllabe Labeling System

Due to the lack of any stuttering speech labeling systems and datasets on the internet. We decided to create our own Open Source System built upon JSON to allow easy modification and access

Which allows storage in any string format ( **.databases**, **.assls**, **.txt** etc) and allows for easy custom parsers to be made





<br>

### The System can store
* Audio Timestamp Annotations
* Word / Syllable based Annotations 

<br>

Audio Timestamp Annotations are pretty straightfoward ( **label**, **starting_timestamp**, **ending_timestamp** )

Word / Syllable based Annotations require external transcription services 


<br>
<br>

### Example Dataset File Structure

This system is intended to be used in conjunction with audio files (**.wav**, **.mp3**, **.flac** etc..)


- Dataset
  - recording_7353
    - audio.wav
    - data.assls
  - recording_374929
    - audio.wav
    - data.assls



