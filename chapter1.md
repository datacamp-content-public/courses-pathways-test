---
title: 'Chapter Title Here'
description: 'Chapter description goes here.'
free_preview: true
---

## Example coding exercise

```yaml
type: NormalExercise
key: e8c1edbe67
lang: python
xp: 100
skills: 2
```

This is an example exercise.

`@instructions`
First, see if you can get three plus three. Can you do it?

`@hint`


`@pre_exercise_code`
```{python}
# x= 3 + ??
```

`@sample_code`
```{python}
x = 
```

`@solution`
```{python}
x = 3+3
```

`@sct`
```{python}
Ex().check_object("x").has_equal_value()
```
