# emberjs-contributors-workshop
Materials and resources for the Contributors Workshop on March 10th, 2018 at EmberConf

## Quick links
- [Ember.js Community Slack](https://ember-community-slackin.herokuapp.com/) - your facilitators are @locks and @jenweber. The workshop channel is called #conf-workshop.
- [Pre-workshop survey](https://tilde.wufoo.com/forms/p12e9bep09a1yoa/)
- [Post-workshop feedback form](https://tilde.wufoo.com/forms/png9ogu0w645f2/)
- [Conference schedule](https://emberconf.com/schedule.html#contributors-workshop)

## Pre-Work for EmberConf Contributor's Workshop

Hi! Thanks for participating in the EmberConf Contributor’s Workshop! 

We only have 3 hours for the event, so help make the most of your time, there are some things you need to do ahead of time. Most attendees should budget at least 2 hours for this and try to do it at least 5-10 days before the event. The facilitators will be best able to help walk you through any issues you encounter if they aren’t last-minute requests. Send any questions or requests for help to @locks and @jenweber on the [Ember.js Community Slack](https://ember-community-slackin.herokuapp.com/)

- Install the latest [stable ember-cli](https://github.com/ember-cli/ember-cli/releases) `npm uninstall -g ember-cli &&
npm install -g ember-cli`
- Fork, clone, npm install, and test run projects you are interested in. This is essential to do ahead of time. While we hope and pray for the quality internetz, most wifi can’t handle 50 devs cloning and npm installing all at the same time.
- Browse open issues to form some goals for yourself. See list of repositories and some helpful links below. You can work on anything during the workshop. The list just contains suggestions.
- Have node, git, and npm installed, and have a GitHub account connected in git. If you need help with these steps, contact the facilitators. LINK TO VIDEO/MORE RESOURCES.
- If you want to work on the https://emberjs.com website or The Guides, install Docker
- If you are not familiar with Open Source workflows (forking, cloning, opening PRs), try it out in [this practice repository](https://github.com/jenweber/our-open-source-contributions), while following [this article of step-by-step instructions](https://medium.com/@jenweber/your-first-open-source-contribution-a-step-by-step-technical-guide-d3aca55cc5a6).

## Core libraries to browse for issues
- [ember.js](https://github.com/emberjs/ember.js) - our favorite framework. Includes both technical and documentation issues
- [data](https://github.com/emberjs/data) - home of ember-data
- [ember.js website](https://github.com/emberjs/website) - public website at www.emberjs.com *
- [guides-app](https://github.com/ember-learn/guides-app) - the app that powers https://guides.emberjs.com *
- [guides-source](https://github.com/ember-learn/guides-source) - the written content that is used in guides-app. Easy to edit, written in markdown.
- [ember-api-docs](https://github.com/ember-learn/ember-api-docs) - the app that displays the documentation found in ember.js core code
- [statusboard](https://github.com/ember-learn/statusboard) - a WIP app that will show the status of ongoing Ember ecosystem projects
- [deprecation-app](https://github.com/ember-learn/deprecation-app) - a WIP app that transforms the non-Ember deprecation content from website  into an Ember app instead
- [ember-cli](https://github.com/ember-cli/ember-cli) - home of the best command line tool for a front end framework
- [ember-cli website and docs](https://github.com/ember-cli/ember-cli.github.io) - help other people use the best cli *

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

If you want to choose one ahead of the workshop, be sure to add a comment that says you’d like to work on it.

[Magic search](https://github.com/search?utf8=%E2%9C%93&q=repo%3Aemberjs%2Fember.js+repo%3Aemberjs%2Fdata+repo%3Aemberjs%2Fwebsite+repo%3Aember-learn%2Fguides-app+repo%3Aember-learn%2Fguides-source+repo%3Aember-learn%2Fember-jsonapi-docs+repo%3Aember-learn%2Fdeprecations-app+repo%3Asimplabs%2Fqunit-dom+repo%3Aember-learn%2Fstatusboard+repo%3Apoteto%2Fember-changeset-validations+repo%3Apoteto%2Fember-changeset+label%3A%22good+first+issue%22&type=Repositories&ref=advsearch&l=&l=)
