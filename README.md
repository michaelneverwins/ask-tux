# ask-tux
A silly Bash script. Ask a question, and Tux gives a random answer.

![(Tux answers in the affirmative.)](images/yes.png)

## Dependencies
The script, as written, requires the following:
* `bash`
* `tput`
* `figlet` with font `smmono9`
* `cowsay` with cowfile `tux`
* `lolcat`

Could it do without the `lolcat`? Sure. If you don't like it, change it after installing it. It's just Bash. You should learn Bash.

## Installation
1. Put `ask-tux` wherever you want it, preferably some location in your `PATH` e.g. `~/.local/bin/`.
2. Make it executable, e.g. with `chmod u+x`.

## Usage
```
ask-tux <your question here>
```

## Configuration
The script can be configured by opening it in a text editor. Add or remove lines from the `answers` array to modify the set of possible answers given by Tux. Delete everything from `if` through `fi` to remove the requirement of typing a question if you would prefer to speak your question aloud. Maybe get `spd-say` involved if you want the computer to speak the answers aloud. If you learn Bash, which I already told you to do, then you can figure that out.

## Disclaimers
This script comes with no warranty of any kind. Use it at your own risk. If it magically breaks something, or whatever, it's your fault. You should learn Bash and then look at the script before running it. It's literally just a list of phrases and a few shell commands, the latter of which I wrote in my spare time because I was bored, and is shared here just in case anyone might find it amusing.

If someone else already wrote a substantially similar script, I'm sorry. If we both thought of it independently, then it must not be a very original idea, and I'm sorry for that too. If, say, the manufacturer of some fortune-telling toy doesn't like the fact that this script's default list of Tux answers is not very original either, then I guess I'm sorry for that as well. I just found this list of 20 phrases on some weird Wikipedia page about pool or billiards or something.
