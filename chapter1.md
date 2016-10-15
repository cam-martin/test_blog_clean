---
title       : Insert the chapter title here
description : Insert the chapter description here
attachments :
  slides_link : https://s3.amazonaws.com/assets.datacamp.com/course/teach/slides_example.pdf


--- type:NormalExercise lang:python xp:100 skills:1 key:4ccb40bb74
## Plot the movies yourself

Do you remember the plot of the last exercise? Let's make an even cooler plot!

A dataset of movies, `movies`, is available in the workspace.

*** =instructions
- Test

*** =hint
- Test

*** =pre_exercise_code
```{python}
import pandas as pd
movies = pd.read_csv("http://s3.amazonaws.com/assets.datacamp.com/course/introduction_to_r/movies.csv")

import numpy as np
```

*** =sample_code
```{python}
# Get integer values for genres
movies = pd.read_csv("http://s3.amazonaws.com/assets.datacamp.com/production/course_1983/datasets/311_Service_Requests.csv")


```

*** =solution
```{python}
# Get integer values for genres
movies = pd.read_csv("http://s3.amazonaws.com/assets.datacamp.com/production/course_1983/datasets/311_Service_Requests.csv")

```

*** =sct
```{python}
# SCT written with pythonwhat: https://github.com/datacamp/pythonwhat/wiki


success_msg("Great work!")
```
--- type:NormalExercise lang:python xp:100 skills:1 key:f430b12af7
## Plot the movies yourself

Do you remember the plot of the last exercise? Let's make an even cooler plot!

A dataset of movies, `movies`, is available in the workspace.

*** =instructions
- Test

*** =hint
- Test

*** =pre_exercise_code
```{python}

```

*** =sample_code
```{python}
# Get integer values for genres
import pandas as pd
requests = pd.read_csv('http://s3.amazonaws.com/assets.datacamp.com/production/course_1983/datasets/311_Service_Requests.csv')
requests['Incident Zip'].unique()
na_value = ['NO CLUE', 'N/A', '0', '00000']
requests = pd.read_csv('http://s3.amazonaws.com/assets.datacamp.com/production/course_1983/datasets/311_Service_Requests.csv', na_values=na_value, dtype={'Incident Zip': str})

long_zip_codes = requests['Incident Zip'].str.len() > 5
requests['Incident Zip'][long_zip_codes].unique()
```

*** =solution
```{python}
# Get integer values for genres
movies = pd.read_csv("http://s3.amazonaws.com/assets.datacamp.com/production/course_1983/datasets/311_Service_Requests.csv")

```

*** =sct
```{python}
# SCT written with pythonwhat: https://github.com/datacamp/pythonwhat/wiki


success_msg("Great work!")
```
