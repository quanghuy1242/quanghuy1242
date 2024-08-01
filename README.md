## Hi, I'm Huy 🎉

![](https://komarev.com/ghpvc/?username=quanghuy1242&label=📚&style=flat)

```python
async build_good_things(
  backend: BackendStuff, frontend: FrontendStuff,
  cloud: Union[GCP, Azure], monitor_tool: Monitoring
) -> None:
  # Let's build the back
  backend.build().connect(postgresql)

  # Then connect with the front
  frontend.build().connect(backend)

  # Serve them
  cloud.host(backend, frontend)

  # Don't forget to monitor closely
  monitor_tool.monitor(cloud)

asyncio.run(ci.manage(build_good_things()))
```

## Contacts
- Drop a message in `quanghuy1242/quanghuy1242` repo
- Mail to quanghuy1242@gmail.com

## My personal blog (Vietnamese)
- https://blog.quanghuy.dev
- https://www.linkedin.com/in/quanghuy1242/
