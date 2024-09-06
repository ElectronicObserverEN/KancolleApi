https://ElectronicObserverEN.github.io/KancolleApi/

Repo to host the kancolle api definition (based on: https://github.com/peter-evans/swagger-github-pages).

The swagger doc is generated via the [KancolleApi](https://github.com/ElectronicObserverEN/ElectronicObserver/pull/496) project.
There are no guarantees that the doc is correct, and it's certainly incomplete.

Notes:
 - kancolle sends requests via form data, we send it as body
 - kancolle response data has a `svdata=` prefix, we don't
