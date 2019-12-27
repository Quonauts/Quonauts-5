# Quonauts (4.)5 — Rules

## Table of contents

* [**1. Meta rules**](#meta-rules)
    * [**1.1. Accuracy**](#accuracy)
    * [**1.2. Precedence**](#precedence)
    * [**1.3. Disallowed by default**](#disallowed-by-default)
    * [**1.4. Rule violations**](#rule-violations)
        * [**1.4.1. Errors**](#errors)
        * [**1.4.2. Judgements**](#judgements)
        * [**1.4.3. Punitive action**](#punitive-action)
    * [**1.5. Timezones**](#timezones)
    * [**1.6. Bots**](#bots)
    * [**1.7. Style conventions**](#style-conventions)
        * [**1.7.1. Content**](#content)
        * [**1.7.2. Headers and tags**](#headers-and-tags)
        * [**1.7.3. Rules**](#lists)
        * [**1.7.4. Formatting**](#formatting)
    * [**1.8. Glossary**](#glossary)
* [**2. Channels**](#channels)
    * [**2.1. #general**](#general-channel)
    * [**2.2. #proposals**](#proposals-channel)
    * [**2.3. #polls**](#polls-channel)
    * [**2.4. #rules**](#rules-channel)
* [**3. Roles**](#roles)
    * [**3.1. Rule offender**](#rule-offender)
* [**4. Activity**](#activity)
* [**5. Quantities**](#quantities)
* [**6. Polls**](#polls)
* [**7. Binding agreements**](#binding-agreements)
* [**8. Proposals**](#proposals)
    * [**8.1. Proposal content**](#proposal-content)
        * [**8.1.1. Conflict resolution**](#conflict-resolution)
        * [**8.1.2. Dependency resolution**](#dependency-resolution)
    * [**8.2. Voting on proposals**](#voting-on-proposals)
    * [**8.3. Closing proposals**](#closing-proposals)
    * [**8.4. Passing and failing proposals**](#passing-and-failing-proposals)
    * [**8.5. Proposal modification**](#proposal-modification)
* [**9. Actions**](#actions)
    * [**9.1. Claiming actions**](#claiming-actions)
* [**10. Win conditions**](#win-conditions)
    * [**10.1. Rounds**](#rounds)
* [**11. End of the game**](#end-of-the-game)

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

Judgements are rulings on the legality of a game action.

All judgements are made by the user known as <@!556954927969075225>.

If a judgement determines that a rule violation took place, the rule violation must be resolved, if it has not already.

#### <a name='punitive-action'/> Punitive action

If a player (hereby "the convicted player") is convicted, then another player may conduct a majority poll (called a "puninitive action poll") to determine whether punitive action should be taken.

Players should vote in favour of this poll if, and only if, they believe the convicted player violated the rules knowingly and with malicious intent.

Any vote in such a poll cast by the convicted player is not counted.

If a punitive action poll passes, then the convicted player gains one strike.

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
* **Clause**: A single statement in the rules.
* **Roll an n-sided die**: Randomly generate an integer between 1 and a given value, inclusively, with an equal chance of each possible result.

## <a name='channels'/> Channels

The game rules govern only messages and reactions in the GAME CHANNELS category of the Discord server.

Each subsection of this rule section corresponds to a game channel; as these subsections are created, removed, or reordered, game channels must be created/renamed/reordered accordingly.

### <a name='general-channel'/> #general

Players may converse freely in the <#607965760006127616> channel.

### <a name='proposals-channel'/> #proposals

The <#607966057981935710> channel is governed by [**8. Proposals**](#proposals).

### <a name='polls-channel'/> #polls

The <#607966084531748894> channel is governed by [**6. Polls**](#polls).

### <a name='rules-channel'/> #rules

The <#607966106891583518> channel contains this rules document.

## <a name='roles'/> Roles

Null.

### <a name='rule-offender'/> Rule offender

If a player has a nonzero number of strikes, then they are given the "rule offender" role. If a player's number of strikes reaches zero, the "rule offender" role is removed.

Players with the "rule offender" role may not make any game action; i.e. they may not participate in the game.

After 24 hours with the "rule offender" role, a player's number of strikes decreases by one.

## <a name='activity'/> Activity

All players that have taken some game action in the preceding 72 hours are active players. All other players are inactive players.

## <a name='quantities'/> Quantities

A quantity is a named property with a numerical value for each player.

By default any unique quantity added to the game:

    • applies to all players,
    • is instatiated at zero,
    • must always be an integer,
    • must never have a negative value,
    • cannot be traded or exchanged.

The following quantities exist within the game:

    • Point
    • Action
    • Strike
    • Money

## <a name='polls'/> Polls

A poll is a means of gathering the opinions of players on an issue. Players may conduct a poll by providing any necessary detail and posing a question in the <#607966084531748894> game channel. A poll that grants power to perform a game action or otherwise makes some formal determination (e.g. [%rule-violation-polls]) are formal polls; all others are informal polls.

Players may vote in favor of a poll by reacting to the poll with 👍. Players may vote against a poll by reacting to the poll with 👎.

Players may use any reaction they wish to respond to a poll. The player conducting the poll may interpret other reactions to the poll as they see fit, except in formal polls, where reactions may only have meaning as specified in the rules.

The player that posted a poll may edit it freely, as long as such edits do not change the meaning/intent of any existing reactions to the poll.

## <a name='binding-agreements'/> Binding agreements

One or more players may at any time create a binding agreement. It must be clear to all players, involved or uninvolved, that such an agreement is being made, and an agreement cannot be made without the support of all involved players A binding agreement has terms, which can govern any in-game actions (including sending messages) that the involved parties may take. The terms may make use of conditions based on exact times, certain actions, or any other criteria. At no point can the terms of a binding agreement be broken by a member of the agreement, and if such an event occurs, it should be handled like any violation of the rules.

## <a name='proposals'/> Proposals

Proposals can be made by posting them to the <#607966057981935710> game channel.

The first proposal is numbered #1 and each subsequent proposal's number is increased by 1. Deleted proposals retain their number.

A proposal is either open or closed. When it is first submitted a proposal is open. A closed proposal is either passed or failed. When a player closes a proposal, they must either pass it or fail it.

### <a name='proposal-content'/> Proposal content

A proposal can describe any number of actions that make changes to the game rules or otherwise alter the game state.

If a proposal describes a modification to the rules, it must unambiguously specify the rule section(s) to be modified and how they will be modified.

If a proposal describes the creation of a new rule section, it must specify its title, its location in relation to an existing one, and its content.

#### <a name='conflict-resolution'/> Conflict resolution

If multiple proposals describe the modification or addition of sections, paragraphs, or sentences to the same part of the rules, conflicts should be resolved based on the age of the proposal, such that the newer proposal's effect overrides the older one's. For example, if proposal #10 adds a new section "A" to the bottom of the rules, and proposal #11 adds a new section "B" to the bottom of the rules, and both proposals pass, then regardless of which proposal passed first, section "B" will appear below section "A" in the rules.

#### <a name='dependency-resolution'/> Dependency resolution

A proposal may state that it depends on other proposals. If a proposal's dependencies fail, then the proposal dependent on them also fails.

A proposals may amend an existing proposal. If a proposal A amends an existing proposal B, then the amendment has no effect if B fails. If A and B both pass, then the result of proposal B is undone or modified according to proposal A. The content of proposal B, however, does not change.

A proposal may also state incompatible proposals, in which case the later proposal will fail if any proposal it is incompatible proposal on is passed.

### <a name='voting-on-proposals'/> Voting on proposals

Each player may cast one vote on each open proposal.

Players may vote for or against a proposal. Players may also explicitly abstain from voting.

A player may change their vote on an open proposal at any time.

### <a name='closing-proposals'/> Closing proposals

Any player may close an open proposal if one or more of the following conditions is met:
 * The proposal is at least 48 hours (2 days) old.
 * All active players have cast a vote on the proposal.
 * A majority of active players have voted in favor of the proposal.
 * A majority of active players have voted against the proposal.

The player that authored a proposal may fail or delete it at any time.

When a player passes a proposal, that player must carry out the effects of that proposal and its passing to the best of their ability.

### <a name='passing-and-failing-proposals'/> Passing and failing proposals

When a proposal is closed, it passes if it has more votes in favour than against; otherwise, it fails.

### <a name='proposal-modification'/> Proposal modification

A player may edit a proposal they have submitted if that proposal is open for voting and has no votes cast by players other than its author.

## <a name='actions'/> Actions

Actions can be spent to effect changes to the game state. Actions may only be spent in a manner that is explicitly described in the game rules.

### <a name='claiming-actions'/> Claiming actions

A player may claim a number of actions equal to the number of 24-hour periods that have elapsed since they last claimed actions. A player may gain no more than 3 actions each time they claim actions.

## <a name='win-conditions'/> Win conditions

A player with 100 points wins the round.

### <a name='rounds'/> Rounds

One round of the game takes place at a time.

The first round begins immediately as the game begins. Each subsequent round begins as the preceding round ends.

A round ends when one or more players wins the round.

Whenever a round begins, all quantities are reset to their initial values.

## <a name='end-of-the-game'/> End of the game

The game ends if the game is won. This applies retroactively.

