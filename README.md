# **The Challenge**

The objective is to find the path of lowest cost when moving across a grid. For this challenge, you are provided a grid of integers where each integer represents the amount of cost encountered at a given point on the grid. A path enters the grid from the left (at any point) and passes through the grid to the right, moving only one column per round. Movement is always to the same row or an adjacent row, meaning the path can proceed horizontally or diagonally. For the sake of this challenge, we assume the first and last row are also adjacent. Effectively, the grid “wraps”.

  
<img width="225" alt="screen shot 2017-09-14 at 2 45 35 am" src="https://user-images.githubusercontent.com/20385717/30415631-d7e88f3c-98f6-11e7-9020-317a5bf7110c.png">


The total cost of a path is the sum of the integers in each of the visited cells. The solution needs to handle grids of various sizes with a minimum of 1 row and 5 columns up to 10 rows and 100 columns. If in the next move, the total cost will exceed 50, that path is abandoned. The purpose of this challenge is to find the path of least cost (that is, the path with the lowest total cost of any possible path). The paths of least cost through two slightly different 5 x 6 grids are shown below. The grid values differ only in the bottom row. The path for the grid on the right takes advantage of the adjacency between the first and last rows.

<img width="784" alt="screen shot 2017-09-14 at 2 46 36 am" src="https://user-images.githubusercontent.com/20385717/30415663-07c46578-98f7-11e7-84dd-8c729483ac8b.png">


<img width="466" alt="screen shot 2017-09-14 at 2 13 30 am" src="https://user-images.githubusercontent.com/20385717/30414815-55ef9eec-98f3-11e7-9865-04614b443982.png">

# **Input**

The input consists of a sequence of row specifications. Each row is represented by a series of delimited integers on a single line. Note: integers are not restricted to being positive.


<img width="429" alt="screen shot 2017-09-14 at 2 13 52 am" src="https://user-images.githubusercontent.com/20385717/30414813-55e9c076-98f3-11e7-85ce-dda9ce0ed468.png">

# **Output**

Three lines should be output for each matrix specification. The first line is either “Yes” or “No” to indicate the path made it all the way through the grid. The second line is the total cost. The third line shows the path taken as a sequence of n delimited integers, each representing the rows traversed in turn. If there is more than one path of least cost, only one path need be shown in the solution.

<img width="494" alt="screen shot 2017-09-14 at 2 48 49 am" src="https://user-images.githubusercontent.com/20385717/30415712-49bb285e-98f7-11e7-9069-9b14ca52832c.png">
<img width="423" alt="screen shot 2017-09-14 at 2 49 23 am" src="https://user-images.githubusercontent.com/20385717/30415735-5dc9ec4a-98f7-11e7-868c-da9098610952.png">


<img width="479" alt="screen shot 2017-09-14 at 2 14 09 am" src="https://user-images.githubusercontent.com/20385717/30414812-55e6b1b0-98f3-11e7-9fd7-01f3c4f7cf3e.png">

Thank you. Let me know what you think @mralisher 
