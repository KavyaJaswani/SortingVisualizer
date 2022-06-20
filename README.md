# SortingVisualizer




## INTRODUCTION TO PROJECT

Sorting algorithms can be difficult to understand and it's easy to get confused. I believe visualizing sorting algorithms can be a great way to better understand their functioning while having fun!
Sorting is a very classic problem of reordering items (that can be compared, e.g., integers, floating-point numbers, strings, etc) of an array (or a list) in a certain order (increasing, non-decreasing (increasing or flat), decreasing, non-increasing (decreasing or flat), lexicographical, etc). There are many different sorting algorithms, each has its own advantages and limitations.
In data structures and algorithms ,I have different types of sorting algorithms like merge sort,quick sort,bubble sort, selection sort etc. I have tried to implement the visualization of some of these sorting algorithms using OpenGL which helps in easier understanding of the implementation of the algorithms


## COMPUTER GRAPHICS CONCEPTS USED

Polygon Drawing: -
#### • Lines: - 
They are drawn using the library by mentioning starting and ending points (x, y coordinates) in the space.
#### • Through Points - 
Polygon is constructed by looping over different points in the space. Using 2D and 3D transformations: - To rotate the stones, increase the decrease the size of stones and create various shapes the following 2D and 3D transformations are used in this project. 
#### • Translation - 
Movement of object on screen/in space without deformation. We translate a point by adding to x, y and z coordinates. Movement of objects on screen without deformation.
#### • Rotation -
 Process of changing the angle of object about any pivot point along any axis/plane. 
#### • Scaling-
 The scaling operation on an object can be carried out for an object by multiplying each of the points (x,y,z) by the scaling factors sx, sy and sz.
#### • Polygon-Filling -
 Filling a Polygon is the process of coloring every pixel that comes inside the polygon region. By using glcolor3f, we could fill colors inside any polygon by filling the RGB values to make the project visually appealing.


## USER DEFINED FUNCTIONS
#### ●	void displayText(std::string textToDraw, int x, int y):
 To display the information such as the algorithm used, time taken,number of comparisons etc.
#### ●	void displayTitle(std::string textToDraw, int x, int y):
To display the heading of the project.
#### ●	void displayInfo(): 
It displays the title and the text and sets color,size,etc for the same.
#### ●	void displayTotalTime(int diff, std::string algorithm):
 To display the time taken by each algorithm for easy comparison.
#### ●	void draw(int x, int y):
 To draw and set different colors (for showing the transition)for the bars that will be sorted by the algorithm.
#### ●	void generate():
 This will create an unsorted set of bars that will then be sorted by the algorithm selected by the user.
#### ●	void menuFunc(int id):
 This function takes care of the different choices that the user will make like the speed settings, 
#### ●	void createMenu():
 This creates the menu which will be displayed in the final result.
#### ●	Various sorting algorithm methods: 
The backend to sorting the values.
