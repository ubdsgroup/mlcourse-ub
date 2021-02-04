.. CSE474574 course webpage documentation master file, created by
   sphinx-quickstart on Fri Mar 17 21:28:07 2017.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Syllabus
====================================================================

`Computer Science and Engineering <http://www.cse.buffalo.edu/>`_, University at Buffalo 

**Spring Semester 2021**

.. raw:: html

    <style> .red {color:red} </style>
    <style> .blue {color:blue} </style>
    <style> .gr {color:green;font-weight:bold} </style>
    <style> .highlights {background-color:#ef9c7f;padding:1em} </style>

Instructors
------------

* `Varun Chandola <http://www.cse.buffalo.edu/~chandola>`_ (lead instructor; chandola[at]buffalo.edu)

* Deen Dayal Mohan (TA; dmohan[at]buffalo.edu)
* Seokmin Choi (TA; seokminc[at]buffalo.edu)
* Jie Zhang (TA; zhang326[at]buffalo.edu)
* Enshu Wang (TA; enshuwan[at]buffalo.edu)

.. note::
   Students are strongly encouraged to use the Piazza's private messaging option to contact the intructors to ensure that the messages are dealt with promptly. 

Class Website
-------------
https://cse.buffalo.edu/~chandola/machinelearning.html

Meeting times and locations
----------------------------
Every Monday, Wednesday and Friday - 1.50 to 2.40 PM, virtually on `Zoom <https://buffalo.zoom.us/j/95608261824>`_ 

.. note::
   All lecture videos will be made available after the class. The links will be posted on Piazza and also available `here <lecturevideos.html>`_.
   Please ensure that your video is turned off and the microphone is on mute. Use the zoom reactions and chat to interact with the instructor.

Office Hours
------------
.. csv-table:: 
   :header: "Who?","When?","Where?"
   :widths: 20, 40, 30

   "Chandola", "Fridays 3.00 PM - 5.00 PM",`Virtually on Zoom <https://buffalo.zoom.us/j/94867240117?pwd=NGxCNFgzcUVnYjVoalpJQkczNTNjZz09>`_
   "Deen","Mondays 6.30 PM - 7.30 PM",`Virtually on Zoom <https://buffalo.zoom.us/j/94867240117?pwd=NGxCNFgzcUVnYjVoalpJQkczNTNjZz09>`_ 
   "Seokmin","Mondays 9.00 AM - 10.00 AM", `Virtually on Zoom <https://buffalo.zoom.us/j/93717120120?pwd=S3g3KytBYkljMWdhQlNlL0k2KzNDQT09>`_
   "Jie","Thursdays 2.30 PM - 3.30 PM",`Virtually on Zoom <https://buffalo.zoom.us/j/93717120120?pwd=S3g3KytBYkljMWdhQlNlL0k2KzNDQT09>`_ 
   "Enshu","Tuesdays 1:00 PM - 2:00 PM",`Virtually on Zoom <https://buffalo.zoom.us/j/97158552112?pwd=WkszZHE3QWZPaEdQM1ZmbjRQVmlHdz09>`_ 

Prerequisites
---------------
CSE 250 and (EAS 305 or MTH 411 or STA 301 or MTH 309).

.. note::
   This course requires a strong background in linear algebra, advanced calculus and statistics. Please refer to the `FAQs <faqs.html>`_ for more.

Topic Schedule
---------------
.. role:: red
.. role:: gr
.. tabularcolumns:: |l|l|p{2cm}|

+------------+-----------------------------------+--------------------------------------------------------------+
| Week       | Topic                             | Pre-requisites                                               |
+============+===================================+==============================================================+
| 1          | Introduction and Basics           |                                                              | 
+------------+-----------------------------------+--------------------------------------------------------------+
| **Supervised Learning::Linear Models**                                                                        |
+------------+-----------------------------------+--------------------------------------------------------------+
| 1          | Linear Regression                 | Linear Algebra,Gradient Descent Optimization, Matrix Calculus|
+------------+-----------------------------------+--------------------------------------------------------------+
| 2          | Logistic Regression/Perceptrons   | Newton's Method                                              |
+------------+-----------------------------------+--------------------------------------------------------------+
| 2-3        | Support Vector Machines           | Constrained Optimization, Lagrangian Methods                 |
+------------+-----------------------------------+--------------------------------------------------------------+
| **Supervised Learning::Non-linear Models**                                                                    |
+------------+-----------------------------------+--------------------------------------------------------------+
| 4          | Non-linear Regression             |                                                              |
+------------+-----------------------------------+--------------------------------------------------------------+
| 4          | Regularization                    |                                                              |
+------------+-----------------------------------+--------------------------------------------------------------+
| 5-6        | Neural Networks                   |                                                              |
+------------+-----------------------------------+--------------------------------------------------------------+
| **Kernel Methods**                                                                                            |
+------------+-----------------------------------+--------------------------------------------------------------+
| 7          | Kernel Regression                 |                                                              |
+------------+-----------------------------------+--------------------------------------------------------------+
| 7          | Kernel Support Vector Machines    |                                                              |
+------------+-----------------------------------+--------------------------------------------------------------+
| **Statistical Learning** (Continued)                                                                          |
+------------+-----------------------------------+--------------------------------------------------------------+
| 8          | Generative Models                 | Laws of Probability, Statistical Distributions, Moments      |
+------------+-----------------------------------+--------------------------------------------------------------+
| 9          | Bayesian Learning Methods         | Bayes Rule                                                   |
+------------+-----------------------------------+--------------------------------------------------------------+
| 10         | Bayesian Classification           |                                                              |
|            |                                   |                                                              |
+------------+-----------------------------------+--------------------------------------------------------------+
| 11         | Bayesian Linear Regression        |                                                              |
+------------+-----------------------------------+--------------------------------------------------------------+
| **Fairness and Transparency Issues**                                                                          |
+------------+-----------------------------------+--------------------------------------------------------------+
| 12         | Fairness in Machine Learning      |                                                              |
|            | (PA3 Review)                      |                                                              |
+------------+-----------------------------------+--------------------------------------------------------------+
| 12         | Interpretable Models              |                                                              |
|            | (Decision Trees)                  |                                                              |
+------------+-----------------------------------+--------------------------------------------------------------+
| **Unsupervised Learning**                                                                                     |
+------------+-----------------------------------+--------------------------------------------------------------+
| 13         | Clustering (k-Means/Spectral)     | Linear Algebra (Eigenvalue Decomposition)                    |
+------------+-----------------------------------+--------------------------------------------------------------+
| 14         | Dimensionality Reduction Methods  |                                                              |
|            | (Principal Component Analysis)    |                                                              |
+------------+-----------------------------------+--------------------------------------------------------------+
| **Reinforcement Learning**                                                                                    |
+------------+-----------------------------------+--------------------------------------------------------------+
| 15         | Reinforcement Learning            |                                                              |
+------------+-----------------------------------+--------------------------------------------------------------+
| **Wrap-up**                                                                                                   |
+------------+-----------------------------------+--------------------------------------------------------------+
| 16         | Machine Learning Best Practices   |                                                              |
+------------+-----------------------------------+--------------------------------------------------------------+

Course Deliverables
-------------------

+---------------+--------------+------------+
| Deliverable   | Release Date | Due Date   |
+===============+==============+============+
| Gradiance 0   | Feb 1        |  *Feb 9*   |
+---------------+--------------+------------+
| Gradiance 1   | Feb 10       |  Feb 16    |
+---------------+--------------+------------+
| :gr:`PA 1`    | :gr:`Feb 8`  | :gr:`Mar 5`|
+---------------+--------------+------------+
| Gradiance 2   | Feb 17       |  Feb 23    |
+---------------+--------------+------------+
| Gradiance 3   | Feb 24       |  Mar 2     |
+---------------+--------------+------------+
| :gr:`PA 2`    | :gr:`Mar 8`  | :gr:`Apr 9`|
+---------------+--------------+------------+
| Gradiance 4   | Mar 3        |  Mar 9     |
+---------------+--------------+------------+
| Gradiance 5   | Mar 10       |  Mar 16    |
+---------------+--------------+------------+
| Gradiance 6   | Mar 17       |  Mar 23    |
+---------------+--------------+------------+
| Gradiance 7   | Mar 24       |  Mar 31    |
+---------------+--------------+------------+
| :gr:`PA 3`    | :gr:`Apr 12` | :gr:`May 7`|
+---------------+--------------+------------+
| Gradiance 8   | Apr 1        |  Apr 7     |
+---------------+--------------+------------+
| Gradiance 9   | Apr 8        |  Apr 14    |
+---------------+--------------+------------+
| Gradiance 10  | Apr 15       |  Apr 21    |
+---------------+--------------+------------+
| Gradiance 11  | Apr 22       |  Apr 28    |
+---------------+--------------+------------+
| Gradiance 12  | Apr 29       |  May 5     |
+---------------+--------------+------------+

.. note::
  * Gradiance quizzes

    * Will be released every Wednesday at 9.00 AM EST
    * Due next Tuesday at 11.59 PM EST
    * Gradiance 0 will not be evaluated (warm up)

  * All assignments are electronically due on Fridays by 11.59 PM EST through UBLearns.

Assignments (Tentative Schedule)
---------------------------------
  * Programming Assignment 1 - This assignment will focus on building linear models for supervised learning. This will include implementing a linear regression model for regression, and three classification models, viz., logistic regression, perceptron, and support vector machine (SVM).
  * Programming Assignment 2 - In this assignment, your task will be to explore non-linear machine learning models to learn from text and image data.
  * Programming Assignment 3 - This programming assignment has two parts. In the first part, you will implement a Naive Bayes Classifier and test it on a publicly available data set. In the second part, you will manipulate the data characteristics to understand how classifiers get impacted by the underlying bias in the training data. Focus will be on developing a COMPAS style risk assessment system. 

Course Texts
---------------
* Kevin Murphy, Machine Learning: A Probabilistic Perspective, MIT Press, 2012.
* Tom Mitchell, Machine Learning. McGraw-Hill, 1997.
* Chris Bishop, Pattern Recognition and Machine Learning, Springer, 2006.
* David Mackay, Information Theory, Inference, and Learning Algorithms, Cambridge Press, 2003.
* Trevor Hastie, Robert Tibshirani and Jerome Friedman, The Elements of Statistical Learning. Springer, 2009.
* Richard S. Sutton and Andrew G. Bart, Reinforcement Learning: An Introduction. MIT Press, 2015.

Grading
---------
* Short weekly quizzes using Gradiance (12) -- 20%
* Programming Assignments (3) -- 45%
* Mid-term Exam (virtual-UBLearns, open book/notes) -- 15%
* Final Exam (virtual-UBLearns, open book/notes) -- 20%
* Final grade (*Tentative*)

.. hlist::
    :columns: 2

    - A  [92.5,100]
    - A- [87.5,92.5)
    - B+ [82.5,87.5)
    - B  [77.5,82.5)
    - B- [72.5,77.5)
    - C+ [67.5,72.5)
    - C  [62.5,67.5)
    - C- [57.5,62.5)

Exams
---------------
* **Mid-term Exam** March 19, 1.40 PM - 2.50 PM, virtually using UBLearns 
* **Final Exam** May 14, 11.45 AM - 2.45 PM, virtually using UBLearns 

.. note::
   The mid-term will held during the regular Friday lecture.

Expectations
-------------
.. * Students are expected to act in a professional manner. A student’s grade may be reduced due to unprofessional or disruptive behavior. Examples include coming to class late, texting (or otherwise using your cell phone) during class, your cell phone ringing during class and/or exams, etc.

* Students are expected to act in a professional manner during the virtual classes and office hours.
* Programming assignments will be graded and returned to students.
* :red:`Late submission of assignments will receive a grade of zero.`
* :red:`No late submission of Gradiance quizzes are allowed. The quizzes will automatically become unavailable immediately after the due date and no accomodations will be made for missed quizzes.`
* Students are encouraged to discuss assignments and share ideas, but each student must independently write and submit their own solution.
* Makeup exams will be given in the following circumstances only: 

  1. You contact the instructor prior to the exam
  2. You have a valid and documented reason to miss the exam

Accessibility Services and Special Needs
-----------------------------------------
If you have a disability and may require some type of instructional and/or examination accommodation, please inform me early in the semester so that we can coordinate the accommodations you may need. If you have not already done so, please contact the Office of Accessibility Services (formerly the Office of Disability Services) University at Buffalo, 25 Capen Hall, Buffalo, NY 14260-1632; email: stu-accessibility@buffalo.edu Phone: 716-645-2608 (voice); 716-645-2616 (TTY); Fax: 716-645-3116; and on the web at http://www.buffalo.edu/accessibility/. All information and documentation is confidential. The University at Buffalo and the School of Engineering and Applied Sciences are committed to ensuring equal opportunity for persons with special needs to participate in and benefit from all of its programs, services and activities.

Academic Integrity
-------------------
This course will operate with a zero-tolerance policy regarding cheating and other forms of academic dishonesty. Any act of academic dishonesty will subject the student to penalty, including the high probability of failure of the course (i.e., assignment of a grade of “F”). It is expected that you will behave in an honorable and respectful way as you learn and share ideas. Therefore, recycled papers, work submitted to other courses, and major assistance in preparation of assignments without identifying and acknowledging such assistance are not acceptable. All work for this course must be original for this course. Additionally, you are not allowed to post course homeworks, exams, solutions, etc., on a public forum. Please be familiar with the University and the School policies regarding plagiarism. Read the Academic Integrity Policy and Procedure for more information: http://undergrad-catalog.buffalo.edu/policies/course/integrity.shtml. Visit the Senior Vice Provost for Academic Affairs web page for the latest information at http://vpue.buffalo.edu/policies/

.. highlights:: 

   **Machine Learning Honor Code**
  
   Against the ML honor code to:

   1. Collaborate on Gradiance quizzes
   2. Collaborate or cheat during exams
   3. Submit someone else’s work, including from the internet, as one’s own for any submission
   4. Misuse Piazza forum

   You are allowed to:

   1. Have discussions about homeworks. Every student should submit own homework with names of students in the discussion group explicitly mentioned.

.. 2. Collaborate in groups of 3 for programming assignments. One submission is required for each group.

.. warning:: 
   * Violation of ML honor code and departmental policy will result in an automatic F for the concerned submission
   * Two violations ⇒ fail grade in the course
