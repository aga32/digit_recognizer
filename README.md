# digit_recognizer proposal
What is the problem that you will be investigating? Why is it interesting?

  - Digit recognition is important because it has many practical applications. Additionally, handwriting can look very different from person to person which presents a challenge for a machine learning algorithm.

What reading will you examine to provide context and background?

  - Readings that we will examine are blog posts and articles on handwriting recognition algorithms.

What data will you use? If you are collecting new data, how will you do it?

  - We will be using the MNIST dataset.

What method or algorithm are you proposing? If there are existing implementations, will you use them and how? How do you plan to improve or modify such implementations? 
  
  - A classification method, more specifically, a template based method will be used.  There are various existing implementations of these methods using SVM and K-nearest neighbor that can be modified to lessen the current rate of error.  This existing implementation will be used as a baseline for these improvements which may include the use of preprocessors such as deskewing.   

How will you evaluate your results? Qualitatively, what kind of results do you expect (e.g. plots or figures)? Quantitatively, what kind of analysis will you use to evaluate and/or compare your results?

  - We will evaluate our results on a quantitative basis. By assigning the correct or “true” value to our data base of handwritten number and comparing the results our algorithm produces. Given this information we can produce graphs that demonstrate the evolution of the algorithm, showing the time needed to learn each number and the accuracy of it results. We expect that as the algorithm learns its speed and accuracy will increase in a manner that can be described mathematically.
