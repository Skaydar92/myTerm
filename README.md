# PLEASE READ

i would not recommend to use this if you have epilepsy since there is A LOT of flickering which i havent quite figured out how to get rid of just yet.

# myTerm

its a terminal emulator that by default loads my own shell so you probably have to adjust the code and recompile so it loads bash or zsh or whatever

to change default shell just adjust path in terminal.go under

func main() {
    ...
    c := exec.Command("$PATH_TO_SHELL_YOU_WANT_TO_USE")
    ...
}

yeah then it should work if it feels like it
