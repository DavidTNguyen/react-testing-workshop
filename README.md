# React Testing Workshop

👋 This is a workshop repo to teach you about increasing your deploy confidence by using Jest
and React Testing Library to test your react components.

[![Build Status][build-badge]][build]
[![AppVeyor Build Status][win-build-badge]][win-build]
[![Code Coverage][coverage-badge]][coverage]
[![GPL 3.0 License][license-badge]][license]
[![All Contributors](https://img.shields.io/badge/all_contributors-8-orange.svg?style=flat-square)](#contributors)
[![PRs Welcome][prs-badge]][prs] [![Code of Conduct][coc-badge]][coc]

## System Requirements

- [git][git] v2 or greater
- [NodeJS][node] v8 or greater
- [yarn][yarn] v1 or greater (or [npm][npm] v6 or greater)

All of these must be available in your `PATH`. To verify things are set up
properly, you can run this:

```shell
git --version
node --version
yarn --version # or npm --version
```

If you have trouble with any of these, learn more about the PATH environment
variable and how to fix it here for [windows][win-path] or
[mac/linux][mac-path].

## Setup

After you've made sure to have the correct things (and versions) installed, you
should be able to just run a few commands to get set up:

```
git clone https://github.com/davidtnguyen/react-testing-workshop.git
cd react-testing-workshop
npm run setup --silent
```


This may take a few minutes. **It will ask you for your email.** This is
optional and just automatically adds your email to the links in the project to
make filling out some forms easier If you get any errors, please read through
them and see if you can find out what the problem is. You may also want to look
at [Troubleshooting](#troubleshooting). If you can't work it out on your own
then please [file an issue][issue] and provide _all_ the output from the
commands you ran (even if it's a lot).

## Running the app

To get the app up and running (and really see if it worked), run:

```shell
npm start
```

This should start up your browser. If you're familiar, this is a standard
[react-scripts](https://github.com/facebook/create-react-app) application.

You can also open
[the deployment of the app on Netlify](https://react-testing-workshop.netlify.com/).

At the top of each file in the `components` directory is a link to the URL you
can visit to open the component in the browser.

## Running the tests

```shell
npm test
```

This will start [Jest](http://facebook.github.io/jest) in watch mode. Read the
output and play around with it.

**Your goal will be to go into each test in the `exercises` directory and follow
the instructions to test the component**

## Helpful Emoji 🐨 💰 💯 🦉 📜

Each exercise has comments in it to help you get through the exercise. **Kody
the Koala Bear**, **Marty the Money Bag**, **Hannah the Hundred**, **Olivia the
Owl**, and **Dominic the Document** are here to help you.

- **Kody** 🐨 will tell you when there's something specific you should do
- **Marty** 💰 will give you specific tips (and sometimes code) along the way
- **Hannah** 💯 will give you extra challenges you can do if you finish the
  exercises early.
- **Olivia** 🦉 will give you useful tidbits/best practice notes.
- **Dominic** 📜 will give you links to useful documentation

## Troubleshooting

<details>

<summary>"npm run setup" command not working</summary>

Here's what the setup script does. If it fails, try doing each of these things
individually yourself:

```
# verify your environment will work with the project
node ./scripts/verify

# install dependencies
npm install

# verify the project is ready to run
npm run lint
npm run test:coverage
npm run build
```

If any of those scripts fail, please try to work out what went wrong by the
error message you get. If you still can't work it out, feel free to [open an
issue][issue] with _all_ the output from that script. I will try to help if I
can.

</details>

## Contributors

Thanks goes to these wonderful people
([emoji key](https://github.com/kentcdodds/all-contributors#emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore -->
| [<img src="https://avatars.githubusercontent.com/u/1500684?v=3" width="100px;"/><br /><sub><b>Kent C. Dodds</b></sub>](https://kentcdodds.com)<br />[💻](https://github.com/kentcdodds/react-testing-workshop/commits?author=kentcdodds "Code") [📖](https://github.com/kentcdodds/react-testing-workshop/commits?author=kentcdodds "Documentation") [🚇](#infra-kentcdodds "Infrastructure (Hosting, Build-Tools, etc)") [⚠️](https://github.com/kentcdodds/react-testing-workshop/commits?author=kentcdodds "Tests") | [<img src="https://avatars0.githubusercontent.com/u/1250430?v=4" width="100px;"/><br /><sub><b>FWeinb</b></sub>](https://github.com/FWeinb)<br />[🐛](https://github.com/kentcdodds/react-testing-workshop/issues?q=author%3AFWeinb "Bug reports") [🤔](#ideas-FWeinb "Ideas, Planning, & Feedback") | [<img src="https://avatars2.githubusercontent.com/u/1383720?v=4" width="100px;"/><br /><sub><b>David Lannoye</b></sub>](https://github.com/dlannoye)<br />[🐛](https://github.com/kentcdodds/react-testing-workshop/issues?q=author%3Adlannoye "Bug reports") [📖](https://github.com/kentcdodds/react-testing-workshop/commits?author=dlannoye "Documentation") | [<img src="https://avatars2.githubusercontent.com/u/9815009?s=460&v=4" width="100px;"/><br /><sub><b>Colin Cummings</b></sub>](https://github.com/colinrcummings)<br />[💻](https://github.com/kentcdodds/react-testing-workshop/commits?author=colinrcummings "Code") [⚠️](https://github.com/kentcdodds/react-testing-workshop/commits?author=colinrcummings "Tests") | [<img src="https://avatars2.githubusercontent.com/u/464764?v=4" width="100px;"/><br /><sub><b>Benji Koltai</b></sub>](https://github.com/bkoltai)<br />[📖](https://github.com/kentcdodds/react-testing-workshop/commits?author=bkoltai "Documentation") | [<img src="https://avatars1.githubusercontent.com/u/1779959?v=4" width="100px;"/><br /><sub><b>Sumit Bagga</b></sub>](http://baggasumit.github.io)<br />[📖](https://github.com/kentcdodds/react-testing-workshop/commits?author=baggasumit "Documentation") | [<img src="https://avatars0.githubusercontent.com/u/2027010?v=4" width="100px;"/><br /><sub><b>Yury Tarabanko</b></sub>](https://github.com/Tarabyte)<br />[💻](https://github.com/kentcdodds/react-testing-workshop/commits?author=Tarabyte "Code") |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [<img src="https://avatars2.githubusercontent.com/u/5779538?v=4" width="100px;"/><br /><sub><b>Alex Wendte</b></sub>](http://www.wendtedesigns.com/)<br />[💻](https://github.com/kentcdodds/react-testing-workshop/commits?author=themostcolm "Code") |

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the
[all-contributors](https://github.com/kentcdodds/all-contributors)
specification. Contributions of any kind welcome!

## License

This material is available for private, non-commercial use under the
[GPL version 3](http://www.gnu.org/licenses/gpl-3.0-standalone.html). If you
would like to use this material to conduct your own workshop, please contact me
at kent@doddsfamily.us

[npm]: https://www.npmjs.com/
[node]: https://nodejs.org
[git]: https://git-scm.com/
[build-badge]:
  https://img.shields.io/travis/kentcdodds/react-testing-workshop.svg?style=flat-square&logo=travis
[build]: https://travis-ci.org/kentcdodds/react-testing-workshop
[license-badge]:
  https://img.shields.io/badge/license-GPL%203.0%20License-blue.svg?style=flat-square
[license]:
  https://github.com/kentcdodds/react-testing-workshop/blob/master/README.md#license
[prs-badge]:
  https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square
[prs]: http://makeapullrequest.com
[donate-badge]:
  https://img.shields.io/badge/$-support-green.svg?style=flat-square
[donate]: http://kcd.im/donate
[coc-badge]:
  https://img.shields.io/badge/code%20of-conduct-ff69b4.svg?style=flat-square
[coc]:
  https://github.com/kentcdodds/react-testing-workshop/blob/master/CODE_OF_CONDUCT.md
[github-watch-badge]:
  https://img.shields.io/github/watchers/kentcdodds/react-testing-workshop.svg?style=social
[github-watch]: https://github.com/kentcdodds/react-testing-workshop/watchers
[github-star-badge]:
  https://img.shields.io/github/stars/kentcdodds/react-testing-workshop.svg?style=social
[github-star]: https://github.com/kentcdodds/react-testing-workshop/stargazers
[twitter]:
  https://twitter.com/intent/tweet?text=Check%20out%20react-testing-workshop%20by%20@kentcdodds%20https://github.com/kentcdodds/react-testing-workshop%20%F0%9F%91%8D
[twitter-badge]:
  https://img.shields.io/twitter/url/https/github.com/kentcdodds/react-testing-workshop.svg?style=social
[emojis]: https://github.com/kentcdodds/all-contributors#emoji-key
[all-contributors]: https://github.com/kentcdodds/all-contributors
[win-path]:
  https://www.howtogeek.com/118594/how-to-edit-your-system-path-for-easy-command-line-access/
[mac-path]: http://stackoverflow.com/a/24322978/971592
[issue]: https://github.com/kentcdodds/react-testing-workshop/issues/new
[win-build-badge]:
  https://img.shields.io/appveyor/ci/kentcdodds/react-testing-workshop.svg?style=flat-square&logo=appveyor
[win-build]: https://ci.appveyor.com/project/kentcdodds/react-testing-workshop
[coverage-badge]:
  https://img.shields.io/codecov/c/github/kentcdodds/react-testing-workshop.svg?style=flat-square
[coverage]: https://codecov.io/github/kentcdodds/react-testing-workshop
[watchman]: https://facebook.github.io/watchman/docs/install.html
