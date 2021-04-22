# Overview

This notebook is intended to provide a non-comprehensive introduction to SQL and relational database concepts.

Specifically, it was created to show a person with some technical background but no familiarity with SQL everything needed to construct queries to address use cases like:

    Given a table of event logs associated with users, I need to see events triggered by a specific set of users
    Given a table of event logs associated with users, I need the set of users assocaited with a specific event recorded during a given period of time

To address these use cases, the document will cover:

- Basic relational database structure
- `SELECT`ing columns from a table
- `ORDER`ing and `LIMIT`ing column data
- `GROUP`ing and aggregating column data
- Filtering results to show only columns `WHERE` the value matches one or more criteria, including being `IN` a given list
- `JOIN`ing tables together

# Viewing the notebook

Best viewed in [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/usernamenumber/SQLBasics/master?filepath=SQLBasics.ipynb) (be patient, it will take a while for this link to fully load!)
