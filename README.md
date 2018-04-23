# ADS Project 5: 

Term: Spring 2018

+ Team 5
+ Projec title: Lorem ipsum dolor sit amet
+ Team members
	+ Yanjun Lin
	+ Yu Tong
	+ Xiuruo Yan
	+ Linna Yu
	+ Mingming Liu
	
![image](figs/1.jpg)
+ Project summary: Music is a method that we can communicate with the other people. We express our happy, sad and anger. However, there are mathematical relationships behind it, like the octaves, keys and scales. Because of this precise relationship, we can use computer to generate music.
    In this project we implement recurrent neural network trained to generate pop music. The model, which uses LSTM layers and draws inspiration from convolutional neural networks, learns to predict which notes will be played at each time step of a musical piece.We used TensorFlow deep learning frame work and worte code in python. We need miod package to download midi files and the following packages are required: 
    
    **mido**, **bs4**, **lxml**. 
    
    The main document is used to train the model. Here, you can use our pre-trained model or change arguments in the main file to train a new model. After training this model, we can use the predict part to predict new songs. 
    
    The useage of the following file is listed below: 
    
    (1)model.py is for the biaxial model class.   
    
    (2) data.py is used to clean data for the model.  
    
    (3) midi_scraper.py is for scrape midi files. 
    
    (4)midi_to_statematrix.py is to read the midi files and translate it to not state matrix. 
    
    (5)operations.py is for truning a python function to tensorflow operation. 
    
    (6)cache.py is used to save the input format of statematrix, which enables us train faster whithout translating data every time.
	
**Contribution statement**: ([default](doc/a_note_on_contributions.md)) All team members contributed equally in all stages of this project. All team members approve our work presented in this GitHub repository including this contributions statement. 

Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.
