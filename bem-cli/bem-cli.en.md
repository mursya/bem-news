#bem-cli: launch bem-tools locally

Mikhail Davydov wrote a tool called [bem-cli](https://github.com/bem/bem-cli) that launches locally installed [bem-tools](http://bem.info/tools/bem/).

Sometimes BEM-projects have different versions of bem-tools, and you can not simply run %%npm i -g bem%% 
to install bem-tools globally. Also there may be other reasons such as lack of root privileges.

We are also recommend you ((http://bem.info/tools/bem/installation/ to install bem-tools locally)) by %%npm i bem%% 
to prevent conflicts with other BEM-projects.

Locally installed bem is inconvenient to use. You have to run bem from project root, typing full path to bin/bem 
script %%./node_modules/.bin/bem make%%. You may also create a symbolic link %%ln -s ./node_modules/.bin/bem%% and 
run like this %%./bem%% or add path to your local %%./node_modules/.bin%% directory to environment variable %%PATH%%. 
There are many ways to do that, for example, ((http://bem.info/articles/smartcd/ smartcd)).

Inspired by ((http://gruntjs.com/ Grunt.js)) project, Mikhail created bem-cli - 
((https://github.com/bem/bem-cli/blob/master/bin/bem tool)), which finds local or global bem-tools and runs it, 
if it were installed globally.

Install bem-cli globally  %%npm i -g bem-cli%%, and you will have access to %%bem%% command anywhere on your system.

GitHub repository - https://github.com/bem/bem-cli
Issues - https://github.com/bem/bem-cli/issues

Mikhail Davydov is a JavaScript and Node.js developer. Now he is working on front-end part of Yandex.Taxi, 
mobile web-applications and promo-projects. He also writes and translates articles on JavaScript for major 
Russian web-community ((http://habrahabr.ru/ Habrahabr)) under ((http://habrahabr.ru/users/azproduction/ azproduction)) 
nick-name.

[Twitter](https://twitter.com/azproduction), [GitHub](http://github.com/azproduction).
