

## Dev. notes

```
docker run --rm -it -v %CD%:/data remact bash -c "cp /data/example.remind /tmp && remind -t -g /tmp/example.remind >/remind.txt && cat /remind.txt"
```

https://github.com/settings/notifications - require visiting website so not useful.

https://github.com/dawidd6/action-send-mail

https://stackoverflow.com/a/57989070/1072212 - pass values between steps