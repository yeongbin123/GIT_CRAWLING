# GIT_CRAWLING

This program that use <strong>"GITHUB API"</strong> support to searching "GITHUB" repositories information. 

Because it is based on the Python language, you must install a Python library to use this program. 

For more information, see:

## Introduction

It is a Python program for mining git storage information, including stars, forks, followers, and so on and so forth.

### To run the program

First, a <strong>"requests"</strong> library should be installed.

1. Window command
> pip install requests
2. Mac command
> [Your python3 version] -m pip install requests

Next, run the program.

<img src="images/starting.png" alt="Image Error" width="200">
Enter the your github ID and Token. Token can get from follow path.<br /> 
<strong>Path : settings -> Developer settings -> Personal access tokens</strong>

<img src="images/condition.png" alt="Image Error" width="200">
Then, Set a condition that you want to search. You must place space unconditionally between characters.<br />
<strong>Example input list</strong> <br />
<ul>
  <li>1<space>java</li>
  <li>2<space><2009-02-13</li> 
  <li>6<space><60</li> 
  <li>3<space>2010-10-06 2017-04-05</li> 
</ul>


