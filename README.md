# Audio-StutterSyllable-Labeling-System
Audio Stutter/Syllabe Labeling System (.ASSLS) file format

Due to the lack of any stuttering speech labeling systems and datasets on the internet. We decided to create our own Open Source System built upon JSON to allow easy modification and access

This system is intended to be used in conjunction with audio files (**.wav**, **.mp3**, **.flac** etc..)

<br>

The .ASSLS file format can store
* Audio Timestamp Annotations
* Word / Syllable based Annotations 


Audio Timestamp Annotations are pretty straightfoward ( label, starting_timestamp, ending_timestamp )

Word / Syllable based Annotations require external transciption services 


<br>
<br>

### Example Dataset File Structure
- Dataset
  - recording_7353
    - audio.wav
    - data.assls
  - recording_374929
    - audio.wav
    - data.assls



