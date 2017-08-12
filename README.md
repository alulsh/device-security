# Device Security Presentation

A 10 minute presentation on laptop and phone (device) security for a [digital security workshop](https://www.meetup.com/DCLegalHackers/events/239489125/) for DC Legal Hackers/Georgetown Law/ACLU DC on Saturday, August 12th 2017 at Georgetown Law in Washington, D.C.

## Slides online

View the slides online at http://www.alexandraulsh.com/device-security/index.html.

## Content note

I published this presentation on GitHub for reference for workshop attendees. Though I tried to present standard security guidelines that probably won't expire any time soon, I will likely not be updating this presentation after the workshop.

## Viewing slides locally

This project uses [big](https://github.com/tmcw/big) to generate the presentation.

To view the slides locally:

```sh
git clone git@github.com:alulsh/device-security.git
cd device-security
npm install
npm install -g big-presentation
big-presentation-serve
```

## Making changes to the slides

The slides use a Markdown file called `index.md` for content. Make sure to regenerate the slides by running the command `big-presentation-compose` before running `big-presentation-serve` in order to see your changes.