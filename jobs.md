## Jobs

### Shortcut
> k run name --restart=OnFailure

### Deadline
```
job.spec.activeDeadlineSeconds=30
```

### Iteration
```
job.spec.completions=5
```

### Parlallel
```
job.spec.parallelism=3
```


## Cron Jobs

### Shorcut
> k run name --restart=OnFailure --schedule="*/1 * * * *" 
