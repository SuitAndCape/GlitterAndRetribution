<!-- README.md -->

Documentation Template
==========================================================================

## What?

This is a default repo.

--------------------------------------------------------------------------

## Table Of Blah Blah

- [What?](#what)
- [Table Of Blah Blah](#table-of-blah-blah)
- [Reasons](#reasons)
  + [Why?](#why)
  + [Show Us The Code!](#show-us-the-code)
    * [Alias](#alias)
- [Connect](#connect)
  + [GitHubs](#githubs)
    * [Personal GitHub](https://github.com/AESM)
    * [SuitAndCape GitHub](https://github.com/SuitAndCape)
  + [Miscellany](#miscellany)
    * [Website](https://SuitAndCape.github.io/)
    * [LinkedIn](https://www.linkedin.com/in/SuitAndCape)
    * [Dribbble](https://dribbble.com/SuitAndCape)
    * [Twitter](https://twitter.com/SuitAndCape)
- [LICENSE](https://github.com/SuitAndCape/AndTheTemplateOfDoom/blob/master/LICENSE)
- [User Stories, MVP, Specifications, & Pseudocode](https://github.com/SuitAndCape/AndTheTemplateOfDoom/blob/master/Stories_MVP_Specs_Pseudocode.md)
- [humans.txt](https://github.com/SuitAndCape/AndTheTemplateOfDoom/blob/master/humans.txt)

--------------------------------------------------------------------------

## Reasons

>First, a list of reasons why.  Then, the code.

### Why?
1. Ease
  - This makes my life slightly easier
2. Experience
  - I wanted to build an alias that could generate default repository files, so I did
3. Documentation
  - I love documentation
    + Obsessed with it
      * Seriously

### Show Us The Code!

I created an alias for my `~/.bash_profile` to copy these files over to whichever directory I'm in, generating my default Git repo needs.

#### Alias
```bash
## NOTE: must have `AndTheTemplateOfDoom` repo in the `~/Code directory`
## SOURCE: github.com/SuitAndCape/AndTheTemplateOfDoom
  ## `gitit` – Create personalized default Git repo setup
  alias gitit="cp ~/Code/AndTheTemplateOfDoom/README.md $PWD/README.md; cp ~/Code/AndTheTemplateOfDoom/humans.txt $PWD/humans.txt; cp ~/Code/AndTheTemplateOfDoom/Stories_MVP_Specs_Pseudocode.md $PWD/Stories_MVP_Specs_Pseudocode.md; cp ~/Code/AndTheTemplateOfDoom/LICENSE $PWD/LICENSE; cp ~/Code/AndTheTemplateOfDoom/.gitignore $PWD/.gitignore"
```

--------------------------------------------------------------------------

## Connect

### GitHubs
- **_Personal GitHub_**
  + https://github.com/AESM
- **_SuitAndCape GitHub_**
  + https://github.com/SuitAndCape

### Miscellany
- **_Website_**
  + https://SuitAndCape.github.io/
- **_LinkedIn_**
  + https://www.linkedin.com/in/SuitAndCape
- **_Dribbble_**
  + https://dribbble.com/SuitAndCape
- **_Twitter_**
  + https://twitter.com/SuitAndCape
