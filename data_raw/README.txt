This archive contains the dataset used in the following papers:

* Eye Movement Analysis for Activity Recognition Using Electrooculography
  Andreas Bulling, Jamie A. Ward, Hans Gellersen and Gerhard Tröster
  IEEE Transactions on Pattern Analysis and Machine Intelligence, 33(4):741-753, 2011.
  http://dx.doi.org/10.1109/TPAMI.2010.86

* Eye Movement Analysis for Activity Recognition
  Andreas Bulling, Jamie A. Ward, Hans Gellersen and Gerhard Tröster
  Proc. of the 11th International Conference on Ubiquitous Computing (UbiComp 2009)
  Orlando, United States, pages 41-50, ACM Press, September 2009.
  http://dx.doi.org/10.1145/1620545.1620552

=======================================================================================

This dataset is licensed under a Creative Commons Attribution-Noncommercial 3.0 Unported License.
See http://creativecommons.org/licenses/by-nc/3.0/ for details.
The full text of the license can be found at
http://creativecommons.org/licenses/by-nc/3.0/legalcode

BY DOWNLOADING AND USING THIS DATASET YOU AGREE TO THE TERMS OF THE ABOVE LICENSE
AND TO CITE THE ABOVE PAPERS IN YOUR OWN WORK.

You are free:
 * to Share - to copy, distribute and transmit the work
 * to Remix - to adapt the work

Under the following conditions:
* Attribution - You must attribute the work in the manner specified by the author
  or licensor (but not in any way that suggests that they endorse you or your use of the work).
* Noncommercial - You may not use this work for commercial purposes.

=======================================================================================

In case of questions please feel free to contact me:
Andreas Bulling <andreas.bulling@acm.org>
http://www.andreas-bulling.eu/

Cambridge, United Kingdom, 11 February 2012

=======================================================================================

Technical Description
---------------------

recording device: Twente Medical Systems International (TMSI) Mobi
raw signals, 128Hz sampling frequency

MATLAB data format:
    column 1: timestamp [sec]
    column 2: timestamp [usec]
    column 3: horizontal EOG [Mobi amplitude units]
    column 4: vertical EOG [Mobi amplitude units]
    column 5: ground truth annotation

Ground truth annotation format:
    null: 1
    read: 2
    browse: 3
    write: 4
    video: 5
    copy: 6
    disspeak: 7 // distraction speak
    disphone: 8 // distraction phone

Participants (number gender comment)
--------------------------------

(1) male
(2) male
(3) male
(4) male
(5) male
(6) female
(7) female
(8) male

Experimental Runs (number type comment)
---------------------------------------

(0) Run 1, performing a random sequence of office activities
(1) Run 2, performing a random sequence of office activities

The number in brackets corresponds to the number appended to each filename.