# pyMyShareAPI

**Important!  
We do not have access to the API at this point, as the API itself is not yet launched.  
We will be updating this repo as soon as the situation changes!**

We have made the MyShare API easy to use.  

![License](https://img.shields.io/badge/License-white?logo=data:image/svg%2bxml;base64,PHN2ZyB2ZXJzaW9uPSIxLjEiIGlkPSJDYXBhXzEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHg9IjBweCIgeT0iMHB4IiB2aWV3Qm94PSIwIDAgMTg0LjY1MyAxODQuNjUzIiBzdHlsZT0iZW5hYmxlLWJhY2tncm91bmQ6bmV3IDAgMCAxODQuNjUzIDE4NC42NTM7IiB4bWw6c3BhY2U9InByZXNlcnZlIj4KPHBhdGggZD0iTTEyNS40MDEsMTg0LjY1M2MtMC4wMDksMC0wLjAxOCwwLTAuMDI2LDBIMjMuMTM0Yy0xLjY1NywwLTMtMS4zNDMtMy0zVjNjMC0xLjY1NywxLjM0My0zLDMtM2gxMzguMzg1YzEuNjU3LDAsMywxLjM0MywzLDMgIHYxNDEuNTVjMC4wMDEsMC4xMjMtMC4wMDYsMC4yNDUtMC4wMiwwLjM2NmMwLDAsMCwwLjAwMSwwLDAuMDAyYzAsMC4wMDIsMCwwLjAwNC0wLjAwMSwwLjAwNmMwLDAuMDAxLDAsMC4wMDIsMCwwLjAwMyAgYzAsMC4wMDIsMCwwLjAwNC0wLjAwMSwwLjAwN2MwLDAuMDAyLDAsMC4wMDQsMCwwLjAwNmMwLDAsMCwwLDAsMGMtMC4wMTUsMC4xMjMtMC4wMzgsMC4yNDQtMC4wNjcsMC4zNjMgIGMwLDAuMDAxLTAuMDAxLDAuMDAyLTAuMDAxLDAuMDA0YzAsMC4wMDEtMC4wMDEsMC4wMDItMC4wMDEsMC4wMDNjMCwwLjAwMi0wLjAwMSwwLjAwNC0wLjAwMSwwLjAwNmwwLDAuMDAxICBjLTAuMTI0LDAuNDgzLTAuMzY5LDAuOTM3LTAuNzI1LDEuMzE0YzAsMCwwLDAsMCwwYy0wLjAwMiwwLjAwMi0wLjAwNCwwLjAwNC0wLjAwNiwwLjAwNmwwLDBjLTAuMDAyLDAuMDAyLTAuMDA0LDAuMDA0LTAuMDA2LDAuMDA2ICBsMCwwYy0wLjAwMiwwLjAwMi0wLjAwMywwLjAwMy0wLjAwNSwwLjAwNWMwLDAuMDAxLTAuMDAxLDAuMDAxLTAuMDAyLDAuMDAyYy0wLjAwMSwwLjAwMS0wLjAwMiwwLjAwMy0wLjAwNCwwLjAwNCAgYzAsMC0wLjAwMSwwLjAwMS0wLjAwMiwwLjAwMmMtMC4wMDIsMC4wMDItMC4wMDQsMC4wMDQtMC4wMDYsMC4wMDZsLTM2LjExNywzNy4wODJjLTAuMDA0LDAuMDA0LTAuMDA5LDAuMDA5LTAuMDEzLDAuMDE0bDAsMCAgYy0wLjAwMiwwLjAwMi0wLjAwNCwwLjAwNC0wLjAwNywwLjAwN2wwLDBjLTAuMDAyLDAuMDAyLTAuMDA0LDAuMDA0LTAuMDA2LDAuMDA2YzAsMCwwLDAtMC4wMDEsMC4wMDEgIGMtMC4wMDEsMC4wMDEtMC4wMDMsMC4wMDMtMC4wMDUsMC4wMDVjMCwwLTAuMDAxLDAuMDAxLTAuMDAyLDAuMDAxYy0wLjAwMSwwLjAwMi0wLjAwMywwLjAwMy0wLjAwNCwwLjAwNSAgYy0wLjAwMSwwLjAwMS0wLjAwMiwwLjAwMi0wLjAwMywwLjAwMmMtMC4wMDEsMC4wMDEtMC4wMDIsMC4wMDItMC4wMDMsMC4wMDNjLTAuMDAxLDAuMDAxLTAuMDAyLDAuMDAyLTAuMDA0LDAuMDA0ICBjMCwwLDAsMC4wMDEtMC4wMDEsMC4wMDFjLTAuMzkyLDAuMzg0LTAuODczLDAuNjQ1LTEuMzg1LDAuNzdjLTAuMDA0LDAuMDAyLTAuMDA2LDAuMDAxLTAuMDA5LDAuMDAyICBjLTAuMDAxLDAuMDAxLTAuMDA0LDAuMDAxLTAuMDA4LDAuMDAyYy0wLjAwMywwLTAuMDA1LDAuMDAxLTAuMDA4LDAuMDAyYy0wLjAwMiwwLjAwMS0wLjAwNiwwLTAuMDA4LDAuMDAyICBjLTAuMDAzLDAtMC4wMDgsMC4wMDItMC4wMDgsMC4wMDJjLTAuMDAzLDAtMC4wMDksMC4wMDEtMC4wMDksMC4wMDFjLTAuMDI3LDAuMDA2LTAuMDU0LDAuMDEyLTAuMDgyLDAuMDE3bDAsMCAgYy0wLjAwMywwLTAuMDA2LDAuMDAxLTAuMDA5LDAuMDAyYzAuMDAxLDAuMDAzLTAuMDA1LDAuMDAxLTAuMDA5LDAuMDAxYy0wLjAwMi0wLjAwMS0wLjAwNSwwLTAuMDA4LDAuMDAxICBjLTAuMDA2LDAuMDAxLTAuMDA2LDAuMDAxLTAuMDA5LDAuMDAyYy0wLjAwMiwwLTAuMDA1LDAuMDAxLTAuMDA4LDAuMDAxYy0wLjAwMiwwLTAuMDA1LDAuMDAxLTAuMDA5LDAuMDAxICBjLTAuMDAzLDAuMDAxLTAuMDA1LDAuMDAyLTAuMDA4LDAuMDAxQzEyNS43NSwxODQuNjM4LDEyNS41NzYsMTg0LjY1MywxMjUuNDAxLDE4NC42NTN6IE0yNi4xMzQsMTc4LjY1M2g5Ni4yNjh2LTM0LjA4MiAgYzAtMS42NTcsMS4zNDMtMywzLTNoMzMuMTE3VjZIMjYuMTM0VjE3OC42NTN6IE0xMjguNDAyLDE0Ny41NzF2MjYuNzAybDI2LjAwNy0yNi43MDJIMTI4LjQwMnogTTEzMy4wNzIsMTMxLjE5SDQwLjY5OCAgYy0xLjY1NywwLTMtMS4zNDMtMy0zczEuMzQzLTMsMy0zaDkyLjM3NWMxLjY1NywwLDMsMS4zNDMsMywzUzEzNC43MjksMTMxLjE5LDEzMy4wNzIsMTMxLjE5eiBNMTQzLjQ2LDExNy42NDhINDAuNjk4ICBjLTEuNjU3LDAtMy0xLjM0My0zLTNzMS4zNDMtMywzLTNIMTQzLjQ2YzEuNjU3LDAsMywxLjM0MywzLDNTMTQ1LjExNywxMTcuNjQ4LDE0My40NiwxMTcuNjQ4eiBNNjAuOTY3LDk4Ljc5MiAgYy0wLjEzNiwwLTAuMjcyLTAuMDA5LTAuNDA5LTAuMDI4bC0yMi45MDItMy4xNTFjLTAuODI1LTAuMTE0LTEuNTY2LTAuNTY1LTIuMDQ1LTEuMjQ3Yy0wLjQ3OS0wLjY4Mi0wLjY1My0xLjUzMS0wLjQ4MS0yLjM0NiAgbDcuMTM0LTMzLjczNGMtNS4wNjYtNS4wMzctNy45NjktMTIuMTg1LTcuMzQ5LTE5Ljg0NmMxLjExOC0xMy44MDUsMTMuMjUyLTI0LjEzLDI3LjA2My0yMy4wMDkgIGMxMy44MDUsMS4xMTgsMjQuMTI3LDEzLjI1OCwyMy4wMDksMjcuMDYzYy0wLjUxLDYuMjk4LTMuMzE1LDExLjg3Mi03LjUyNSwxNS45NjVsNi44NzQsMjYuODQ3YzAuMjEsMC44MTksMC4wNjQsMS42ODktMC40MDEsMi4zOTUgIHMtMS4yMDcsMS4xODMtMi4wNDIsMS4zMTNMNjQuMDYsOTEuNzk2bC0wLjA5Myw0LjA2NGMtMC4wMiwwLjg1NS0wLjQwMywxLjY2MS0xLjA1NCwyLjIxNSAgQzYyLjM2Nyw5OC41NDEsNjEuNjc2LDk4Ljc5Miw2MC45NjcsOTguNzkyeiBNNDEuNjY3LDkwLjEwN2wxNi4zNzgsMi4yNTRsMC42MTMtMjYuODFjLTAuMjQ0LTAuMDEzLTAuNDg4LTAuMDI5LTAuNzMzLTAuMDQ5ICBjLTMuNzc0LTAuMzA2LTcuMjg4LTEuNDM1LTEwLjM3OC0zLjE5N0w0MS42NjcsOTAuMTA3eiBNNjQuMjI1LDg0LjU1NGwwLjI1NiwxLjEwNGwxMy4yMjMtMi4wNjNMNzIuMjY1LDYyLjM1ICBjLTIuMzM2LDEuMzE5LTQuODk2LDIuMjczLTcuNTk2LDIuNzkxTDY0LjIyNSw4NC41NTR6IE01OS45MTksMjEuMzQ3Yy00LjUyOCwwLTguODY0LDEuNTg5LTEyLjM1Miw0LjU1NCAgYy0zLjg5MSwzLjMwOC02LjI2LDcuOTMzLTYuNjcyLDEzLjAyM2MtMC44NTEsMTAuNTA3LDcuMDA2LDE5Ljc0OCwxNy41MTQsMjAuNTk5YzEwLjUwNSwwLjg1NSwxOS43NDctNy4wMDYsMjAuNTk4LTE3LjUxMyAgYzAuODUxLTEwLjUwNy03LjAwNS0xOS43NDgtMTcuNTEzLTIwLjU5OUM2MC45NjcsMjEuMzY4LDYwLjQ0MiwyMS4zNDcsNTkuOTE5LDIxLjM0N3ogTTE0My40Niw2My4yMDdoLTQyLjM5Yy0xLjY1NywwLTMtMS4zNDMtMy0zICBzMS4zNDMtMywzLTNoNDIuMzljMS42NTcsMCwzLDEuMzQzLDMsM1MxNDUuMTE3LDYzLjIwNywxNDMuNDYsNjMuMjA3eiBNMTM3LjQwNiw0Ny4yMzlIMTAxLjA3Yy0xLjY1NywwLTMtMS4zNDMtMy0zczEuMzQzLTMsMy0zICBoMzYuMzM1YzEuNjU3LDAsMywxLjM0MywzLDNTMTM5LjA2Miw0Ny4yMzksMTM3LjQwNiw0Ny4yMzl6IE0xNDMuNDYsMzAuMzAxaC00Mi4zOWMtMS42NTcsMC0zLTEuMzQzLTMtM3MxLjM0My0zLDMtM2g0Mi4zOSAgYzEuNjU3LDAsMywxLjM0MywzLDNTMTQ1LjExNywzMC4zMDEsMTQzLjQ2LDMwLjMwMXoiLz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPGc+CjwvZz4KPC9zdmc+)

[![License](https://img.shields.io/pypi/l/pymyshareapi.svg?label=License&logo=license&logoColor=red&labelColor=white)](#edit-me)
[![MyShare](https://img.shields.io/badge/MyShare-white?logo=data:image/svg%2bxml;base64,PHN2ZyB2ZXJzaW9uPSIxLjEiIHZpZXdCb3g9IjAgMCA1NSA1NSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPGc+Cjxwb2x5Z29uIGNsYXNzPSIiIHBvaW50cz0iNTMuNjY4IDIyLjM3NCAzNC44NjggMjIuMjc0IDQxLjg2OCAzLjM3NDIgMzAuNDY4IDMuMjc0MiAyMy40NjggMjIuMTc0IDQuNjY4NSAyMi4wNzQgMC44Njg0NSAzMS44NzQgMTkuNzY4IDMxLjk3NCAxMi43NjggNTAuODc0IDI0LjE2OCA1MC45NzQgMzEuMTY4IDMyLjA3NCA0OS45NjggMzIuMTc0IiBmaWxsPSIjOEFCQThCIi8+Cjxwb2x5Z29uIGNsYXNzPSIiIHBvaW50cz0iNTMuNjY4IDIyLjM3NCAzNC44NjggMjIuMjc0IDQxLjg2OCAzLjM3NDIgMzAuNDY4IDMuMjc0MiAyMy40NjggMjIuMTc0IDE5Ljc2OCAzMS45NzQgMzEuMTY4IDMyLjA3NCA0OS45NjggMzIuMTc0IiBmaWxsPSIjM0UzRTNFIi8+CjwvZz4KPC9zdmc+Cg==)](#pyMyShareAPI)
[![Open source](https://img.shields.io/badge/Open_Source-white?logo=GitHub-Sponsors&logoColor=red)](#pyMyShareAPI)  
[![PyPi](https://img.shields.io/pypi/v/pymyshareapi.svg?logo=pypi&label=PyPi&labelColor=white)](https://pypi.org/project/pymyshareapi/)
[![Python versions](https://img.shields.io/pypi/pyversions/pymyshareapi.svg?label=Python&logo=python&labelColor=white)](https://pypi.org/project/pymyshareapi/)
[![Downloads](https://img.shields.io/pypi/dm/pymyshareapi?labelColor=white&logo=pypi&label=Downloads)](https://pypistats.org/packages/pymyshareapi)

## Table on contents

- [Introduction](#introduction)
- [API support](#api-support)
- [Installing](#installing)
- [Getting started](#getting-started)
- [Documentation](#documentation)
- [Getting help](#getting-help)
- [Contributing](#contributing)
- [License - key points](#license---key-points)

## Introduction

We are currently waiting on MyShare API to launch.  
This project will start as soon as we have access to the newly created API.

## API support

We are currently supporting the following methods:

- [ ] Method name
- [x] Method name
- [ ] Method name

## Installing

More info to come...

## Getting started

More info to come...

## Documentation

- Thake a look at our [PMA Wiki](https://github.com/LeanderGangso/pyMyShareAPI/wiki).

- The origional [MyShare API](https://api.myshare.today).

## Getting help

Report bugs, request new features or ask questions by [creatin an issue](https://github.com/LeanderGangso/pyMyShareAPI/issues/new/choose) or [a discussion](https://github.com/LeanderGangso/pyMyShareAPI/discussions/new).

## Contributing

Contributions of all sizes are welcome. Please review our [contribution guidelines](https://github.com/LeanderGangso/pyMyShareAPI/blob/master/CODE_OF_CONDUCT.md) to get started. You can also help by [reporting bugs](https://github.com/LeanderGangso/pyMyShareAPI/issues/new/choose).

## License - key points

To be determined...
<!---
- When distributing derived works, the source code of the work must be made available under the same license.
- All modification's has to have the same license and be open source.
- You do not need to release you modified code, but we would really apreacheate it you did do a [pull request](https://www.freecodecamp.org/news/how-to-make-your-        first-pull-request-on-github-3/) with you changes.
--->

Disclaimer: I am not a lawyer, so any and all information given is strictly based on my understanding and may or may not be correct.
