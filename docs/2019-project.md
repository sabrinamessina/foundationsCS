You have to work on  the [Kiva](https://drive.google.com/file/d/1-tJtnIbo1Rt-F1XfoWGVkmBXiI-ciuRx/view?usp=sharing)
dataset.
Some information on the datasets are on the [Kaggle](https://www.kaggle.com/gaborfodor/additional-kiva-snapshot) web page.

#### All groups and individual must do the following:

1.  Normalize the `loan_lenders` table. In the normalized table, each row must have one `loan_id` and one `lender`.
1.  For each loan, add a column `duration` corresponding to the number of days between the disburse time and the planned
    expiration time.
1.  Find the borrowers that have funded at least twice.
1.  For each country, compute the how many loans have involved that country as borrowers.
1.  For each country, compute the overall amount of money borrowed.
1.  Like the previous point, but expressed as a percentage of the overall amount lent.
1.  Like the three previous points, but split for each year.
1.  For each lender, compute the overall amount of money lent.
1.  For each country, compute the difference between to overall amount of money lent and the overall amount of money
    borrowed.
1.  Which country has the highest ratio between the difference computed at the previous point and the population?
1.  Which country has the highest ratio between the difference computed at the previous point and the population that is
    not below the poverty line?
1.  For each year, compute the total amount of loans. Each loan that has planned expiration time and disburse time in
    different years must have its amount distributed proportionally to the number of days in each year.

#### The following part of the exercise must be done only by groups with two or three people

1.  For each value of `repayment_interval`, add a new column to the `lenders` dataframe that contains the total amount
    of money corresponding to loans in such state
1.  What is the occupation with the highest average amount of money lent (the average must be computed over all lenders
    with a given occupation)?
1.  Cluster the loans according to the year-month of disburse time.
1.  For each country, compute its overall GDP, by multiplying the per capita GDP with its population.

#### The following part of the exercise must be done only by groups with three people

1.  Find the country with highest rate of irregular repayment interval.
1.  Find the country with highest fraction of loaned amount with irregular repayment interval.
1.  For each lender, estimate the total amount of money lent. For each loan that has more than one lender, you must
    assume that all lenders contributed the same amount.

### Notes

1.  It is mandatory to use [GitHub](https://www.github.com) for developing the project.
1.  The project *must* be a jupyter notebook. 
1.  There is *no restriction* on the libraries that can be used, nor on the Python version.
1.  Post any question on the [Discussions](https://elearning.unimib.it/mod/forum/view.php?id=319886) forum