# This is Leetcode's 30 Days Of Pandas Challenge

I provided the question link as well my answer link in both Pandas and MySQL.
'Note' column indicates what unique function of Pandas used has not appeared in other question.

| No | Question | Answer | Note |
| :--| :------- | :----- | :--- |
| 1 | [Big Countries](https://leetcode.com/problems/big-countries/description/?envType=study-plan-v2&envId=30-days-of-pandas&lang=pythondata) | [Solution](https://leetcode.com/problems/big-countries/solutions/4046912/pandas-and-mysql/) | df.query( ) |
| 2 | [Recyclable And Low Fat Products](https://leetcode.com/problems/recyclable-and-low-fat-products/description/?envType=study-plan-v2&envId=30-days-of-pandas&lang=pythondata) | [Solution](https://leetcode.com/problems/recyclable-and-low-fat-products/solutions/4046930/pandas-and-mysql/) |  |
| 3 | [Customers Who Never Order](https://leetcode.com/problems/customers-who-never-order/description/?envType=study-plan-v2&envId=30-days-of-pandas&lang=pythondata) | [Solution](https://leetcode.com/problems/customers-who-never-order/solutions/4046959/pandas-and-mysql/) | ~, df['column'].isin( ), df.merge( ), df['column'].isna( ) |
| 4 | [Article Views I](https://leetcode.com/problems/article-views-i/description/?envType=study-plan-v2&envId=30-days-of-pandas&lang=pythondata) | [Solution](https://leetcode.com/problems/article-views-i/solutions/4047430/pandas-and-mysql/) | df.drop_duplicates( ), df.sort_values( ) |
| 5 | [Invalid Tweets](https://leetcode.com/problems/invalid-tweets/description/?envType=study-plan-v2&envId=30-days-of-pandas&lang=pythondata) | [Solution](https://leetcode.com/problems/invalid-tweets/solutions/4052802/pandas-and-mysql/) | df['column_of_string'].str.len() |
| 6 | [Fix Names In A Table](https://leetcode.com/problems/fix-names-in-a-table/description/) | [Solution](https://leetcode.com/problems/fix-names-in-a-table/solutions/4065620/pandas-and-mysql/) |df.assign( ) |
| 7 | [Calculate Special Bonus](https://leetcode.com/problems/calculate-special-bonus/description/?envType=study-plan-v2&envId=30-days-of-pandas&lang=pythondata) | [SOLUTION](https://leetcode.com/problems/calculate-special-bonus/solutions/4069179/pandas-and-mysql-with-explanation/) | df.loc[ ] (Theory Explained) |
| 8 | [Find Users With Valid E Mails](https://leetcode.com/problems/find-users-with-valid-e-mails/description/) | [SOLUTION](https://leetcode.com/problems/find-users-with-valid-e-mails/solutions/4078071/pandas-and-mysql/) | df[column].str.match(regex), regex explained |
| 9 | [Patients With A Condition](https://leetcode.com/problems/patients-with-a-condition/description/) | [SOLUTION](https://leetcode.com/problems/patients-with-a-condition/solutions/4075890/pandas-and-mysql-with-explanation/) | df[column].str.contains(regex), regex explained |