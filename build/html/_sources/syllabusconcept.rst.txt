.. CSE474 course webpage documentation master file, created by
   sphinx-quickstart on Fri Mar 17 21:28:07 2017.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Introduction to Machine Learning (CSE474)
====================================================================

`Computer Science and Engineering <http://www.cse.buffalo.edu/>`_, University at Buffalo 

Spring Semester 2020

.. toctree::
   :maxdepth: 2
   :caption: Contents:

.. raw:: html

    <style> .red {color:red} </style>
    <style> .blue {color:blue} </style>
    <style> .gr {color:green;font-weight:bold} </style>
    <style> .highlights {background-color:#ef9c7f;padding:1em} </style>

.. note:: 

   This is a sample syllabus for the Mozilla Responsible CS Challenge (https://foundation.mozilla.org/en/initiatives/responsible-cs/). This is not the actual syllabus for Spring 2020.

Instructors
------------

* `Varun Chandola <http://www.cse.buffalo.edu/~chandola>`_ (lead instructor; chandola[at]buffalo.edu)

Meeting times and locations
----------------------------
* Mondays, Wednesdays and Fridays, 9.00 AM - 9.50 AM, 121 Cooke Hall. 

* Chandola Office Hours: Wednesdays, 10.00 AM - 12.00 PM, 213 Capen Hall.

Prerequisites
---------------
CSE 250 and (EAS 305 or MTH 411 or STA 301 or MTH 309).

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
| 2          | Linear Regression                 | Linear Algebra,Gradient Descent Optimization, Matrix Calculus|
+------------+-----------------------------------+--------------------------------------------------------------+
| 2          | Logistic Regression               | Newton's Method                                              |
+------------+-----------------------------------+--------------------------------------------------------------+
| 2          | Perceptron Learning               |                                                              |
+------------+-----------------------------------+--------------------------------------------------------------+
| 3          | Support Vector Machines           | Constrained Optimization, Lagrangian Methods                 |
+------------+-----------------------------------+--------------------------------------------------------------+
| **Supervised Learning::Non-linear Models**                                                                    |
+------------+-----------------------------------+--------------------------------------------------------------+
| 4          | Non-linear Regression             |                                                              |
+------------+-----------------------------------+--------------------------------------------------------------+
| 5          | Regularization                    |                                                              |
+------------+-----------------------------------+--------------------------------------------------------------+
| 6-7        | Neural Networks                   |                                                              |
+------------+-----------------------------------+--------------------------------------------------------------+
| :red:`Spring Break`                                                                                           |
+------------+-----------------------------------+--------------------------------------------------------------+
| **Kernel Methods**                                                                                            |
+------------+-----------------------------------+--------------------------------------------------------------+
| 9          | Kernel Regression                 |                                                              |
+------------+-----------------------------------+--------------------------------------------------------------+
| 9          | Kernel Support Vector Machines    |                                                              |
+------------+-----------------------------------+--------------------------------------------------------------+
| **Statistical Learning**                                                                                      |
+------------+-----------------------------------+--------------------------------------------------------------+
| 10         | Generative Models                 | Laws of Probability, Statistical Distributions, Moments      |
+------------+-----------------------------------+--------------------------------------------------------------+
| 11         | Bayesian Learning Methods         | Bayes Rule                                                   |
+------------+-----------------------------------+--------------------------------------------------------------+
| 12         | Probabilistic Interpretation for  |                                                              |
|            | Linear/Logistic Regression        |                                                              |
+------------+-----------------------------------+--------------------------------------------------------------+
| 12         | Bayesian Linear Regression        |                                                              |
+------------+-----------------------------------+--------------------------------------------------------------+
| **Unsupervised Learning**                                                                                     |
+------------+-----------------------------------+--------------------------------------------------------------+
| 13         | Clustering (k-Means/Spectral)     | Linear Algebra (Eigenvalue Decomposition)                    |
+------------+-----------------------------------+--------------------------------------------------------------+
| 14         | Mixture Models (Expectation       |                                                              |
|            | Maximization)                     |                                                              |
+------------+-----------------------------------+--------------------------------------------------------------+
| 14         | Dimensionality Reduction Methods  |                                                              |
|            | (Principal Component Analysis)    |                                                              |
+------------+-----------------------------------+--------------------------------------------------------------+
| **Ethical Implications of ML Algorithms**                                                                     |
+------------+-----------------------------------+--------------------------------------------------------------+
| 15         | :gr:`Bias and Fairness in ML`     |                                                              |
+------------+-----------------------------------+--------------------------------------------------------------+


.. highlights:: 

   **Bias and Fairness in Machine Learning**

   With Machine Learning occupying every imaginable facet of our day to day lives, it is vital to design inclusive and fair algorithms. From delivering optimal search results on a search engine to making risk assessments about a person to commit a crime when granting bail (recidivism), biased algorithms can have serious consequences. Given the strong reliance of an ML algorithm on data and strong assumptions regarding the nature of the problem, it is easy for algorithms to become biased towards a certain type of outcome, or unfair towards a group of people. ML algorithms are intended to be biased by the data, in fact, a strong result that we will discuss early in the class is that you cannot learn without generalizing. But that fundamental principle conflicts with how we expect such algorithms to behave in the society. In this course, we will study these issues and possible strategies to avoid them in two parts:
   
   * `Programming Assignment 3`: You will apply a suite of machine learning algorithms, taught in the class, and analyze the tendency of each algorithm in learning biased models. The algorithms include logistic regression, Naive Bayes classifier, support vector machines, and neural networks. The data will be provided, along with multiple bias measures. Extra credit will be assigned for proposing new measures for bias. The deliverable for each project group will be a project report summarizing the group’s findings. Additionally, the report will include a section outlining the implications and the potential reasons for the bias.
   * `Follow-on discussion module in Week 15`: The instructor will summarize the outcomes from student project reports and discuss potential strategies for avoiding or mitigating the bias in the algorithms. At the end of the discussion, you will be able to answer questions such as:

     * Is a machine learning algorithm biased?
     * How to measure bias?
     * Between two machine learning algorithms, which one is more biased?
     * Even if offending features are removed from the training data, could proxy features induce an undesired bias?

Course Deliverables
-------------------

+---------------+--------------+-----------+
| Deliverable   | Release Date | Due Date  |
+===============+==============+===========+
| Gradiance 0   | Jan 28       |  *Feb 3*  |
+---------------+--------------+-----------+
| Gradiance 1   | Feb 4        |  Feb 10   |
+---------------+--------------+-----------+
| :gr:`PA 1`    | :gr:`Feb 6`  |:gr:`Mar 6`|
+---------------+--------------+-----------+
| Gradiance 2   | Feb 11       |  Feb 17   |
+---------------+--------------+-----------+
| Gradiance 3   | Feb 18       |  Feb 24   |
+---------------+--------------+-----------+
| :gr:`PA 2`    | :gr:`Mar 6`  |:gr:`Apr 3`|
+---------------+--------------+-----------+
| Gradiance 4   | Feb 25       |  Mar 3    |
+---------------+--------------+-----------+
| Gradiance 5   | Mar 4        |  Mar 10   |
+---------------+--------------+-----------+
| Gradiance 6   | Mar 11       |  *Mar 24* |
+---------------+--------------+-----------+
| Gradiance 7   | Mar 25       |  Mar 31   |
+---------------+--------------+-----------+
| :gr:`PA 3`    | :gr:`Apr 3`  |:gr:`May 1`|
+---------------+--------------+-----------+
| Gradiance 8   | Apr 1        |  Apr 7    |
+---------------+--------------+-----------+
| Gradiance 9   | Apr 8        |  Apr 14   |
+---------------+--------------+-----------+
| Gradiance 10  | Apr 15       |  Apr 21   |
+---------------+--------------+-----------+
| Gradiance 11  | Apr 22       |  Apr 28   |
+---------------+--------------+-----------+
| Gradiance 12  | Apr 29       |  May 5    |
+---------------+--------------+-----------+

.. note::
  * Gradiance quizzes

    * Will be released every Monday at 9.00 AM EST
    * Due next Sunday at 11.59 PM EST
    * Gradiance 0 will not be evaluated (warm up)
    * Gradiance 6 will be released on March 12 but will be due on March 25

  * All assignments are electronically due on Wednesdays by 08.59 AM EST through UBLearns.
  * Hard copies of assignment reports will be due in-class on Wednesdays before the end of the class.

Recitation Schedule
-------------------
+------+----------------------------------------------+
| Week | Topic                                        |
+======+==============================================+
| 1    | *No Recitation*                              |
+------+----------------------------------------------+
| 2    | Linear Algebra Review (Part 1)               |
+------+----------------------------------------------+
| 3    | Linear Algebra Review (Part 2)               |
+------+----------------------------------------------+
| 4    | Optimization Basics                          |
+------+----------------------------------------------+
| 5    | Python Basics (Part 1)                       |
+------+----------------------------------------------+
| 6    | Python Basics (Part 2)                       |
+------+----------------------------------------------+
| 7    | Midterm Review                               |
+------+----------------------------------------------+
| 8    | *Spring Break*                               |
+------+----------------------------------------------+
| 9    | Probability Theory Review                    |
+------+----------------------------------------------+
| 10   | Statistical Distributions Review             |
+------+----------------------------------------------+
| 11   | Using `scikit-learn`                         |
+------+----------------------------------------------+
| 12   | Decision Trees and Random Forests            |
+------+----------------------------------------------+
| 13   | Clustering Methods Review                    |
+------+----------------------------------------------+
| 14   | Dimensionality Reduction Methods             |
+------+----------------------------------------------+
| 15   | Finals Review                                |
+------+----------------------------------------------+

Course Texts
---------------
* Tom Mitchell, Machine Learning. McGraw-Hill, 1997.
* Kevin Murphy, Machine Learning: A Probabilistic Perspective, MIT Press, 2012.
* Chris Bishop, Pattern Recognition and Machine Learning, Springer, 2006.
* David Mackay, Information Theory, Inference, and Learning Algorithms, Cambridge Press, 2003.
* Trevor Hastie, Robert Tibshirani and Jerome Friedman, The Elements of Statistical Learning. Springer, 2009.

Grading
---------
* Class participation -- 5%
* Short weekly quizzes using Gradiance (12) -- 20%
* Programming Assignments (3) -- 30%
* Mid-term Exam (in-class, open book/notes) -- 20%
* Final Exam (in-class, open book/notes) -- 25%

* All components will be individually curved
* Final grade (*Tentative*)

== ===========
A  [92.5,100]
A- [87.5,92.5)
B+ [82.5,87.5)
B  [77.5,82.5)
B- [72.5,77.5)
C+ [67.5,72.5)
C  [62.5,67.5)
C- [57.5,62.5)
== ===========

Exams
---------------
* **Mid-term Exam** TBA
* **Final Exam** TBA

Expectations
-------------
* Students are expected to act in a professional manner. A student’s grade may be reduced due to unprofessional or disruptive behavior. Examples include coming to class late, texting (or otherwise using your cell phone) during class, your cell phone ringing during class and/or exams, etc.
* Homework assignments will be assigned for each module. Homework assignments are due at the beginning of class.
* Homework and programming assignments will be graded and returned to students.
* Late submission of assignments will receive a grade of zero.
* Students are encouraged to discuss assignments and share ideas, but each student must independently write and submit their own solution.
* Makeup exams will be given in the following circumstances only: 
  1. You contact the instructor prior to the exam
  2. You have a valid and documented reason to miss the exam

Accessibility Services and Special Needs
-----------------------------------------
If you have a disability and may require some type of instructional and/or examination accommodation, please inform me early in the semester so that we can coordinate the accommodations you may need. If you have not already done so, please contact the Office of Accessibility Services (formerly the Office of Disability Services) University at Buffalo, 25 Capen Hall, Buffalo, NY 14260-1632; email: stu-accessibility@ buffalo.edu Phone: 716-645-2608 (voice); 716-645-2616 (TTY); Fax: 716-645-3116; and on the web at http://www.buffalo.edu/accessibility/. All information and documentation is confidential. The University at Buffalo and the School of Engineering and Applied Sciences are committed to ensuring equal opportunity for persons with special needs to participate in and benefit from all of its programs, services and activities.

Academic Integrity
-------------------
This course will operate with a zero-tolerance policy regarding cheating and other forms of academic dishonesty. Any act of academic dishonesty will subject the student to penalty, including the high probability of failure of the course (i.e., assignment of a grade of “F”). It is expected that you will behave in an honorable and respectful way as you learn and share ideas. Therefore, recycled papers, work submitted to other courses, and major assistance in preparation of assignments without identifying and acknowledging such assistance are not acceptable. All work for this course must be original for this course. Additionally, you are not allowed to post course homeworks, exams, solutions, etc., on a public forum. Please be familiar with the University and the School policies regarding plagiarism. Read the Academic Integrity Policy and Procedure for more information: http://undergrad-catalog.buffalo.edu/policies/course/integrity.shtml. Visit the Senior Vice Provost for Academic Affairs web page for the latest information at http://vpue.buffalo.edu/policies/
