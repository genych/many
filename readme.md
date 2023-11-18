#### what:
* is it possible to serve multiple apps simultaneously?
* share data between containers?
* debug/profile and webgrind?

#### how:
* update /etc/hosts with
```
127.0.0.1  shiny.stuff.local
127.0.0.1  debuggable.stuff.local
127.0.0.1  grind.stuff.local
```
* `docker compose up -d`

#### todo:
* are they connected? can I do `POST shiny.stuff.local/api/hello` from the debuggable and vice versa?
* can I serve static? from both?
* debug both?
