## Logs are for humans to read. 

Logs a lot easier to process and query if you emit them in structured log form. This in turn makes your logs harder to read for humans. `humanlog` solves this by prettifying your structured logs and making them easier to use!

```
$ humanlog < /var/log/logfile.log
```

Structured logs are prettified, and the rest is left alone.

![2__fish___users_antoine_gocode_src_github_com_humanlogio_humanlog__fish_](https://cloud.githubusercontent.com/assets/1189716/4328545/f2330bb4-3f86-11e4-8242-4f49f6ae9efc.png)




Install `humanlog` with:
```
curl -L "https://humanlog.io/install.sh" | sh
```

Or follow the [instructions on the repo](https://github.com/humanlogio/humanlog#humanlog).
