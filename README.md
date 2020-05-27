# test-results
Repository to persist test results for existing dotCMS projects.

Currently starting with the `core` repo to persit its test results.

## Directory Structure
Since this repo might be used to keep results from multiple dotCMS repos, branches/commits, test type and sometimes database type, we need to introduce a directory structure similar to this one:
```
projects
|--core
|  |--<branch>
|  |  |--curl
|  |  |  |--mysql
|  |  |  |  |__reports
|  |  |  |     |__html
|  |  |  |        |__index.html
|  |  |  |__postgres
|  |  |     |__reports
|  |  |        |__html
|  |  |           |__index.html
|  |  |--integration
|  |  |  |--mysql
|  |  |  |  |__reports
|  |  |  |     |__html
|  |  |  |        |__index.html
|  |  |  |__postgres
|  |  |     |__reports
|  |  |        |__html
|  |  |           |__index.html
|  |  |__unit
|  |     |__reports
|  |        |__html
|  |           |__index.html
|  |__17bc4fd9
|     |--curl
|     |  |--mysql
|     |  |  |__reports
|     |  |     |__html
|     |  |        |__index.html
|     |  |__postgres
|     |     |__reports
|     |        |__html
|     |           |__index.html
|     |--integration
|     |  |--mysql
|     |  |  |__reports
|     |  |     |__html
|     |  |        |__index.html
|     |  |__postgres
|     |     |__reports
|     |        |__html
|     |           |__index.html
|     |__unit
|        |__reports
|           |__html
|              |__index.html
|
|
|__core-web
...
```
