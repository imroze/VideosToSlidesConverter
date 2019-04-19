# SlideThruLectures
A Python and OpenCV based tool that uses Computer Vision algorithms and Text Parsing to convert Online Lecture/MOOC Videos and Transcripts into auto-generated Slides with images and caption text, to facilitate easy and effective note-taking, learning, revision, compilation, referencing, skimming, comparsion and analysis of online course content.

##Requirements:
- Python 3
- OpenCV 3
- NumPy
- PIL
- imutils
- PyPPTX

## Usage:

#### Inputs and Output:
- The program takes a video file or folder of video files as input and generates a PPTX file with slide images extracted from one video or images from all videos in the video folder joined together.
- The program also supports using folder with .srt format transcript files to extract caption text from videos and embed it as textual slides in the PPT slides.

#### Adding the Input Data Files:
- Example video/transcript data is present for testing.
- To change or add new videos/transcript data as input place a folder with that data inside the Data folder in EdTechProject. 
- The data for a lesson or course would include 2 folders inside the Data folder, a video folder for video files and a transcript folder for .srt transcript files corresponding to the video files arranged in the same order. If a Transcript/Subtitles folder has to be used then its name must contain "Subtitles" and names of file should be same as corresponding videos eg: xyz1.mp4 and xyz1.srt. 
- Using the transcript text in slides is optional which can be enabled using GUI. Having a video folder is enough too.

### Running the Program:

- Clone or Download the github repo.
- Open the ETProject folder in command prompt/terminal.
- Enter "pip install -r requirements.txt" to install package dependencies automatically or install the mentioned packages manually using following pip commands:
- pip install numpy
- pip install opencv_python
- pip install pillow
- pip install imutils
- pip install pypptx
- Run the program by entering "python SlideThruLectures.py" or through any IDE/editor without giving arguments. 
- Use the GUI to generate the output by loading files and setting options and parameters if required