<p align="center">
  <a href="https://imgur.com/nBF0w5gC"><img src="https://imgur.com/nBF0w5g.png" height="10%" width="10%" title="header image"/></a>
</p>

# GameFinder
GameFinder is an Alexa Skill which allows user using voice controls to prompt the user to search for details about video games, locations in games and characters in games.

## Table of contents

## Getting Started

- Setup blank folder
- Right click on project folder
- Git clone https://github.com/cian2009/GestureBasedProject.git

### Prerequisites

Amazon Echo & Alexa:
[Amazon Echo Range](https://www.amazon.co.uk/dp/B0792KWK57/ref=fs_dn)

Alexa Developer Account:
[Alexa Developer Console](https://developer.amazon.com/alexa/console/ask)

AWS Account to access AWS Lambda:
[AWS Lambda](https://aws.amazon.com/lambda/)

Download Node.js
[Node.js](https://nodejs.org/en/)

### Installing

A step by step series of examples that tell you have to get a development env running

1. Set-up Alexa Skill in the Alexa Development Console

2. Set-up AWS Lambda function

3. Set-up Git Repository

```
Git clone https://github.com/cian2009/GestureBasedProject
```

4. npm install

5. Initialise project using ASK CLI
```
ask init
```

## Running the tests

### Intent Examples

#### Game

> Alexa ask game finder what is Fallout 3

Audio:                |  UI:
:-------------------------:|:-------------------------:
![](https://imgur.com/jnvMdus.png)  |  ![](https://imgur.com/HVfg2Lo.png)

#### Location

> Alexa ask game finder what is Megaton

Audio:                |  UI:
:-------------------------:|:-------------------------:
![](https://imgur.com/1bs61A4.png)  |  ![](https://imgur.com/84hGbu4.png)

#### Character

> Alexa ask game finder who is Master Chief

Audio:                |  UI:
:-------------------------:|:-------------------------:
![](https://imgur.com/BUINYCy.png)  |  ![](https://imgur.com/pqciSk6.png)

#### Phrase not built into intent

Due to how alexa works to find which intent works best with what the user is trying to call, we can also used phrases not built into how intents are called.
Alexa is very good at adapting to the user using a phrase outside what the intents have been built to use.

Example call:
<img src="https://imgur.com/TW7ifza.png"/>

Audio:                |  UI:
:-------------------------:|:-------------------------:
![](https://imgur.com/9UvoktQ.png)  |  ![](https://imgur.com/lcAoGlD.png)

## Alexa Skill Store Report

### Submission (Passed)

#### Automatic Review
Validation:                |  Functional test:
:-------------------------:|:-------------------------:
![](https://imgur.com/lU1Tvs3.png)  |  ![](https://imgur.com/KfVUAX8.png)

The automatic review just checked if the basic intents were programmed into the Skill and checked if the custom intents exsisted.
This review passed as it found no bugs and found custom intents and all five 'Built-In Intents' were programmed into the skill.

#### Manual Review
<img src="https://imgur.com/cEqiHM0.png"/>

The manual review is done by an employee at Amazon. The skill passed the manual review as the custom intents had enough content to get into the skill store.
And all five 'Built-In Intents' were present and working.

#### Certification Analysis
The Certification process was very quick and gave feedback along the way in order to make the process as painless as possible for developers.


## Videos

### Presentation
[![Presentation](https://imgur.com/9oJxbiZ.png)](https://www.youtube.com/watch?v=kANHj3TlU7M)

### Demo
[![Demo](https://imgur.com/teWgtUz.png)](https://www.youtube.com/watch?v=G4bOt0RVIpo)

## Conclusion

## Built With

* [Visual Studio Code](https://code.visualstudio.com/) - IDE used
* [Node.js](https://nodejs.org/en/) - Allows execution of JavaScript outside the browser
* [Alexa Developer Console](https://developer.amazon.com/alexa/console/ask) - Used to create and distribute the skill
* [AWS Lambda](https://aws.amazon.com/lambda/) - AWS Lamdba is used to host the source code used by the skill
* [Ask CLI](* [StackOverflow](https://stackoverflow.com/) - Community forum for troubleshooting) - Tool to manage Alexa skills and related resources
* [GiantBomb API](https://www.giantbomb.com/api/) - API used to access game, location and character information
* [StackOverflow](https://stackoverflow.com/) - Community forum for troubleshooting

## Authors

* **Cian Gannon** - *Source code, UI and Research* - [Github](https://github.com/cian2009)
* **Aron O Malley** - *Source code, UI and Research* - [Github](https://github.com/badwulf51)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details

## Store Page Details

* **[GameFinder](LINK HERE)** - Store page for skill
