# anki-decks

__Q__: What is Anki?

__A__: Anki is a spaced repetition flashcard program.

<hr />

To learn more, take a look at https://apps.ankiweb.net and the [docs](https://apps.ankiweb.net/docs/manual.html#introduction).

# available decks

- __ETG__, structured after _Elektrotechnische Grundlagen - Heinz Meister_

# how to use a deck

- clone this repository
- get [Anki for desktop](https://apps.ankiweb.net) (Linux, Windows, macOS)
- to install the [CrowdAnki Plugin](https://ankiweb.net/shared/info/1788670778):
  - open Anki
  - click _Tools_, _Add-ons_, _Browse & Install..._
  - enter plugin id `1788670778`
  - restart Anki
- click _File_, _CrowdAnki: import from Disk_
  - select the folder of the deck that you'd like to import
- optional: [create an Anki account](https://ankiweb.net/account/register) to sync your decks, this allows you to
  - learn on your phone/tablet
  - learn using the [web interface](https://ankiweb.net/decks/)

# how to help out

Fork this repository, clone it, and start editing:

## editing with Anki

1. import the deck as per the previous section
2. edit the cards and/or create new ones
3. export your deck as _CrowdAnki Json Representation_

<img src="export.png"></img>

4. select the directory of this repo as a target
5. send me a pull request

## editing the json directly

1. edit the json directly (useful for minor changes)
2. send me a pull request

# conventions

- formulas are written in LaTeX
- try to keep questions and answers concise
- don't hotlink images, add them locally instead
- optional information, that's not neccessary to answer a question, follows a horizontal ruler tag (`<hr />`)
