---
description: Last updated 1/16/25
cover: >-
  https://images.unsplash.com/photo-1648217736318-fbc4abc138ec?crop=entropy&cs=srgb&fm=jpg&ixid=M3wxOTcwMjR8MHwxfHNlYXJjaHwxfHxjb2ZmZWUlMjBib29rfGVufDB8fHx8MTczNzA4NjcxMHww&ixlib=rb-4.0.3&q=85
coverY: 0
---

# Virtual Environments

My first error in the course was solved due to a virtual environment issue. So let's talk about setting up a virtual environment, specifically conda on a Mac.

> I will add that it is my understanding that a new virtual environment is encouraged for each module - though there may be one module that does not need one? I will update this page once I know the answer!

### \[Optional] Brew install iterm2&#x20;

It was recommended to me to use iterm2&#x20;

1. Do you have homebrew installed?
   1. Open a terminal window and type

```bash
brew
```

&#x20;       b. If yes, continue. If no, installl homebrew - details [https://docs.brew.sh/Installation](https://docs.brew.sh/Installation)

2. brew install iterm2

&#x20;

### Conda

1. You may need to install [Anaconda](https://docs.anaconda.com/anaconda/install/), so head over to the site if you do not have the application.
2. Open iterm2 _(a terminal window)_ and type

```bash
python -V
```

_This will show your python version for your awareness_

3. Now the fun part, create an environment! Remember, we will want a different environment for each project. I am using python version 3.12, so the command is

```bash
conda create -n myenvname python=3.12
```

4. Now we want to add our packages that are **not** included in the standard library, such as pandas. To do that, we need to `activate` the environment and then `pip install` what we need.

```bash
conda activate myenvname
```

In your terminal, your myenvname of choice should now show at the far left of your command promt in parentheses like&#x20;

_(myenvname) Kaylas-MacBook-Air:data-engineering-zoomcamp-my-work kayla$_

```bash
pip install pandas sqlalchemy psycopg2-binary jupyterlab
```



In the future, to use these packages, we _**import**_ them into our python scripts. For example, for pandas we would write `import pandas as pd` at the top of our python script.



<details>

<summary>Briefly discussed w/ course instructur but not used</summary>

1. UV - [https://docs.astral.sh/uv/getting-started/installation/#pypi](https://docs.astral.sh/uv/getting-started/installation/#pypi)
2.

</details>



