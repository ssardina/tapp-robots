# Team App Robots

This repo contains a set of web robots to automatize interactions with the [Team App web interface](https://www.teamapp.com) for a club. It was created to support [Brunswick Magic](https://www.brunswickmagic.com/) club (Melbourne, Australia).

Two robots are available:

1. A robot to delete a list of current members.
2. A robot to delete all chat rooms.

These robots are usually run when a new season is started, and the whole framework needs to be reset to reflect the new teams and people in the club.

## Pre-requisites

The robot notebooks use **[Salenium](https://www.selenium.dev/)**, a package used to automate web browser interaction from Python.

* Salenium dev doc: https://www.selenium.dev/selenium/docs/api/py/index.html#
* Salenium with Python: https://selenium-python.readthedocs.io/
* Tutorial in Real Python: https://realpython.com/modern-web-automation-with-python-and-selenium/
* geckodriver (https://github.com/mozilla/geckodriver/releases) and put it in path
* Salenium webdriver: https://www.selenium.dev/documentation/overview/


## Usage

Notebooks are provided for each robot.

Before using the notebooks, it is important to create a Firefox profile that is alread logged into the club's Team App system. This is because the browser used by Python is not able to logged into Google accounts, but we can just re-use an existing profile.

Configure the start of each notebook to use the right profile.


