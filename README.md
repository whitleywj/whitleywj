Build An Alexa High Low Game Skill using ASK Python SDK
=========================================

This Alexa sample skill is a template for a basic high-low game skill. The high low game is a game where the player tries to guess the target number between 1 to 100. After each incorrect guess, the player is informed if the target number is higher or lower than their current guess. This continues until the target number is guessed or the player gives up. This sample Alexa Skill is written in Python and demonstrates the use of session and persistent attributes.

<img src="https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexa-skills-kit/tutorials/quiz-game/header._TTH_.png" />

[![Voice User Interface](https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexa-skills-kit/tutorials/navigation/1-off._TTH_.png)](./instructions/1-voice-user-interface.md)[![Lambda Function](https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexa-skills-kit/tutorials/navigation/2-off._TTH_.png)](./instructions/2-lambda-function.md)[![Connect VUI to Code](https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexa-skills-kit/tutorials/navigation/3-off._TTH_.png)](./instructions/3-connect-vui-to-code.md)[![Testing](https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexa-skills-kit/tutorials/navigation/4-off._TTH_.png)](./instructions/4-testing.md)[![Customization](https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexa-skills-kit/tutorials/navigation/5-off._TTH_.png)](./instructions/5-customization.md)[![Publication](https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexa-skills-kit/tutorials/navigation/6-off._TTH_.png)](./instructions/6-publication.md)

## Let's Get Started
If this is your first time here, you're new to Alexa Skills Development, or you're looking for more detailed instructions, click the **Get Started** button below:

<p align='center'>
<a href='./instructions/1-voice-user-interface.md'><img src='https://developer.amazon.com/en-US/docs/alexa/custom-skills/steps-to-build-a-custom-skill.html'></a>
</p>


Be sure to take a look at the [Additional Resources](#additional-resources)!

### Usage

```text
Alexa, open high low game
	>> ...Would you like to play?
Yes
	>> ...Guess a number...
Five
	>> Five is too low. Try saying a larger number.
...
```

### Repository Contents	 
* `/lambda` - Back-End Logic for the Alexa Skill hosted on [AWS Lambda](https://aws.amazon.com/lambda/)
* `/models` - Voice User Interface and Language Specific Interaction Models
* `/instructions` - Step-by-Step Instructions for Getting Started

## Additional Resources

### Community

* [Amazon Developer Forums](https://forums.developer.amazon.com/spaces/165/index.html) - Join the conversation!
* [Hackster.io](https://www.hackster.io/amazon-alexa) - See what others are building with Alexa.

### Tutorials & Guides

* [Voice Design Guide](https://developer.amazon.com/designing-for-voice/) - A great resource for learning conversational and voice user interface design.
* [CodeAcademy: Learn Alexa](https://www.codecademy.com/learn/learn-alexa) - Learn how to build an Alexa Skill from within your browser with this beginner friendly tutorial on CodeAcademy!

### Documentation

*  [Official Alexa Skills Kit Python SDK](https://pypi.org/project/ask-sdk/)
*  [Official Alexa Skills Kit Python SDK Docs](https://alexa-skills-kit-python-sdk.readthedocs.io/en/latest/)
*  [Official Alexa Skills Kit Documentation](https://developer.amazon.com/docs/ask-overviews/build-skills-with-the-alexa-skills-kit.html)
