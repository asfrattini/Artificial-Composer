![header_image](https://github.com/asfrattini/Artificial-Composer/blob/master/images/presentation.jpg)

By:
  [Anna Sofia Frattini](https://www.behance.net/Asfrattini)
  & 
  [Alejandro Calderón](https://www.behance.net/acalderonl) 

This project was created as a first approach to a Machine Learning algorithm that allowed us to create new song lyrics based on a [55000+ song lyrics database](https://www.kaggle.com/mousehead/songlyrics) found on Kaggle and afterwards create different MIDI ringtones based on a [recurrent neural network that had been trained on thousands of MIDI files.](https://github.com/asfrattini/Artificial-Composer/blob/master/images/basic_rnn.mag) 

We also decided to make the most of this tool by choosing some of the lyrics that were outputted to create different wallpapers with celebrities that might, in general terms, have them in their songs. Even though when you took a closer look into them, they would probably be **meaningless and weird.**

<h3>Part 1: GPT-2 Text Generator</h3>

<h4>Training the model</h4>

In order to train a model with our song lyrics database we used a [google colab tutorial](https://colab.research.google.com/drive/1VLG8e7YSEwypxU-noRNhsv5dW4NfTGce) that allowed us to use our own database in order to change the output of the program.

<h5>The database</h5>

![input](https://github.com/asfrattini/Artificial-Composer/blob/master/images/Database.png)

<h5>The model</h5>

![input](https://github.com/asfrattini/Artificial-Composer/blob/master/images/Model.png)

<h4>Outputs</h4>

[Output 1 - Temperature 05, Length 200](https://github.com/asfrattini/Artificial-Composer/tree/master/outputs/01_temp05_length200.txt)

[Output 2 - Temperature 07, Length 200](https://github.com/asfrattini/Artificial-Composer/tree/master/outputs/02_temp07_length200.txt)

[Output 3 - Temperature 09, Length 200](https://github.com/asfrattini/Artificial-Composer/tree/master/outputs/03_temp09_length200.txt)

[Output 4 - Temperature 12, Length 200](https://github.com/asfrattini/Artificial-Composer/tree/master/outputs/04_temp12_length200.txt)

[Output 5 - Temperature 15, Length 200](https://github.com/asfrattini/Artificial-Composer/tree/master/outputs/05_temp15_length200.txt)

[Output 6 - Temperature 11, Length 200](https://github.com/asfrattini/Artificial-Composer/tree/master/outputs/06_temp11_length200.txt)

[Output 7 - Temperature 10, Length 300](https://github.com/asfrattini/Artificial-Composer/tree/master/outputs/07_temp10_length300.txt)

[Output 8 - Temperature 09, Length 300](https://github.com/asfrattini/Artificial-Composer/tree/master/outputs/08_temp09_length300.txt)


<h4>Celebrities mockups made in Photoshop</h4>

![input](https://github.com/asfrattini/Artificial-Composer/blob/master/images/Beyonce.png)

![input](https://github.com/asfrattini/Artificial-Composer/blob/master/images/Alicia.png)

![input](https://github.com/asfrattini/Artificial-Composer/blob/master/images/Billy.png)

![input](https://github.com/asfrattini/Artificial-Composer/blob/master/images/Coldplay.png)

![input](https://github.com/asfrattini/Artificial-Composer/blob/master/images/Kenny.png)

![input](https://github.com/asfrattini/Artificial-Composer/blob/master/images/Snoopp.png)


<h3>Part 2: Magenta MIDI-Generator + Pre-trained piano model</h3>

<h4>Training the model</h4>

For this part of the project we used a [tutorial](https://www.twilio.com/blog/generate-music-python-neural-networks-magenta-tensorflow) by [Sam Agnew](https://www.twilio.com/blog/author/sagnew) which implemented Magenta and Tensorflow in order to train a model with a midi files database and gave 10 midi files as an output (which we later decided to modify on Garage Band to create new music tracks.

![input](https://github.com/asfrattini/Artificial-Composer/blob/master/images/Midi-Files.png)

<h4>Outputs</h4>

[MIDI File Output 1](https://github.com/asfrattini/Artificial-Composer/blob/master/Midi-Outputs/2020-02-11_122213_01.mid)

[MIDI File Output 2](https://github.com/asfrattini/Artificial-Composer/blob/master/Midi-Outputs/2020-02-11_122213_02.mid)

[MIDI File Output 3](https://github.com/asfrattini/Artificial-Composer/blob/master/Midi-Outputs/2020-02-11_122213_03.mid)

[MIDI File Output 4](https://github.com/asfrattini/Artificial-Composer/blob/master/Midi-Outputs/2020-02-11_122213_04.mid)

[MIDI File Output 5](https://github.com/asfrattini/Artificial-Composer/blob/master/Midi-Outputs/2020-02-11_122213_05.mid)

[MIDI File Output 6](https://github.com/asfrattini/Artificial-Composer/blob/master/Midi-Outputs/2020-02-11_122213_06.mid)

[MIDI File Output 7](https://github.com/asfrattini/Artificial-Composer/blob/master/Midi-Outputs/2020-02-11_122213_07.mid)

[MIDI File Output 8](https://github.com/asfrattini/Artificial-Composer/blob/master/Midi-Outputs/2020-02-11_122213_08.mid)

[MIDI File Output 9](https://github.com/asfrattini/Artificial-Composer/blob/master/Midi-Outputs/2020-02-11_122213_09.mid)

[MIDI File Output 10](https://github.com/asfrattini/Artificial-Composer/blob/master/Midi-Outputs/2020-02-11_122213_10.mid)


<h4>Remix</h4>

[MIDI File Output 5 - REMIX](https://soundcloud.com/user-277066246/05_remix)

[MIDI File Output 7 - REMIX](https://soundcloud.com/user-277066246/07_remix)
