# Regex Tutorial - Understanding "Matching a Username" Regex

## Introduction
This tutorial aims to provide a detailed explanation of the "Matching a Username" regex pattern. We will break down each component of the regex and explain its role, helping you understand the search pattern it defines.

## Summary
The regex pattern we'll be dissecting is: `^[a-z0-9_-]{3,16}$`

## Table of Contents
1. [Regex Components](#regex-components)
    1. [Anchors](#anchors)
    2. [Bracket Expressions](#bracket-expressions)
    3. [Quantifiers](#quantifiers)
2. [Grouping Constructs](#grouping-constructs)
3. [The OR Operator](#the-or-operator)
4. [Character Escapes](#character-escapes)
5. [Character Classes](#character-classes)
6. [Flags](#flags)
7. [Backreference Constructs](#backreference-constructs)
8. [Boundaries](#boundaries)
9. [Lookaround Assertions](#lookaround-assertions)
10. [Author](#author)

## Regex Components

A regex is a literal pattern wrapped in slashes (/). Let's examine the "Matching a Username" regex:

Note: JavaScript provides two ways to create a regex object - literal notation and RegExp constructor.

### Anchors
The `^` anchor signifies the start of a string, and `$` signifies the end. In our regex, the string must start and end with `[a-z0-9_-]`.

### Bracket Expressions
Anything inside square brackets `[]` represents a range of characters to match. We can include lowercase letters, numbers, underscores, and hyphens in our pattern.

### Quantifiers
Quantifiers set limits for a match. `{3,16}` means the string must be 3 to 16 characters long.

## Grouping Constructs

Grouping constructs, denoted by `()`, help break down complex regex patterns into manageable subexpressions.

## The OR Operator

The OR operator `|` allows for multiple alternative matches within a regex.

## Character Escapes

The backslash `\` in a regex escapes a character, interpreting it literally.

## Character Classes

Character classes define sets of characters that can fulfill a match. Examples include `\d` (digits), `\w` (alphanumeric), and `\s` (whitespace).

## Flags

Flags provide additional functionality to regex patterns. Common flags are `g` (global), `i` (case-insensitive), and `m` (multi-line).

## Backreference Constructs

Backreferences (\1, \2, ...) capture and reuse matched substrings within the regex.

## Boundaries

Boundaries (\b, \B) match positions rather than characters, such as the start or end of a word.

## Lookaround Assertions

Lookaround assertions (lookahead and lookbehind) assert whether a pattern is followed or preceded by another pattern.

## Author Information
------------------

This tutorial was written by [Josue Feliciano](https://github.com/JoFel7), a web development enthusiast and avid learner.
Email me here at [josuefeliciano7@gmail.com](josuefeliciano7@gmail.com)