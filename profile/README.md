# org-not-included  
  
This org contains a mix of opensource projects, which are described in tables below.  
Some of them can be previewed at http://notincluded.org.  
  
---  
  
  
### Github Actions / PyPi Packages
  
| Repository Name                                                          | type             | Use Case                                 | Description                                                                                                                    |  
|--------------------------------------------------------------------------|------------------|------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------|
| [dbt_table_diff](https://github.com/org-not-included/dbt_table_diff)     | Github Action    | Run on Open Pull Requests                | Compares`dbt` tables in across `BigQuery schemas`, aka `dbt datasets`.                                                         |  
| [dbt_example](https://github.com/org-not-included/dbt_example)           | .github/workflow | Example of using `dbt_table_diff`        | Shows how `dbt_table_diff` can be used to comment on an [Open dbt PR](https://github.com/org-not-included/dbt_example/pull/2). |  
| [payment_parser](https://github.com/org-not-included/payment_parser)     | PyPi package     | File Transformation (fixed-width to csv) | Parses a fwf payment file into CSV files.                                                                                      |
| [py-github-helper](https://github.com/org-not-included/py-github-helper) | PyPi package     | Trigger on Github events                 | Enables interaction with Github Repositories and Pull Requests.                                                                |

  
---  
  
  
### Learning (Data Structures, Data Science, and Data Engineering)
   
| Repository Name                                                                            | Use Case                                 | Description                                                                                                                                      |  
|--------------------------------------------------------------------------------------------|------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------|
| [ds-tour](https://github.com/org-not-included/ds-tour)                                     | Learning Javascript                      | Implements data structures and has OOP examples, in Javascript.                                                                                  |  
| [simple_django_app](https://github.com/org-not-included/simple_django_app)                 | Learning Django (intro)                  | Creates a simple Django project, based of [this Youtube series](https://www.youtube.com/watch?v=IMG4r03G6g8).                                    |
| [simple_flask_app](https://github.com/org-not-included/simple_flask_app)                   | Learning Flask (intro)                   | Creates a simple homepage using Flask, based of [this Youtube series](https://www.youtube.com/playlist?list=PLFtQkpylAzMAKJNId7GBrCG5yIncZivVL). |
| [simple_analytics_pipeline](https://github.com/org-not-included/simple_analytics_pipeline) | Learning Data Engineering (ETL Intro)    | Uses Pandas to load CSV into SQLite database and queries database to create a simple chart.                                                      |
| [search_completion](https://github.com/org-not-included/search_completion)                 | Learning Data Engineering (ETL Medium)   | Extracts Bag of Words from text file, loads into SQLite database, and returns most common words based on a prefix.                               |
| [mlb-stats](https://github.com/org-not-included/mlb-stats)                                 | Learning Data Engineering (ETL Advanced) | Extracts game data from MLB Stats API, loads into SQLite database, and generates some charts.                                                    |  
  
  
---  
  
  
### Other
  
| Repository Name                                                                         | Use Case                  | Description                                                                                |  
|-----------------------------------------------------------------------------------------|---------------------------|--------------------------------------------------------------------------------------------|
| [py-strftime](https://github.com/org-not-included/py-strftime)                          | Python Datetime Formatter | A fork of @lachlan-eagling's [py-strftime](https://github.com/lachlan-eagling/py-strftime) |  
  
