# Salaries of US Presidents and Vice Presidents [1789-2020]

US Presidents and Vice Presidents salaries dataset, and a Jupyter Lab EDA.


## Context

Researching for the White House Office staff salaries I found it interesting to accompany it with president and vice president salary data. 

The President's salary is set by Congress, and under Article II, Section 1, Clause 7 of the Constitution, any increase or reduction in Presidential salary can not take effect before the next Presidential term of office. The Vice President's salary is set by Congress as well, but the Constitution doesn't limit the timeframe. This dataset only includes the base salary, excluding the expense allowance, nontaxable travel account, and entertainment account expenses. The salary is paid out Per Annum.


## Content

This dataset contains 2 file:
* pvp_dataset.csv - Salary data for Presidents and Vice Presidents \[1789-2020].
* inflation_dataset.csv - Inflation info for EDA.

Row values include following attributes:
* year - Year of serving, as an integer \[1789-2020].
* name - Name formated as <last_name><comma><first_name>. Last and first names can consist of multiple names, separated by a space. If the person has a suffix (Jr., Sr., I, II, III, IV), it is added last, separated by a comma: <last_name><comma><first_name><comma><suffix>.
* party - Political party. Can be Unaffiliated, Federalist, Democratic-Republican, Whig, Democratic, and Republican.
* term - Four year term. Even though VPs don't have strict constitutional term limits, they often refer to their VP term of serving.
* salary - Salary in nominal US Dollars. Represented as an integer, without a dollar ($) character and trailing zeros. 
* position_title - President or Vice President.

For the next release I will add exact timeframes of the presidency and vice presidency.


## Acknowledgements

This dataset was collected from multiple sources, in various formats.
* [List of Presidents](https://en.wikipedia.org/wiki/List_of_presidents_of_the_United_States)
* [List of Vice Presidents](https://en.wikipedia.org/wiki/List_of_vice_presidents_of_the_United_States)
* Congressional Records from Google Books


## History:
* Version 1: Initial commit.
* Version 2: TBD