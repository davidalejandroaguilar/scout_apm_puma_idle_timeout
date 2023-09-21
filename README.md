# How to run

```
bundle install
RAILS_ENV=production SCOUT_DEV_TRACE=true bundle exec puma --idle-timeout=5
```

# What you'll see

```
➜  scout_apm_puma_idle_timeout git:(main) RAILS_ENV=production SCOUT_DEV_TRACE=true bundle exec puma --idle-timeout=5
[24972] Puma starting in cluster mode...
[24972] * Puma version: 6.4.0 (ruby 3.2.0-p0) ("The Eagle of Durango")
[24972] *  Min threads: 5
[24972] *  Max threads: 5
[24972] *  Environment: production
[24972] *   Master PID: 24972
[24972] *      Workers: 2
[24972] *     Restarts: (✔) hot (✖) phased
[24972] * Preloading application
[24972] * Listening on http://0.0.0.0:3000
[24972] Use Ctrl-C to stop
I, [2023-09-21T13:25:13.552425 #25097]  INFO -- : Installing Puma worker loop.
[24972] - Worker 0 (PID: 25097) booted in 0.0s, phase: 0
I, [2023-09-21T13:25:13.553455 #25098]  INFO -- : Installing Puma worker loop.
[24972] - Worker 1 (PID: 25098) booted in 0.0s, phase: 0
I, [2023-09-21T13:25:18.578334 #25100]  INFO -- : Installing Puma worker loop.
[24972] - Worker 1 (PID: 25100) booted in 0.0s, phase: 0
I, [2023-09-21T13:25:18.579079 #25101]  INFO -- : Installing Puma worker loop.
[24972] - Worker 0 (PID: 25101) booted in 0.0s, phase: 0
```
