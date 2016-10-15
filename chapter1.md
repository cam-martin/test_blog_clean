---
title       : Insert the chapter title here
description : Insert the chapter description here
attachments :
  slides_link : https://s3.amazonaws.com/assets.datacamp.com/course/teach/slides_example.pdf

--- type:MultipleChoiceExercise lang:python xp:50 skills:1 key:a2b3acee9e
## A really bad movie

Have a look at the plot that showed up in the viewer to the right. Which type of movies have the worst rating assigned to them?

*** =instructions
- Long movies, clearly
- Short movies, clearly
- Long movies, but the correlation seems weak
- Short movies, but the correlation seems weak

*** =hint
Have a look at the plot. Do you see a trend in the dots?

*** =pre_exercise_code
```{python}
# The pre exercise code runs code to initialize the user's workspace.
# You can use it to load packages, initialize datasets and draw a plot in the viewer

import pandas as pd
import matplotlib.pyplot as plt

movies = pd.read_csv("http://s3.amazonaws.com/assets.datacamp.com/course_1983/datasets/311_Service_Requests.csv")


```

*** =sct
```{python}
# SCT written with pythonwhat: https://github.com/datacamp/pythonwhat/wiki

msg_bad = "That is not correct!"
msg_success = "Exactly! The correlation is very weak though."
test_mc(4, [msg_bad, msg_bad, msg_bad, msg_success])
```

--- type:NormalExercise lang:python xp:100 skills:1 key:4ccb40bb74
## Plot the movies yourself

Test


*** =instructions
Test

*** =pre_exercise_code
```{python}
import pandas as pd
311_service_URL = "http://s3.amazonaws.com/assets.datacamp.com/course/introduction_to_r/movies.csv"

import numpy as np
```

*** =sample_code
```{python}
requests = pd.read_csv(311_service_URL)

```

*** =solution
```{python}
# Get integer values for genres
requests = pd.read_csv(311_service_URL)

```

*** =sct
```{python}
# SCT written with pythonwhat: https://github.com/datacamp/pythonwhat/wiki


success_msg("Great work!")
```
