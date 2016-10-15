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
