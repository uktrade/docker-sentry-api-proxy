# sentry api proxy container

Accepts only POST requests matching regex: `\/api\/\d+\/(store|envelope)`
...and passes them through to host named `sentry-app`
