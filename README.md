```sh
$ ./status_server
```

A little python server exposing a `/status` endpoint returning:

```json
{
  "calls": 10,
  "lifetime_calls": 654,
  "original_start": "Mon Jan 16 23:00:16 2017",
  "running": 145.33353304862976
}
```

to be consumed by the [status renderer][status-renderer]

[status-renderer]: https://github.com/composerinteralia/status-renderer
