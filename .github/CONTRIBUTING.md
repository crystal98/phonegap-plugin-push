# Contributing

We love pull requests from everyone.

[Fork](https://help.github.com/articles/fork-a-repo/), then [clone](https://help.github.com/articles/cloning-a-repository/) the repo:

```
git clone git@github.com:your-username/phonegap-plugin-push.git
```

Set up a branch for your feature or bugfix with a link to the original repo:

```
git checkout -b my-awesome-new-feature
git push --set-upstream origin my-awesome-new-feature
git remote add upstream https://github.com/phonegap/phonegap-plugin-push.git
```

Set up the project:

```
npm install
```

Make sure the tests pass before changing anything:

```
npm test
```

Make your change. Add tests for your change. Make the tests pass:

```
npm test
```

Commit changes:

```
git commit -m "Cool stuff"
```

Consider starting the commit message with an applicable emoji:
* :art: `:art:` when improving the format/structure of the code
* :zap: `:zap:` when improving performance
* :non-potable_water: `:non-potable_water:` when plugging memory leaks
* :memo: `:memo:` when writing docs
* :ambulance: `:ambulance:` a critical hotfix.
* :sparkles: `:sparkles:` when introducing new features
* :bookmark: `:bookmark:` when releasing / version tags
* :rocket: `:rocket:` when deploying stuff
* :penguin: `:penguin:` when fixing something on Android
* :apple: `:apple:` when fixing something on iOS
* :checkered_flag: `:checkered_flag:` when fixing something on Windows
* :bug: `:bug:` when fixing a bug
* :fire: `:fire:` when removing code or files
* :green_heart: `:green_heart:` when fixing the CI build
* :white_check_mark: `:white_check_mark:` when adding tests
* :lock: `:lock:` when dealing with security
* :arrow_up: `:arrow_up:` when upgrading dependencies
* :arrow_down: `:arrow_down:` when downgrading dependencies
* :shirt: `:shirt:` when removing linter warnings
* :hammer: `:hammer:` when doing heavy refactoring
* :heavy_minus_sign: `:heavy_minus_sign:` when removing a dependency.
* :heavy_plus_sign: `:heavy_plus_sign:` when adding a dependency.
* :wrench: `:wrench:` when changing configuration files.
* :globe_with_meridians: `:globe_with_meridians:` when dealing with internationalization and localization.
* :pencil2: `:pencil2:` when fixing typos.
* :hankey: `:hankey:` when writing bad code that needs to be improved.
* :package: `:package:` when updating compiled files or packages.

Make sure your branch is up to date with the original repo:

```
git fetch upstream
git merge upstream/master
```

Review your changes and any possible conflicts and push to your fork:

```
git push origin
```

[Submit a pull request](https://help.github.com/articles/creating-a-pull-request/).

At this point you're waiting on us. We do our best to keep on top of all the pull requests. We may suggest some changes, improvements or alternatives.

Some things that will increase the chance that your pull request is accepted:

- Write tests.
- Write a [good commit message](http://chris.beams.io/posts/git-commit/).
- Make sure the PR merges cleanly with the latest master.
- Describe your feature/bugfix and why it's needed/important in the pull request description.


## Editor Config

The project uses [.editorconfig](http://editorconfig.org/) to define the coding
style of each file. We recommend that you install the Editor Config extension
for your preferred IDE. Consistency is key.

## ESLint

The project uses [.eslint](http://eslint.org/) to define the JavaScript
coding conventions. Most editors now have a ESLint add-on to provide on-save
or on-edit linting.

## Issue labels

Selecting accurate label(s) communicates vital information about an issue.

### Labels by `Type` defined

> #### :information_source: `Type` labels and Git commit conventions
> This project enforces _[AngularJS Git Commit Guidelines][git-commit-guidelines-url]_ with [`commitplease`][commitplease-url] pre-commit hooks. This not only encourages succinct change logs, but also enables automated release management with [`semantic-release`][semantic-release-url].

#### 🏷️  `Type: Build`

Issues related to product builds. The AngularJS Git commit message format is

```

build(<scope>): <subject>
<BLANK LINE>
<[body]>
<BLANK LINE>
<footer>
```

#### 🏷️  `Type: Chore`

Issues related to miscellaneous non-functional changes (usually "maintenance" changes). The AngularJS Git commit message format is

```

chore(<scope>): <subject>
<BLANK LINE>
<[body]>
<BLANK LINE>
<footer>
```

#### 🏷️  `Type: CI`

Issues related to continuous integration, delivery, and deployment tasks. The AngularJS Git commit message format is

```

ci(<scope>): <subject>
<BLANK LINE>
<[body]>
<BLANK LINE>
<footer>
```

#### 🏷️  `Type: Docs`

Issues related to continuous integration, delivery, and deployment tasks. The AngularJS Git commit message format is

```

ci(<scope>): <subject>
<BLANK LINE>
<[body]>
<BLANK LINE>
<footer>
```

#### 🏷️  `Type: Feature`

New feature or enhancement requests. The AngularJS Git commit message format is

```

feat(<scope>): <subject>
<BLANK LINE>
<[body]>
<BLANK LINE>
<footer>
```

#### 🏷️  `Type: Fix`

Defect (bug) repair issues. The AngularJS Git commit message format is

```

fix(<scope>): <subject>
<BLANK LINE>
<[body]>
<BLANK LINE>
<footer>
```

#### 🏷️  `Type: Performance`

Performance improvement issues. The AngularJS Git commit message format is

```

perf(<scope>): <subject>
<BLANK LINE>
<[body]>
<BLANK LINE>
<footer>
```

#### 🏷️  `Type: Refactor`

Source code design **improvements that do not affect product behavior**. The AngularJS Git commit message format is

```

refactor(<scope>): <subject>
<BLANK LINE>
<[body]>
<BLANK LINE>
<footer>
```

#### 🏷️  `Type: Revert`

Tasks that revert to a previous commit hash. The AngularJS Git commit message format is

```

revert(<scope>): <subject>
<BLANK LINE>
<[body]>
<BLANK LINE>
<footer>
```

#### 🏷️  `Type: Style`

Issues related to style guideline compliance, especially `ESLint` errors and warnings. The AngularJS Git commit message format is

```

style(<scope>): <subject>
<BLANK LINE>
<[body]>
<BLANK LINE>
<footer>
```

#### 🏷️  `Type: Test`

Test coverage tasks. The AngularJS Git commit message format is

```

test(<scope>): <subject>
<BLANK LINE>
<[body]>
<BLANK LINE>
<footer>
```

[commitplease-url]: https://www.npmjs.com/package/commitplease
[git-commit-guidelines-url]: https://github.com/angular/angular.js/blob/master/CONTRIBUTING.md#commit
[label-status-available-url]: ../labels/Status%3A%20Available
[new-issue-url]: ../issues/new
[open-issues-url]: ../issues
[pr-url]: ../pulls
[semantic-release-url]: https://github.com/semantic-release/semantic-release
