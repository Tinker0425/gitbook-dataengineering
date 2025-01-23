---
description: Last updated 1/22/25
icon: whale
cover: >-
  https://images.unsplash.com/photo-1616764814882-fb4bcfc5e277?crop=entropy&cs=srgb&fm=jpg&ixid=M3wxOTcwMjR8MHwxfHNlYXJjaHwxfHx3aGFsZSUyMHRhaWx8ZW58MHx8fHwxNzM3NjAwMzkzfDA&ixlib=rb-4.0.3&q=85
coverY: -64
---

# Docker-Compose Summary

:writing\_hand: To make sure I was understanding the final version of our Docker lesson, I did two things. I first worked through this quickstart [https://docs.docker.com/compose/gettingstarted/](https://docs.docker.com/compose/gettingstarted/) , which gave me another example of how to use docker-compose. I then went back and made sure I could use the docker-compose YAML file we created.

Thus, I \*think\* these are the steps we need to take if we were starting over:

{% stepper %}
{% step %}
### What is our goal?

:pencil: From you code editor

First, write your code and figure out what your goal is. In our case we are writing a python script `.py` that ingests `.csv` data in postgres. In my repo, I also created an `.env` file to hold our parameters.
{% endstep %}

{% step %}
### Dockerize it!

:pencil: From you code editor

Now we will need a Docker file and a docker-compose file. We use our Docker file to build our environment and you can find a full list of 'dictionary' options online. We use our docker-compose yaml file to create our server and container structures and then we can easily start or end the process in CLI.
{% endstep %}

{% step %}
### View it!

:black\_medium\_small\_square:Terminal & :globe\_with\_meridians: web browser

To view our work on the front end, we need to `docker-compose up -d` to run it and then open it's location on our browser. For our project, we are using local host and port 8080 (for pgAdmin).
{% endstep %}

{% step %}
### Use it!

:globe\_with\_meridians: web browser

Because our project end goal is being able to look at the data using SQL queries in pgAdmin, we now want to use it!&#x20;
{% endstep %}

{% step %}
### End

:black\_medium\_small\_square:Terminal

When you're done with your docker-compose be sure to end it by running `docker-compose down`
{% endstep %}
{% endstepper %}

### Resources

:scroll: My repo for this summary section can be found here:

{% @github-files/github-code-block url="https://github.com/Tinker0425/de-zoomcamp-my-work/tree/master/module-01/docker/summary" %}
