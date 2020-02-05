## Rollouts

### Status
```sh
$ k rollout status deploy/__name__
```

### Rollback
```sh
$ k rollout undo deploy/__name__
```

### Rollback to specific revision
```sh
$ k rollout undo deploy/__name__ --to-revision=:number
```

### History
```sh
$ k rollout history deploy/__name__ [ --revision:=number ]
```

### Pause
```sh
$ k rollout pause deploy/__name__
```

### Resume
```sh
$ k rollout resume deploy/__name__
```
