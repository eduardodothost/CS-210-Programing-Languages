# CS210-Programing-Languages

After completing project three in CS210, we developed an inventory tracker I had named 'Progress Reporter' that would allow a user to parse through pairs of data values and discover the frequency of each key word found in the data set.

I had fashioned a bar chart function for data visualization using Windows console API. My function 'level' produces a bar chart with a different color depending on the threshold for a color change based on the frequency of the keyword. It will display well for the data set given; but needs to be able to account for data sets that would draw bars that are misproportional to the data set, sending them off screen. 

I now have a chance to update the program in an upcoming assignment that has us produce a project for our portfolio on 'github' --  IE this project.

I start off with a plan to create a 'barBuilder' function, that will replace level', that constructs a left and right hand of the bar corresponding to a key modeled and scalled by the data set's standard deviation. We will take the standard deviation of the frequencies using code from past projects; being able to divide and wireframe the barchart into six or eight distinct bands, where color change can be discriminated at the developers discretion. Currently overweight and underweight items will be designated green and red for items that are oversold and undersold.

Barbuilder will contain the private functions leftHand and rightHand; that will draw out our bars given the the frequency displacement from the mean frequency calculated from the working data set.

Adding a scaled visualization is key to making the function work effectively as a console application and meet the assignment specifications that want the student to strive to implement and be able to refactor orthogonal code; but I foresee opportunities to move the project outside of the console and into a GUI. I also realize that one can make use of the various visualization and storage libraries to be able to scale the application to be more modern and extensible and interoperable. 

The penultimate module of CS210 leaves the student at 'this stage' where one feels empowered to explore the realm of possibilities while treading lightly in persuit of upholding industry standards and a client(s)' specifications within ethical and legal limits at all facets of the software development lifecycle. A truely remarkable course from Southern New Hampshire University.

I'm currently reviewing means of scaling or normalizing our bars, much like in this EG https://stackoverflow.com/questions/14098895/math-i-need-to-normalize-some-bar-graphs. The next module will offer options to use a different programing languages in conjunction with C++. I feel confident that I'd be able add functionality via using python libraries; but have seen some promissing c++ libraries that will allow me accelerate the development of 'Progress Reporter'.

Qt seems like the most accessable solution to me at this time. A barchart like the following is very impressive -- https://doc.qt.io/qt-6/qtdatavis3d-qmlbars-example.html.
