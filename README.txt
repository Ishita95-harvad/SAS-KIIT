South Asian Sounds - KIIT

Overview
The South Asian Sounds - KIIT dataset is a curated collection of 9,450 labeled audio segments representing diverse soundscapes from South Asia. It is designed for audio classification tasks and includes sounds from musical instruments, religious chants, environmental noises, and human activities.

Website: https://sas-kiit.netlify.app/

Dataset Details
- Total Audio Files: 9,450
- Format: WAV
- Duration: Each segment is 4 seconds long
- Number of Classes: 21
- File Naming Convention: Class-ID_Class-Name_Segment-Number.wav
- Storage: Distributed randomly across 10 folders
- Metadata File: Provided as a CSV

Classes and Labels
Class ID - Class Name
   0     - Tanpura
   1     - Traditional Song
   2     - Railway Engine
   3     - Children Class Noise
   4     - Harmonium
   5     - Dhak
   6     - Tabla
   7     - Azan
   8     - Church Prayer
   9     - Irrigation Engine
  10     - Ektara
  11     - Launch Engine
  12     - Flute
  13     - Buddhist Prayer
  14     - Fish Market
  15     - Tiger
  16     - Elephant
  17     - Kalboishakhi Storm
  18     - Sanatan Religion Aroti
  19     - Rickshaw Horn
  20     - Afghanistan Pashto Music

Metadata Description
The dataset includes a CSV metadata file with the following columns:
- slice_file_name: Segment name
- slicing_start_time: Start timestamp of the segment
- slicing_end_time: End timestamp of the segment
- ClassID: Label (0 to 20)
- Class_name: Corresponding class name
- folder: Folder where the segment is stored


Citation
If you use this dataset in your research, please cite the following paper:
Paper Link: https://ieeexplore.ieee.org/document/10829485

@inproceedings{chatterjee2024south,
  title={South Asian Sounds: Audio Classification},
  author={Chatterjee, Rajdeep and Bishwas, Pappu and Chakrabarty, Sudip and Bandyopadhyay, Tathagata},
  booktitle={2024 4th International Conference on Computer, Communication, Control & Information Technology (C3IT)},
  pages={1--6},
  year={2024},
  organization={IEEE}
}


Contributors
- Sudip Chakrabarty
- Pappu Bishwas
- Rajdeep Chatterjee
- Tathagata Bandyopadhyay


For further inquiries, please refer to our website.

This dataset is intended for research and academic purposes. Proper citation is required for any usage in publications.
