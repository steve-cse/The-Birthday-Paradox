
<p align="center">
<img  width="160" height="160" src="https://raw.githubusercontent.com/steve-cse/The-Birthday-Paradox/master/assets/partying-face_1f973.png" >
</p> 


<h1 align="center"><b>The Birthday Paradox</b></h1>
<p align="center">
  Micro Project for Foundations of Computer Science (221TCS002)
</p>



<p align="center">
In a random group of 23 people, there is about a 50 percent chance that two people have the same birthday.
</p> 

<p style='text-align: justify;'>
The probability of this occurring can be calculated using the following formula:
</p>

##### `P(23) = 1- (1 x (364 / 365) x (363 / 365) x … x (343 / 365))`

<p style='text-align: justify;'>
Here, P(n) is the probability that at least two people in a group of n people will have the same birthday, and 365 is the number of days in a year (assuming all birthdays are equally likely).
</p>

<p style='text-align: justify;'>
To understand this formula, it's helpful to think about the probability that no two people in a group of n have the same birthday. This probability can be calculated by taking the probability that the first person has a unique birthday (365/365) and multiplying it by the probability that the second person has a unique birthday (364/365), and so on, until you have multiplied the probability that the n-th person has a unique birthday (365-n+1/365). 
</p>

<p style='text-align: justify;'>
The probability that at least two people in the group have the same birthday is then just 1 minus the probability that no two people in the group have the same birthday.
</p>

## Run on Google Colaboratory
Run Code [▶️](https://colab.research.google.com/github/steve-cse/The-Birthday-Paradox/blob/master/Main.ipynb)