# colemök

Finnish Colemak layout. Peculiarities:

- `ä` and `ö` take the place of the semicolon `;` and apostrophe `'` (very
respectively).
- `å` demoted to `o` on the 3rd layer (sorry!).
- `.` and `,` have their Finnish comparative counterparts `:` and `;` on the
Shift layer.
- Similarly, `<` and `>` are hanging at the bar `|` on the 102th.
- `'` and `"` cuddle together, spooning the ISO-ass Enter key.
- `/` and `\` leaning together next to the right Shift.
- `?` wanted to go next to the `!`, (impersonating `2`). `@` kicked to 3rd layer.
- On the 3rd some Greek + `©` `™` `®` `ß` `ü` `∞` `≠` and so on, added as needed.
- QWERTY vim movement keys "`hjkl`" (Colemak `hnei`) mapped to arrow keys.
- `CapsLock` is `Escape`, double `Shift` is `CapsLock`, double `Ctrl` changes layout.

## Default layer

```ascii-art
,---,---,---,---,---,---,---,---,---,---,---,---,---,-------,
| ` | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 0 | - | = | <-    |
|---'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-----|
| ->| | q | w | f | p | g | j | l | u | y | ä | [ | ] |     |
|-----',--',--',--',--',--',--',--',--',--',--',--',--'|    |
| Esc  | a | r | s | t | d | h | n | e | i | o | ö | ' |    |
|----,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'---'----|
| LS | < | z | x | c | v | b | k | m | , | . | / |  Shift   |
|----'-,-',--'--,'---'---'---'---'---'---',--'---',--,------|
| Ctrl |  | Alt |                         | AltGr |  | Ctrl |
'------'  '-----'-------------------------'-------'  '------'
```

## Shift layer

```ascii-art
,---,---,---,---,---,---,---,---,---,---,---,---,---,-------,
| ~ | ! | ? | # | $ | % | ^ | & | * | ( | ) | _ | + | <-    |
|---'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-----|
| ->| | Q | W | F | P | G | J | L | U | Y | Ä | { | } |     |
|-----',--',--',--',--',--',--',--',--',--',--',--',--'|    |
| Esc  | A | R | S | T | D | H | N | E | I | O | Ö | " |    |
|----,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'---'----|
| LS | > | Z | X | C | V | B | K | M | ; | : | \ |  Shift   |
|----'-,-',--'--,'---'---'---'---'---'---',--'---',--,------|
| Ctrl |  | Alt |                         | AltGr |  | Ctrl |
'------'  '-----'-------------------------'-------'  '------'
```

## AltGr layer (WIP)

```ascii-art
,---,---,---,---,---,---,---,---,---,---,---,---,---,-------,
|   | ¡ | @ | € |   | ‰ | ^ |   | ∞ |   | ° | ¯ | ≠ | <-    |
|---'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-----|
| ->| |   |   | φ | π | γ |   | λ | ü | ¥ | æ |   |   |     |
|-----',--',--',--',--',--',--',--',--',--',--',--',--'|    |
| Esc  | α | ® | ß | τ | δ |   |   |   |   | å | œ | ` |    |
|----,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'---'----|
| LS | | | ʒ | x | © | š | β | κ | µ | ¸ | " | – |  Shift   |
|----'-,-',--'--,'---'---'---'---'---'---',--'---',--,------|
| Ctrl |  | Alt |                         | AltGr |  | Ctrl |
'------'  '-----'-------------------------'-------'  '------'
```

### ColemöXXör (moexxoer)

Numbers are demoted to Shift layer for ultimate mökki-häcking!

### Colemäk-GM

For Grandmasters? The `ä` and `ö` are as in Manu Järvinen's [Colemäk](https://colemaek.github.io/),
but instead of the Colemak-DH mod, this is just based on the plain-old caveman Colemak.
I don't yet know if `ä`/`ö` and `,`/`.` good, I keep flipping them. Haven't
really tried this, for the moment mine feels better: the `-lä` bigram is pretty harsh...

```ascii-art
,---,---,---,---,---,---,---,---,---,---,---,---,---,-------,
| ` | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 0 | - | = | <-    |
|---'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-----|
| ->| | q | w | f | p | g | j | l | u | y | . | [ | ] |     |
|-----',--',--',--',--',--',--',--',--',--',--',--',--'|    |
| Esc  | a | r | s | t | d | h | n | e | i | o | , | ' |    |
|----,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'---'----|
| LS | < | z | x | c | v | b | k | m | ä | ö | / |  Shift   |
|----'-,-',--'--,'---'---'---'---'---'---',--'---',--,------|
| Ctrl |  | Alt |                         | AltGr |  | Ctrl |
'------'  '-----'-------------------------'-------'  '------'
```

## Quickstart

- Clone repo

```sh
git clone https://github.com/quunnb/colemoek && cd colemoek
```

- Copy files

```sh
cp colemoek /usr/share/X11/xkb/symbols/
```

- Load keymap

```sh
setxkbmap colemoek
```
