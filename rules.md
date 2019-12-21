# Quonauts 5 — Rules

## Table of contents

* [**1. Meta rules**](#meta-rules)
    * [**1.1. Accuracy**](#accuracy)
    * [**1.2. Precedence**](#precedence)
    * [**1.3. Disallowed by default**](#disallowed-by-default)
    * [**1.4. Rule violations**](#rule-violations)
        * [**1.4.1. Errors**](#errors)
        * [**1.4.2. Judgements**](#judgements)
        * [**1.4.3. Appeals**](#appeals)
        * [**1.4.4. Punitive action**](#punitive-action)
    * [**1.5. Timezones**](#timezones)
    * [**1.6. Bots**](#bots)
    * [**1.7. Style conventions**](#style-conventions)
        * [**1.7.1. Content**](#content)
        * [**1.7.2. Headers and tags**](#headers-and-tags)
        * [**1.7.3. Rules**](#lists)
        * [**1.7.4. Formatting**](#formatting)
    * [**1.8. Glossary**](#glossary)
* [**2. Channels**](#channels)
    * [**2.1. #general**](#general)
    * [**2.2. #proposals**](#proposals)
    * [**2.3. #polls**](#polls)
    * [**2.4. #rules**](#rules)
* [**3. Roles**](#roles)
    * [**3.1. Rule offender**](#rule-offender)

## <a name='meta-rules'/> Meta rules

This section details how the rules are to be applied to the game.

### <a name='accuracy'/> Accuracy

This document is not guaranteed to always be up-to-date as the game rules are modified, however it is the duty of all players to keep this document accurate as game rules are modified. Where this document disagrees with the game rules, players must follow the game rules as they legally are, rather than their description in this document.

### <a name='precedence'/> Precedence

In the case of a contradiction between clauses, the following criteria are to be considered in turn until a clear determination can be made as to which clause takes precedence:

1. If one clause has a more limited scope than another, then the clause with the more limited scope takes precedence.
2. If one clause is negative while the other is positive, then the negative clause takes precedence.
3. The clause which appears last in the rules takes precedence.

### <a name='disallowed-by-default'/> Disallowed by default

Unless explicitly stated in the rules, all game actions are forbidden.

### <a name='rule-violations'/> Rule violations

A rule violation is a game action that is not permitted by the rules.

Resolving a rule violation is the process of reversing the immediate effects of that rule violation (not including any indirect effects permitted in reaction to the rule violation) to the extent that it is possible.

#### <a name='errors'/> Errors

An error is a rule violation made by a player either mistakenly or through ignorance. If a player causes a rule violation and is able to resolve the error, they may do so.

If a player resolves an error within 24 hours of making that error, and the resolution of the error leaves the game state in such fashion that it is as if the error had never occurred, no punitive action can be taken against the player.

#### <a name='judgements'/> Judgements

Judgements are rulings made by an official known as The Arbiter.

If any player ("the accusing player") believes that another player (hereby "the accused player") has violated the rules, then the accusing player may call upon The Arbiter to make a judgement. The accusing player must describe which sections or clauses of the rules were violated and what illegal game action was taken by the accused player. The Arbiter must make a judgement on whether a rule violation took place.

If The Arbiter determines that a rule violation took place, the rule violation must be resolved, if it has not already.

Whenever the Arbiter makes a judgement they may spend an action. If they do, they gain three points.

#### <a name='appeals'/> Appeals

If any player believes that a judgement made by The Arbiter is incorrect they may cite the specific judgement in an appeal poll.

Players should vote in favor of this poll if, and only if, they agree that the accused player violated the rules as described.

Any vote in such a poll cast by The Arbiter or the accused player in the cited judgement is not counted.

An appeal poll must be available for voting for at least 24 hours before any action may be taken as a result.

For any given ruling, only one appeal poll may be conducted.

An appeal poll may not be started more than seven days after the cited ruling.

If an appeal poll passes, any effects of the judgement are overturned.

#### <a name='punitive-action'/> Punitive action

Punitive action is to be determined by an official knows as The Justice.

If a player is judged to have violated the rules, The Justice must determine what punitive action is taken. The Justice may select any combination of the following:

* A fine of up to ten points
* An award of one strike.
* Stripping the player of any office held.

In addition, a player that has punitive action taken against them may not assume any office for 24 hours after punitive action is taken.

### <a name='timezones'/> Timezones

Unless otherwise specified, all times and dates are specified with respect to UTC.

### <a name='bots'/> Bots

Certain game functions may be performed automatically by automated "bots;" the behavior of such bots is not governed by the rules, and any function that bots may perform should be feasible, even if inconvenient, to do manually.

### <a name='style-conventions'/> Style conventions

This section and its subsections describe grammatical and stylistic conventions used throughout this ruleset.

Any player may edit the rules to conform to these style conventions. Edits made this way must otherwise be minimal; i.e. they may not change wording or meaning.

#### <a name='content'/> Content

* All rules should be written in English using proper English grammar and spelling.
* American and British English spelling are both acceptable.
* Where applicable, rules should be written using gender-neutral language, with "they/them/their" as a third-person pronoun, both singular and plural.
* Sentences should be separated by a single space.
* Paragraphs should be separated by a blank line.
* Each paragraph or list element must be shorter than 1000 characters.
* Rules may not contain invisible characters besides newlines, normal spaces, and (in special cases) tabs. Non-ASCII characters should be used sparingly.
* Double quotes should be preferred instead of single quotes. ASCII-compatible straight quotes should be used instead of "smart" quotes.

#### <a name='headers-and-tags'/> Headers and tags

* Each section must have a header and a tag.
* Headers must use [sentence case](https://en.wiktionary.org/wiki/sentence_case), and must be a short, succinct word or phrase (not a complete sentence) describing the section.
* A section tag must be a string of text begin with a lowercase letter, end with either a lowercase letter or a number, and may contain only lowercase letters `a`-`z`, digits `0`-`9`, and hyphens `-`.
* A rule's tag should resemble its header.
* Tags must be unique; no two rule sections may have the same tag.

#### <a name='lists'/> Rules

* Unordered lists should use a single asterisk followed by a space (`* `) before each list element.
* Ordered lists should use a single number followed by a period and a space (`1. `) before each list element.
* The numbers of a ordered list should start at `1` and increase by `1` for each element.
* Lists should not be nested.
* Lists should be separated by the paragraphs above and below by a blank line.
* Two lists of the same type can not be adjacent. (This is treated as one list when converted to Markdown.)

Within a given list, all elements should have the same style, chosen from the following:

* Elements are words or phrases, and do not end with a period.
* Elements are clauses ending in a period (or other punctuation), and optionally followed by complete sentences.
* Elements are complete sentences ending in a period, and optionally followed by more complete sentences.

#### <a name='formatting'/> Formatting

From [GitHub's "Mastering Markdown" document](https://guides.github.com/features/mastering-markdown/), the following may be used:

* Emphasis (italics and bold, not including double underscore `__`)
* Unordered and ordered lists (not nested)
* Links
* Inline code
* Automatic linking for URLs
* Strikethrough

Additionally, square brackets `[]` containing a tag will be converted into links to another rule section; e.g. `[%rule-tag]`. Discord mentions (@username, @role, and #channel) may be used, however they are not readable in GitHub-flavored markdown.

### <a name='glossary'/> Glossary

The definitions for terms listed here take precedence over their normal English meanings, however any terms defined in a specific section of the rules override these in the section in which they are defined and any subsections of that section. A section may also define terms for use in the whole document.

* **The Game**: The instance of Nomic which is governed by this rules document.
* **Game Action**: A game action is any message or reaction in a game channel or any other manipulation of game channels or quantities which are part of the game.
* **Game State**: A specific arrangement of all game rules, proposals, polls, votes and quantities.
* **Game Channel**: A game channel is any text or voice channel listed in the GAME CHANNELS channel category of the Discord server.
* **Player**: Any participant of the game.
* **The Rules**: The rules of the game, which are described by this document.
* **Section**: A part of the rules which is contained under one header, not including any subsections.
* **Subsection**: A section of the rules which is contained under another section.
* **Clause**: A single statement in the rules

## <a name='channels'/> Channels

The game rules govern only messages and reactions in the GAME CHANNELS category of the Discord server.

Each subsection of this rule section corresponds to a game channel; as these subsections are created, removed, or reordered, game channels must be created/renamed/reordered accordingly.

### <a name='general'/> #general

Players may converse freely in the <#607965760006127616> channel.

### <a name='proposals'/> #proposals

The <#607966057981935710> channel is governed by [**2.2. #proposals**](#proposals).

### <a name='polls'/> #polls

The <#607966084531748894> channel is governed by [**2.3. #polls**](#polls).

### <a name='rules'/> #rules

The <#607966106891583518> channel contains this rules document.

## <a name='roles'/> Roles

Null.

### <a name='rule-offender'/> Rule offender

If a player has a nonzero number of strikes, then they are given the "rule offender" role. If a player's number of strikes reaches zero, the "rule offender" role is removed.

Players with the "rule offender" role may not make any game action; i.e. they may not participate in the game.

After 24 hours with the "rule offender" role, a player's number of strikes decreases by one.

