Download Link: https://assignmentchef.com/product/solved-csi2372-assignment-2
<br>
<h1></h1>







Question 1 of 2) <strong>Average Temperature of Months </strong>

<strong> </strong>

In this question you are required to use dynamic allocations for ALL the array created.

You are given 10 arrays containing the minimum, average and maximum temperatures for each month for each of the last 10 years in Ottawa. The data arrays are: year19, year18, year17, …, year10.

Write a program that prints the min, max and average data for a month by calculating the average temperature for each month in the given 10-year period:

To do this, you need to create a <strong>Stat structure</strong> composed of 3 floats: <strong>min</strong>, <strong>avg</strong> and <strong>max</strong>. This structure will be used to create a dynamic 10×12 Stat structure containing the temperatures for each month of the last 10 years called tableTemp.

Then you should create 2 functions : <strong>statMonth</strong> and <strong>printMonth</strong>.

?? <strong>statMonth</strong> (?? tableTemp, int month, int year):

<strong>statMonth</strong> takes as parameter the dynamic 10×12 array (tableTemp), the selected month and the number of years (in our case, 10 years). This function will be used to build a dynamic array of 12 elements of structure Stat which will contain the minimum, average and maximum results for each month:

//Dynamic array to hold the average, min and max statistics

Stat *ptr_stat = new Stat [12];







Then, this function returns a Stat structure containing the min, avg, max temperatures for the month entered in parameter.




<strong>printMonth(Stat, int month):</strong> prints the month, the maximum, minimum and average temperature for this month using the pass by reference for the Stat structure in parameter and the month chosen in parameter. The output should be as follows:

Enter the number of the month (between 1 and 12): 1




For the month of January

The minimum temperature was = -18

The average temperature was = -9.7

The maximum temperature was = -3




Finally, you must be able to enter a number between 1 and 12 to print the desired month: “Enter the number of the month (between 1 and 12):”.

Important:

<ul>

 <li>ALL arrays must be dynamic and <strong>must use the Stat structure</strong></li>

 <li>Create the functions <strong>statMonth</strong> and <strong>printMonth</strong></li>

</ul>




Question 2 of 2) <strong>High Scores (with struct) </strong>




Do Assignment 1-Q2 except use a struct named <strong>Player</strong> to store a player’s name and score. Then, use a dynamic array of the <strong>Player struct</strong> to store the players. Start with a dynamic array that stores no players. To add a player, create a new dynamic array that is one larger than the current size and copy the existing and the new player into it.  To remove a player, create a new dynamic array that is one smaller than the current size and copy all players into it except the player to remove.

Using global variables in this program are not allowed. Create a menu system that allows the user to select which option to invoke. The features must be in forms of four functions (adding a player, printing players, searching players, and removing a player) . The program manages a list of up to 10 players and their high scores. <sub> </sub>








