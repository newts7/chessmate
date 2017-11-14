# Chessmate

* It's a small python - CLI based chess game developed during Python Game Challenge hosted at Fuelled office,
Noida on 11th Novemeber.

# Setup

* Clone Repo
```angular2html
$ git clone https://github.com/newts7/chessmate
```
* Install Dependencies
    
    * ```angular2html
      $ pip install Tkinter
        ```
 * Run chess.py
  ```angular2html
$ python chess.py
```


# How game works?

- **./chesslib/board.py** - provides logical support to complete chess game, contains
code for move validation/board rules.
- **./chesslib/pieces.py** - provides logical support to pieces moves
- **./chesslib/gui_tkinter.py** - provides pieces image to cli avatars.
- **./chess.py** - Controls flow of game.