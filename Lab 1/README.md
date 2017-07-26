### Lab 1: Customize this skill for your city or town
[Click here](/Detailed Walkthrough/README.md) if you want detailed instructions for customizing this skill.

Think of your hometown, current city, or favorite city.  Jot down a list of your favorite restaurants and attractions.

Open your Lambda function and click on the Code tab.  Review the first section of the code that is customized for Gloucester.
There are static data blocks called ```languageStrings```, and a ```data {}``` object containing details and lists.
Carefully modify these green strings within the quotes to define the city, state, zip, restaurants, and attractions custom to your particular town.
Be sure to maintain quotes around all strings.  Single or double quotes around strings are both valid (```"``` or ```'```). Ensure all objects ```{key:value}``` and lists ```[item1, item2]``` are properly nested and terminated, as in the starting code sample.

Click **Save** to save the changes to your Lambda function.
[Test](https://github.com/alexa/alexa-cookbook/tree/master/testing) your function.
If it works well, please [publish your skill](https://developer.amazon.com/public/solutions/alexa/alexa-skills-kit/docs/publishing-an-alexa-skill)  for the world to enjoy.
