# arbeit
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FJanAhrens%2Farbeit.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2FJanAhrens%2Farbeit?ref=badge_shield)


**arbeit** is my tool for tracking working hours. It stores the daily
working hours in JSON. The file gets versioned with Git (*planned feature*).

# Setup

Install required packages with pip:

> pip install -r requirements.txt

Create a directory:

> mkdir $HOME/.arbeit && cd $HOME/.arbeit && git init

Setup the ARBEIT_PATH:

> echo 'export ARBEIT_PATH=$HOME/.arbeit/' >> $HOME/.profile

# Usage

Display today's working hours:

> arbeit today

Track the start of the day (uses the current time):

> arbeit start

End your day (uses the current time):

> arbeit end

Take a break:

> arbeit break


## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FJanAhrens%2Farbeit.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2FJanAhrens%2Farbeit?ref=badge_large)