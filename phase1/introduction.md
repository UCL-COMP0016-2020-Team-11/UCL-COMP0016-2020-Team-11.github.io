# Week October 17th 2020
- Gathering Requirements from clients.

## This is the introduction paragraph we received from the project introduction email.
UCL, GOSH and Avanade are working together on this second iteration of this open source project. This work will be led with the simulation team at GOSH. The project will involve building an editor with layers and interactive timeline hotspots that apply situated cognition 360 videos to a handful of human factors training sessions during a series of emergency scenarios. Speech transcription with Deepspeech or other local speech recognition should be included to generate searchable summary notes that allow you to jump through the timeline and position in 360, as well as generate multilingual text for all users. The open source project will reside in the NHS index at Apperta Foundation.

## This is the notes we took down when we had our first meeting with our clients.
- Avanade: Interesting ways of training our workforce
- 360 degrees based video training
- More close to affinity to getting the tasks done
- Built:  
- a web-based unity player
- A very lightweight episodes list in HTML
- This year:
- Cross platform electron app: player + editor 
- XML or JSON file format to store data about the 360 video
- Editor: timeline(plays from the start to finish with the video), interactive HTML layer on the top of the 360 video
- The coordinate space is mapped to the video field: if you start with a particular view point, that is the starting origin and so anyway you rotate in the 360 video, you would have that mapping of that layer.
- Pop up text-boxes, images, other videos 
- Define size of the field
- Event trigger: point trigger, area trigger; open the HTML layer with the interactive text, or actually take you to another video file
- Points would exist in the timeline( as you play the video)
- spacial coordinates for the layer of interactive text and images will be static in time(always be there), or manipulated in the timeline
- Tree diagram of the video and the json/xml file: if you click on a region, it would open another video
- Tree structure: parse the video chain and load into sequence
- Scenario: one decision, use a for something; another decision, use b for something and load another video
- User friendly for clinician 
- AGPL version 3 license 
