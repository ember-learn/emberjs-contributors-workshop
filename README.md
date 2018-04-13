# emberjs-contributors-workshop
This repository contains resources for you to run your own Ember.js
Contributor's Workshop, such as slides, participant instructions,
and survey templates. Please reach out to the authors for advice,
assistance, etc. We're here to help.

Made with :heart: by Jen Weber and Ricardo Mendes. Initially created for
EmberConf 2018.

# Participant instructions

Follow these instructions so that you are prepared for the Contributors Workshop!

Learn how to get started in Open Source with a quick tutorial in [this video](https://www.youtube.com/watch?v=FgqXdsK6ohE):

[![Alt text](https://img.youtube.com/vi/FgqXdsK6ohE/0.jpg)](https://www.youtube.com/watch?v=FgqXdsK6ohE)

## Pre-Work for Contributor's Workshop

Hi! Thanks for participating in the Ember.js Contributor’s Workshop!

We only have 3 hours for the event, so help make the most of your time, there are some things you need to do ahead of time. Most attendees should budget at least 2 hours for this and try to do it at least 5-10 days before the event. The facilitators will be best able to help walk you through any issues you encounter if they aren’t last-minute requests. Send any questions or requests for help to @bryanhickerson and @paulcwatts  on the [Ember.js Seattle Community Slack](http://emberjs-seattle.herokuapp.com/)

- Install the latest [stable ember-cli](https://github.com/ember-cli/ember-cli/releases) `npm uninstall -g ember-cli &&
npm install -g ember-cli`
- Fork, clone, npm install, and test run projects you are interested in. This is essential to do ahead of time. While we hope and pray for the quality internetz, most wifi can’t handle 50 devs cloning and npm installing all at the same time.
- Browse open issues to form some goals for yourself. See list of repositories and some helpful links below. You can work on anything during the workshop. The list just contains suggestions. Look for
issues like "help wanted" or "good first issue" to guide your search.
- Have node, git, and npm installed, and have a GitHub account connected in git. If you need help with these steps, contact the facilitators.
- If you want to work on the https://emberjs.com [website](https://github.com/emberjs/website) or [The Guides](https://github.com/emberjs/guides), budget some extra time to install Docker or Ruby.
- If you are not familiar with Open Source workflows (forking, cloning, opening PRs), try it out in [this practice repository](https://github.com/jenweber/our-open-source-contributions), while following [this article of step-by-step instructions](https://medium.com/@jenweber/your-first-open-source-contribution-a-step-by-step-technical-guide-d3aca55cc5a6).

## Core libraries to browse for issues

You are invited to work on issues in any open source project related to Ember, both official and
community projects. However, here are some repositories to get you started:

- [ember.js](https://github.com/emberjs/ember.js) - our favorite framework. Includes both technical and documentation issues
- [data](https://github.com/emberjs/data) - home of ember-data
- [ember.js website](https://github.com/emberjs/website) - public website at www.emberjs.com *
- [The Guides](https://github.com/emberjs/guides) - public website at https://guides.emberjs.com/ *
- [ember-api-docs](https://github.com/ember-learn/ember-api-docs) - the app that displays the documentation found in ember.js core code
- [deprecation-app](https://github.com/ember-learn/deprecation-app) - an app that gives Ember's users
information about how to overcome deprecations.
- [builds](https://github.com/ember-learn/builds) - the [builds and releases](https://emberjs.com/builds/release/) section of the website
- [ember-cli](https://github.com/ember-cli/ember-cli) - home of the best command line tool for a front end framework
- [ember-cli website and docs](https://github.com/ember-cli/ember-cli.github.io) - help other people use the best cli *
- [statusboard](https://github.com/ember-learn/statusboard) - shows the status of ongoing Ember ecosystem projects at https://emberjs.com/statusboard/
- [guides-app](https://github.com/ember-learn/guides-app) - the WIP app that will eventually replace
the current Ruby-based guides application
- [ember-styleguide](https://github.com/ember-learn/ember-styleguide) - a WIP component library to be
used in Ember's family of webssites
- [ember-inspector](https://github.com/emberjs/ember-inspector) - the browser extension dev tools for Ember

* optional, but recommended to install Docker to run these locally

## Addons and community projects to browse for issues

Maintainers of these addons have specially volunteered to curate some issues and guide new contributors.

- [ember-changeset](https://github.com/poteto/ember-changeset) - checks new objects for validity (nucleartide)
- [ember-changeset-validations](https://github.com/poteto/ember-changeset-validations) - a library to validate user form entries (nucleartide)
- [qunit-dom](https://github.com/simplabs/qunit-dom) - DOM assertions for testing (Tobias Bieniek)
- [ember-cli-code-coverage](https://github.com/kategengler/ember-cli-code-coverage) - see how good your test suite is (Robert Wagner)
- [html-next](https://github.com/html-next) - a collection of addons focused on performance and rendering (Robert Wagner)

## Help Wanted and Good First Contribution Issues
We’ve asked the maintainers of many ember projects to use the “good first issue” label to show which issues they’d like help on during the workshop. Again, you are welcome to choose any issue/project, but if you need ideas, click here to browse all of them! You might also want to search for “help wanted” issues.

If you want to choose one ahead of the workshop, you can add a comment that says you’d like to work on it.

[Help Wanted Issues](https://github.com/search?utf8=%E2%9C%93&q=repo%3Aemberjs%2Fember.js+repo%3Aemberjs%2Fdata+repo%3Aemberjs%2Fwebsite+repo%3Aemberjs%2Fguies+repo%3Aember-learn%2Fguides-app+repo%3Aember-learn%2Fguides-source+repo%3Aember-learn%2Fember-jsonapi-docs+repo%3Aember-learn%2Fdeprecations-app+repo%3Asimplabs%2Fqunit-dom+repo%3Aember-learn%2Fstatusboard+repo%3Apoteto%2Fember-changeset-validations+repo%3Apoteto%2Fember-changeset+label%3A%22help+wanted%22&type=Issues&ref=advsearch&l=&l=)

[Good First Issues](https://github.com/search?utf8=%E2%9C%93&q=repo%3Aemberjs%2Fember.js+repo%3Aemberjs%2Fdata+repo%3Aemberjs%2Fwebsite+repo%3Aemberjs%2Fguies+repo%3Aember-learn%2Fguides-app+repo%3Aember-learn%2Fguides-source+repo%3Aember-learn%2Fember-jsonapi-docs+repo%3Aember-learn%2Fdeprecations-app+repo%3Asimplabs%2Fqunit-dom+repo%3Aember-learn%2Fstatusboard+repo%3Apoteto%2Fember-changeset-validations+repo%3Apoteto%2Fember-changeset+label%3A%22good+first+issue%22&type=Issues&ref=advsearch&l=&l=)

[Everything](https://github.com/search?utf8=%E2%9C%93&q=repo%3Aemberjs%2Fember.js+repo%3Aemberjs%2Fdata+repo%3Aemberjs%2Fwebsite+repo%3Aemberjs%2Fguies+repo%3Aember-learn%2Fguides-app+repo%3Aember-learn%2Fguides-source+repo%3Aember-learn%2Fember-jsonapi-docs+repo%3Aember-learn%2Fdeprecations-app+repo%3Asimplabs%2Fqunit-dom+repo%3Aember-learn%2Fstatusboard+repo%3Apoteto%2Fember-changeset-validations+repo%3Apoteto%2Fember-changeset&type=Issues&ref=advsearch&l=&l=)
