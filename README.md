# Frontend search

> Start your searches easily via CLI

## This repository was merged on Oh-My-Zsh project

## Why activate this repository again?

Unfortunately, On-My-Zsh repository is not being updated regularly. So that I'm activating this repository again until some changes comes to the master.

This solution is totally temporary and I'll create Pull Requests for all features, fixes or changes done in this repository.

## Rationale

The idea for this script is to help searches in important doc contents from frontend.

## Instalation

I will send a Pull Request with this plugin for .oh-my-zsh official repository. If accept them, it's only add in plugins list that exists in `.zshrc` file.

For now, you can clone this repository and add in `custom/plugins` folder

```bash
$ git clone git://github.com/willmendesneto/frontend-search.git ~/.oh-my-zsh/custom/plugins/frontend-search
```

After this, restart your terminal and frontend-search plugin is configurated in you CLI.

```bash
...
plugins=( <your-plugins-list>... frontend-search)
...
```

## Usage

You can use the frontend-search plugin in these two forms:

- `frontend <context> <term> [more terms if you want]`
- `<context> <term> [more terms if you want]`

For example, these two are equivalent:

```zsh
$ frontend angularjs dependency injection
$ angularjs dependency injection
```

Available search contexts are:

| context       | URL                                                                         |
| ------------- | --------------------------------------------------------------------------- |
| angular       | `https://angular.io/docs/ts/latest/api/#!?query=`                           |
| angularjs     | `https://google.com/search?as_sitesearch=angularjs.org&as_q=`               |
| bem           | `https://google.com/search?as_sitesearch=bem.info&as_q=`                    |
| bootsnipp     | `http://bootsnipp.com/search?q=`                                            |
| caniuse       | `http://caniuse.com/#search=`                                               |
| codepen       | `http://codepen.io/search?q=`                                               |
| compassdoc    | `http://compass-style.org/search?q=`                                        |
| cssflow       | `http://www.cssflow.com/search?q=`                                          |
| dartlang      | `https://api.dartlang.org/apidocs/channels/stable/dartdoc-viewer/dart:`     |
| emberjs       | `http://emberjs.com/api/#stp=1&stq=`                                        |
| fontello      | `http://fontello.com/#search=`                                              |
| flowtype      | `https://google.com/search?as_sitesearch=flow.org/en/docs/&as_q=`           |
| typescript    | `https://google.com/search?as_sitesearch=www.typescriptlang.org/docs&as_q=` |
| github        | `https://github.com/search?q=`                                              |
| html5please   | `http://html5please.com/#`                                                  |
| jquery        | `https://api.jquery.com/?s=`                                                |
| lodash        | `https://devdocs.io/lodash/index#`                                          |
| mdn           | `https://developer.mozilla.org/search?q=`                                   |
| nodejs        | `https://www.google.com/search?as_sitesearch=nodejs.org/en/docs/&as_q=`     |
| npmjs         | `https://www.npmjs.com/search?q=`                                           |
| qunit         | `https://api.qunitjs.com/?s=`                                               |
| reactjs       | `https://google.com/search?as_sitesearch=facebook.github.io/react&as_q=`    |
| smacss        | `https://google.com/search?as_sitesearch=smacss.com&as_q=`                  |
| stackoverflow | `http://stackoverflow.com/search?q=`                                        |
| unheap        | `http://www.unheap.com/?s=`                                                 |
| bundlephobia  | `https://bundlephobia.com/result?p=`                                        |
| vuejs         | `https://www.google.com/search?as_sitesearch=vuejs.org&as_q=`               |

## New Features

New features are coming soon. If you want to have another context, open an Issue and tell us!

## Author

**Wilson Mendes (willmendesneto)**

- <https://plus.google.com/+WilsonMendes>
- <https://twitter.com/willmendesneto>
- <http://github.com/willmendesneto>
