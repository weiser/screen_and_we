# screen_and_we

Create a pair-programming session via `screen`.  It creates a shared
screen session with a customizable git username and email so that you
can work together with a buddy and commit your changes together.

## Prerequisites

`git` and `screen` must be installed.

## Usage

```bash
./screen_and_we

What is the name of Player 1?

What is the name of Player 2?

What email is associated with this session?

Your screen session is now available via: `screen -S
<player1>-v-<player2>`
```

Now, when you commit, the commit messages will have a username of
"<player1> v <player2>" and a email of "<email>"

