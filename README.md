Jenkisfile PoC
===

Testing in production is bad. This is to test in a safe testing environment.



Local Testing
---

Use a small Jenkins!
```sh
docker compose up
```

Configure!
* Suggested Plugins
  * `2021-06-07 17:56:40.842+0000 [id=83]	INFO	h.m.UpdateCenter$CompleteBatchJob#run: Completed installation of 79 plugins in 1 min 14 sec`
* New admin user
* Shutdown: http://localhost:8080/exit
