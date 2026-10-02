# Reflection

Working on the BrewMetrics BI project with GitHub Copilot helped me understand how AI assistance can be combined with a structured Business Intelligence development workflow. Copilot was directly useful when creating DAX measures because it provided starting points for calculations such as month-over-month growth, running totals and RANKX-based city ranking. This reduced the time required to write the initial formulas and helped me understand different DAX functions.

However, I did not use Copilot's suggestions without checking them. I had to verify the table and column names, date context and filter behavior. In particular, the time-based measures needed to be checked against the Dim_Date table to make sure the results were meaningful. This showed me that Copilot can provide useful code, but the developer still needs to understand and validate the result.

Using GitHub commit history also changed the way I approached the project. Instead of building the entire Power BI report first and submitting one final file, I developed the solution in smaller stages. I committed the star schema first, followed by individual DAX measures and finally the dashboard. This made each change traceable and made it easier to identify what was changed at each stage.

Overall, the project helped me understand both BI development and a more professional version-controlled workflow.
