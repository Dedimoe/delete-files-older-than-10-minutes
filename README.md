# delete-files-older-than-10-minutes

in linux : delete files older than 10 minutes

### delete :

```
find /tmp -maxdepth 1 -mmin +10 -type f -delete
```

or

```
find /tmp -maxdepth 1 -mmin +10 -type f -exec rm -fv {} \;
```


### find only :

```
find /tmp -maxdepth 1 -mmin +10 -type f
```


Just it.
