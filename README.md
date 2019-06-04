# Today I Learned 
(read it later..)
## 04 Jun 2019
* [git change commit message after push](https://stackoverflow.com/questions/8981194/changing-git-commit-message-after-push-given-that-no-one-pulled-from-remote)
* [delete tag](https://stackoverflow.com/questions/5480258/how-to-delete-a-remote-tag)
* [remove-files-from-git-adding/updating-gitignore](https://eric.blog/2014/05/11/remove-files-from-git-addingupdating-gitignore/)
* [git tag basics](https://git-scm.com/book/en/v2/Git-Basics-Tagging)
## 02 Jun 2019
* [mysql ubuntu 18.04](https://vitux.com/how-to-install-and-configure-mysql-in-ubuntu-18-04-lts/)
* [mysql remove](https://askubuntu.com/questions/640899/how-do-i-uninstall-mysql-completely)
* ~~[mysql access-denied](https://stackoverflow.com/questions/41645309/mysql-error-access-denied-for-user-rootlocalhost)~~
* ~~[mysql reset pw](https://stackoverflow.com/questions/41984956/cant-reset-root-password-with-skip-grant-tables-on-ubuntu-16/50360678)~~
## 29 May 2019
* [set default editor](https://unix.stackexchange.com/questions/73484/how-can-i-set-vi-as-my-default-editor-in-unix)
## 28 May 2019
* git: how to remove added file
```
// make .gitignore file.
// add node_modules/ line to gitignore file
// run this command 
git rm -r --cached .
git add .
git commit -m "remove gitignore files"
git push 
```

## 17 May 2019
* [react-dropdown-tree-select](https://dowjones.github.io/react-dropdown-tree-select/#/story/readme)
* [juse.js - search library](https://fusejs.io/)
## 12 May 2019
* [HTML data-* attributes](https://developer.mozilla.org/en-US/docs/Learn/HTML/Howto/Use_data_attributes)
## 10 May 2019
* [implement-html-entity-decode-in-react-js](https://stackoverflow.com/questions/42361689/implement-html-entity-decode-in-react-js)
* [rendering-raw-html-with-reactjs](https://stackoverflow.com/questions/27934238/rendering-raw-html-with-reactjs)
## 09 May 2019
* `Body.json()` is asynchronous and returns a Promise object that resolves to a JavaScript object. 
* `JSON.parse()` is synchronous can parse a string and change the resulting returned JavaScript object. 
  (turns a string of JSON text into a JavaScript object.)
* `JSON.stringify` turns a JavaScript object into JSON text and stores that JSON text in a string. 
  (create a JSON string out of an object/array)
## 08 May 2019
* [JS e.target](https://developer.mozilla.org/en-US/docs/Web/API/Event/target)
* [netlify](https://www.netlify.com/)
## 29 Apr 2019
* git push for quest
  ```
  git branch
  git checkout -b [new quest]

  git add .
  git commit -m "message"

  git remote -v
  git remote rm origin
  git remote add origin [new quest repo]
  // for gh-pages
  
  git push origin router:master
  git push  <REMOTENAME> <LOCALBRANCHNAME>:<REMOTEBRANCHNAME> 

  // change homepage address in package.json
  npm run deploy
  ```
* git change branch name
  ``` 
  git branch -m <newname>
  ```
## 26 Apr 2019
* [remove quote in json](https://stackoverflow.com/questions/9244824/how-to-remove-quot-from-my-json-in-javascript)
## 25 Apr 2019
* [remove scroll bar](https://medium.com/react-camp/how-to-fight-the-body-scroll-2b00267b37ac)
## 24 Apr 2019
* [for...in | javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for...in)
  ```javascript
  var string1 = "";
  var object1 = {a: 1, b: 2, c: 3};

  for (var property1 in object1) {
    string1 += object1[property1];
  }

  console.log(string1);
  // expected output: "123"
  ```

* callback is invoked with three arguments:
  ```
  the value of the element
  the index of the element
  the Array object being traversed
  ```
## 17 Apr 2019
* [axios](https://github.com/axios/axios)
## 15 Apr 2019
* [git cheat sheet](https://github.github.com/training-kit/downloads/github-git-cheat-sheet/)
  > `git reset` : undo `git add` before commit 
## 14 Apr 2019
* [styling and css - react](https://reactjs.org/docs/faq-styling.html)
* [super(props)](https://stackoverflow.com/questions/30571875/whats-the-difference-between-super-and-superprops-in-react-when-using-e)
* [constructor, super](https://stackoverflow.com/questions/40433463/what-does-calling-super-in-a-react-constructor-do/40440322)
* [react proptypes](https://reactjs.org/docs/typechecking-with-proptypes.html)
* [react default props](https://reactjs.org/docs/react-without-es6.html#declaring-default-props)
* [react state&lifecycle](https://reactjs.org/docs/state-and-lifecycle.html)
* [js this, bind](https://github.com/getify/You-Dont-Know-JS/blob/master/this%20%26%20object%20prototypes/ch2.md)
## 13 Apr 2019
* [clean code vs dirty code](https://americanexpress.io/clean-code-dirty-code/)
* [react patterns](https://reactpatterns.com/)
* [react.js cheatsheet](https://devhints.io/react)
## 12 Apr 2019
* [Youtube | React JS Tutorial](https://www.youtube.com/watch?v=UtIOMUQ7nWM)
* [ES6 katas](http://es6katas.org/)
## 11 Apr 2019
* [lodash](https://lodash.com/)
## 10 Apr 2019
* [vim 마우스 없이 코딩](https://www.youtube.com/watch?v=qn1soztN7k4&feature=youtu.be&fbclid=IwAR1tqUR3vd7Jq7HRVLM_QxCHUWkQq_LTIujawU_iyVWgyQatUoLNrFXWV6Q)
## 09 Apr 2019
* [Four ways to style react components](https://codeburst.io/4-four-ways-to-style-react-components-ac6f323da822)
## 08 Apr 2019
* [npm ERR! code ELIFECYCLE | Stack Overflow](https://stackoverflow.com/questions/42308879/npm-err-code-elifecycle)
* [JavaScript Accessors (Getters and Setters)](https://www.w3schools.com/js/js_object_accessors.asp)
* [Deploy React to GitHub-Pages](https://codeburst.io/deploy-react-to-github-pages-to-create-an-amazing-website-42d8b09cd4d)
* [react-devtools](https://github.com/facebook/react-devtools)
* [vscode enospc error](https://code.visualstudio.com/docs/setup/linux#_visual-studio-code-is-unable-to-watch-for-file-changes-in-this-large-workspace-error-enospc)
* [Watch mode on Linux causes a ENOSPC Node.js error ](https://github.com/facebook/jest/issues/3254)
  ```
  echo fs.inotify.max_user_watches=524288 | sudo tee -a /etc/sysctl.conf && sudo sysctl -p
  ```
* [markdown emoji](https://gist.github.com/rxaviers/7360908)
* [markdown cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
## 03 Apr 2019
* git process
  ```
  git branch -r   # check which branch you are in
  git checkout dev  # switch to dev branch
  git checkout -b feature_nav  # create new brance 'feature_nav' , if you are in dev branch, you will clone it to feature_nav
  ```
  ```
  git status
  git add .
  git commit -m ""
  ```
  ```
  git pull origin dev   # pull from dev branch
  git push origin feature_nav   # push to remote
  ```
* [git adding a remote](https://help.github.com/en/articles/adding-a-remote)
  ```
  $ git remote add origin[name] https://github.com/user/repo.git
  # Set a new remote

  $ git remote -v
  # Verify new remote
  > origin  https://github.com/user/repo.git (fetch)
  > origin  https://github.com/user/repo.git (push)
  ```
* [git fetch remote branch](https://stackoverflow.com/questions/9537392/git-fetch-remote-branch)
  ```
  git branch -r
  git fetch origin dev
  git merge origin/dev
  ```
## 02 Apr 2019
* [github.dev | Personal website generator](https://github.dev/)
* [bootstrap no-gutters](https://getbootstrap.com/docs/4.0/layout/grid/#no-gutters)
* [travis-ci](https://travis-ci.com)
* [learn git branch](https://learngitbranching.js.org/)
* [practice js in terminal](https://github.com/workshopper/javascripting)
* [BEM naming convention](http://getbem.com/naming/)
## 01 Apr 2019
* [nvm](https://github.com/creationix/nvm)
* [curl](https://github.com/curl/curl)
* [How To Install Node.js on Ubuntu 18.04](https://www.digitalocean.com/community/tutorials/how-to-install-node-js-on-ubuntu-18-04#removing-nodejs)
* [The difference between git pull, git fetch and git clone (and git rebase)](https://blog.mikepearce.net/2010/05/18/the-difference-between-git-pull-git-fetch-and-git-clone-and-git-rebase/)
* [clone a specific Git branch? [duplicate]](https://stackoverflow.com/questions/14998923/how-can-i-copy-the-content-of-a-branch-to-a-new-local-branch)
* [rescources to learn git](http://try.github.io/)
* [ssh]()
## 29 Mar 2019
* [css unit](https://www.w3schools.com/cssref/css_units.asp)
## 28 Mar 2019
* [Understanding the Viewport in the Mobile Web](https://www.alsacreations.com/article/lire/1490-comprendre-le-viewport-dans-le-web-mobile.htm)
## 27 Mar 2019
* [AT&T Archives: The UNIX Operating System](https://youtu.be/tc4ROCJYbm0?t=300)
## 26 Mar 2019
### GNU/LINUX
- operating system
  - roles
    manage CPU, RAM, Input/Output, execution of application, Rights, File, Information
  - components
    [kernel](https://en.wikipedia.org/wiki/Kernel_(operating_system)), [command interpreter](https://en.wikipedia.org/wiki/Shell_(computing)), file system
  - GNU,LINUX, UNIX
    - UNIX
      based on [shell](https://en.wikipedia.org/wiki/Shell_script)
    - GNU (GNU is not Unix)
      complete free operating system
      Free software License GPL (General Public License)
       `Freedom of execution : the right to launch the program.
        Freedom of modification :  the right to study the program and modify it (access to the source code).
        Freedom of redistribution : the right to broadcast the program, free or not.
        Freedom of improvement :  the right to redistribute a modified version of the program.`

    
## 25 Mar 2019
* [linux windows dual boot system](https://itsfoss.com/guide-install-linux-mint-16-dual-boot-windows/)
## 19 Mar 2019
* [gist](https://gist.github.com/)
* [HTML Sections](http://w3c.github.io/html/sections.html#the-h1,-h2,-h3,-h4,-h5,-and-h6-elements)
* [MDN | how css works](https://developer.mozilla.org/en-US/docs/Learn/CSS/Introduction_to_CSS/How_CSS_works)
## 18 Mar 2019
* [htmlreference.io](https://htmlreference.io/)
* [MDN | HTML5](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)
## 16 Mar 2019
* [Wireframes : Beginner guide](https://webdesign.tutsplus.com/articles/a-beginners-guide-to-wireframing--webdesign-7399)
## 14 Mar 2019
* [JS class constructor](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes/constructor)
## 13 Mar 2019
* [JS assert](https://www.w3schools.com/nodejs/met_assert.asp)
* [JS remove duplicates in array](https://stackoverflow.com/questions/1960473/get-all-unique-values-in-a-javascript-array-remove-duplicates)
* [JS indexOf](https://www.w3schools.com/jsref/jsref_indexof_array.asp)
* [JS this](https://www.youtube.com/watch?v=PAr92molMHU)
## 12 Mar 2019
* [JS try throw catch finally](https://codeburst.io/learn-how-to-handle-javascript-errors-with-try-throw-catch-finally-83b4f9ef8c6f)
* [JS error](https://www.w3schools.com/js/js_errors.asp)
* [JS throw](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/throw)
## 09 Mar 2019
* [JavaScript Tutor](http://pythontutor.com/javascript.html#mode=edit)
* [regexper](https://regexper.com/)
- `(\(.*?\))` any character
* [starts and ends with a|e|i|o|u](https://regexper.com/#%5Ea%28%5C%28.*%3F%5C%29%29a%24%7C%5Ee%28%5C%28.*%3F%5C%29%29e%24%7C%5Ei%28%5C%28.*%3F%5C%29%29i%24%7C%5Eo%28%5C%28.*%3F%5C%29%29o%24%7C%5Eu%28%5C%28.*%3F%5C%29%29u%24%7C%28%5C%28.*%3F%5C%29%29)
## 08 Mar 2019
* [Regular Expressions in JavaScript](https://www.hackerrank.com/challenges/js10-regexp-1/topics/javascript-regex)
* [웹 아키텍쳐 입문](https://blog.rhostem.com/posts/2018-07-22-web-architecture-101?fbclid=IwAR3KGe5KsP0ePYm_uihta_hE9g53EZ12X2vUyu5NCj06SV1VMehxndb71Qo)
## 07 Mar 2019
* [Bit - share components](https://bitsrc.io/)
* [Components Should Be Focused, Independent, Reusable, Small & Testable (FIRST)](https://addyosmani.com/first/)
* [DRY principle](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself)
* [codewars | String repeat (JavaScript)](https://www.codewars.com/kata/reviews/57f78c4be0da82645b00009c/groups/5c815f358e669d000178204b)
* [codewars | Vowel Count (JavaScript)](https://www.codewars.com/kata/reviews/54ff35d3c1bad9fbfb00021d/groups/5c80f039ecdbb900014f912d)
* [codewars | Categorize New Member (JavaScript)](https://www.codewars.com/kata/reviews/5506c16fa11c0a0eef0000a3/groups/5c80f5ff8e669d0001deb7af)
## 06 Mar 2019
* [agile vs devops](https://www.guru99.com/agile-vs-devops.html)
* [javascript Array Functions: reduce()](https://www.youtube.com/watch?v=-LFjnY1PEDA)
* [codewars | Replace With Alphabet Position (JavaScript)](https://www.codewars.com/kata/reviews/56002d1c656fe9438f00001b/groups/5c7fe22e3bf5c200018057df)
* [JavaScript RegExp [abc] Expression](https://www.w3schools.com/jsref/jsref_regexp_charset.asp)
## 04 Mar 2019
* [svg element](https://developer.mozilla.org/en-US/docs/Web/SVG/Element/svg)
## 02 Mar 2019
* [css z-index](https://www.w3schools.com/cssref/pr_pos_z-index.asp)
* [working with css pseudo-classes in js](https://zzz.buzz/2016/06/16/working-with-pseudo-classes-in-javascript/)
## 01 Mar 2019
* [w3c css2 Visual formatting model](https://www.w3.org/TR/CSS2/box.html#box-model)
* [w3c css2 Box model](https://www.w3.org/TR/CSS2/visuren.html)
## 28 Feb 2019
* [css 2018](https://www.w3.org/TR/css-2018/)
* [Specs Reading: CSS Snapshot 2018 (Overview)](https://gist.github.com/Ta2Rim/d1babcd51fd1c13f63cb8567e55b5b7f)
* [Introduction to CSS 2.1](https://www.w3.org/TR/CSS2/intro.html)
* [css animation](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Animations/Using_CSS_animations)
## 27 Feb 2019
* [css heart shape](https://css-tricks.com/books/volume-i/make-heart-shape/)
* [css pseudo elements](https://www.w3schools.com/css/css_pseudo_elements.asp)
* [css content property](https://www.w3schools.com/cssref/pr_gen_content.asp)
## 26 Feb 2019
### AWS summit berlin
* [amazon lex]()
* [amazon amplify]()
* [amazon personalize]()
* [amazon forecast]()
* [amazon sagemaker]()
* [amazon sumerian]()
* [aws robomaker]()
## 25 Feb 2019
* [DOM은 정확히 무슨뜻일까](https://wit.nts-corp.com/2019/02/14/5522)
* [javascript 비동기처리와 콜백함수](https://joshua1988.github.io/web-development/javascript/javascript-asynchronous-operation/)
* [ajax란 무엇인가](https://coding-factory.tistory.com/143)
## 23 Feb 2019
* [javascript single-threaded, non-blocking](https://nodejs.org/en/docs/guides/blocking-vs-non-blocking/)
* [eloquent javascript](https://eloquentjavascript.net/)
## 22 Feb 2019
* [codingheroes.io/resources](http://codingheroes.io/resources/)
* [css box-sizing:border-box](https://www.w3schools.com/css/css3_box-sizing.asp)
* [css clip-path](https://developer.mozilla.org/en-US/docs/Web/CSS/clip-path)
* [css clip-path clippy](https://bennettfeely.com/clippy/)
## 21 Feb 2019
* [BlaBoo React native 앱 개발기](https://dev-yakuza.github.io/ko/blaboo/development-journal/?utm_source=gaerae.com&utm_campaign=%EA%B0%9C%EB%B0%9C%EC%9E%90%EC%8A%A4%EB%9F%BD%EB%8B%A4&utm_medium=social&fbclid=IwAR33yjXnL2UjRS-2Iz9IgrOobvSM7TagbZC0GF_FqvaOk0MWvaSraitY6RE)
## 20 Feb 2019
### E-commerce Berlin Expo 2019
* [facebook creativeshop](https://m.facebook.com/business/a/creative-tools)
* [microservices](https://en.wikipedia.org/wiki/Microservices)
* [check my search](https://sooqrsearch.typeform.com/to/JCD9a5)
## 19 Feb 2019
* [javascript async/await](https://javascript.info/async-await)
* [javascript promise](https://javascript.info/promise-basics)
* [ajax fetch](https://en.wikipedia.org/wiki/Ajax_(programming)#fetch)
* [json parse&stringify](https://alligator.io/js/json-parse-stringify/)
* [http messages](https://www.w3schools.com/tags/ref_httpmessages.asp)
* [http://www.example.com/](http://www.example.com/)
## 15 Feb 2019
* [service-workers](https://developers.google.com/web/fundamentals/primers/service-workers/)
* [create-react-app](https://facebook.github.io/create-react-app/docs/getting-started)
* [tachyons](https://tachyons.io/)
* [mozilla | re-introduction_to_JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript/A_re-introduction_to_JavaScript)
## 12 Feb 2019
* [command line (windows/linux)](https://skimfeed.com/blog/windows-command-prompt-ls-equivalent-dir/)
* [javascript array sort() method](https://www.w3schools.com/js/js_array_sort.asp)
## 11 Feb 2019
* [You-Dont-Know-JS](https://github.com/getify/You-Dont-Know-JS)
* [javascript-the-core](http://dmitrysoshnikov.com/ecmascript/javascript-the-core-2nd-edition/)

* [javascript modules](https://hacks.mozilla.org/2018/03/es-modules-a-cartoon-deep-dive/)
* [javascript useful array and object methods](https://codeburst.io/useful-javascript-array-and-object-methods-6c7971d93230)
* [Javascript Object-explorer](https://sdras.github.io/object-explorer/)
* [JS instantiation](https://medium.com/dailyjs/instantiation-patterns-in-javascript-8fdcf69e8f9b)
* [JS context](http://ryanmorr.com/understanding-scope-and-context-in-javascript/)
* [JS data type - primitive and reference](http://www.javascripttutorial.net/javascript-primitive-vs-reference-values/)
* [자료구조 - heap 이란](https://gmlwjd9405.github.io/2018/05/10/data-structure-heap.html)
## 10 Feb 2019
* [functional purity](https://hackernoon.com/javascript-and-functional-programming-pt-3-pure-functions-d572bb52e21c)
## 07 Feb 2019
* [Javascript - Computing property names](https://www.deadcoderising.com/2017-06-20-es6-3-new-ways-of-defining-object-properties-in-javascript/)
* [MDN | Javascript - Closures](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Closures)
* [Closures in Javascript](https://www.youtube.com/watch?v=-xqJo5VRP4A)
## 31 Jan 2019
* [Javascript callback function](https://medium.freecodecamp.org/javascript-callbacks-explained-using-minions-da272f4d9bcd)
## 28 Jan 2019
* [git existing project](https://help.github.com/articles/adding-an-existing-project-to-github-using-the-command-line/)
## 27 Jan 2019
* [Event reference | MDN](https://developer.mozilla.org/en-US/docs/Web/Events)
* [javascript Char Codes](https://www.cambiaresearch.com/articles/15/javascript-char-codes-key-codes)
## 26 Jan 2019
# Resources for FREE Templates
* [cruip](https://cruip.com)
* [Creative Tim Templates](https://www.creative-tim.com/bootstrap-themes/ui-kit?direction=asc&sort=price)
* [Bootstrap Templates 0](https://mdbootstrap.com/freebies/)
* [Bootstrap Templates 1](http://www.mashup-template.com/templates.html)
* [Bootstrap Templates 2](https://startbootstrap.com/template-categories/all/)
* [Animate.css](https://daneden.github.io/animate.css/)
* [cssgridgarden](http://cssgridgarden.com/)
* [interfacer](https://interfacer.xyz/)
* [undraw](https://undraw.co/)
* [css media-queries](https://css-tricks.com/snippets/css/media-queries-for-standard-devices/)
## 25 Jan 2019
* [css-trick](https://css-tricks.com/almanac/)
* [css-trick: flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
* [flexbox-cheatsheet](https://darekkay.com/dev/flexbox-cheatsheet.html)
* [css transitions-and-transforms](https://robots.thoughtbot.com/transitions-and-transforms)
* [paletton.com](http://paletton.com/)
* [css specificity calculator](https://specificity.keegan.st/)
* [css-minify](https://www.cleancss.com/css-minify/)
## 24 Jan 2019
* [YouMightNotNeedjQuery](http://youmightnotneedjquery.com/)
* [w3layouts](https://w3layouts.com/)
* [free-css](https://www.free-css.com/free-css-templates)
## 01 Dec 2018
### Deep Dive UX/UI | 1-Day Workshop for Beginners
## 29 Nov 2018
### CryptoParty: Privacy for Beginners
## 22 Nov 2018 - 23 Nov 2018
### Data Natives Berlin 2018
## 20 Nov 2018 - 21 Nov 2018
### Codemotion Berlin 2018
## 15 Thu 2018
### Woman-In-Loop: AI Hackathon
## 14 Nov 2018
### WTMB : Javascript Crash Course Vol.2 @Eurostaff, Berlin
## 07 Nov 2018
### WTMB : Javascript Crash Course Vol.2 @Eurostaff, Berlin
## 31 Oct 2018
### WTMB : Javascript Crash Course Vol.2 @Eurostaff, Berlin
## 29 Oct 2018
### React Girls Berlin - GraphQL & Chatbot-like
## 25 Oct 2018
### CodePub goes Klarna! React Workshop
## 24 Oct 2018
### WTMB : Javascript Crash Course Vol.2 @Eurostaff, Berlin
## 23 Oct 2018
### Le wagon @Berlin: Intro to javascript
## 18 Oct 2018
### Data Science co-learning @co-up, Berlin
## 18 Aug 2018
* [quantum experience ibmQ](https://quantumexperience.ng.bluemix.net/qx/editor)
## 10 Jul 2018
### [AWS AI academy](http://hands-on-ai.surge.sh/) @Wework seoul square
  1. Python/Django & AWS AI API
  2. AWS ML Service
  3. Blockchanin & AI
  ## 9 Jul 2018
  * [bash reference manual](http://www.gnu.org/software/bash/manual/bash.html)
## 6 Jul 2018
* [Ipython](https://ipython.org/) - A better interactive Python interpreter
* [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/) - Used to parse HTML and extract information from it. Great for web scraping.
## 4 Jul 2018
* [Python : Floating Point Arithmetic: Issues and Limitations](https://docs.python.org/3/tutorial/floatingpoint.html)
* [PEP 8 -- Style Guide for Python Code](https://www.python.org/dev/peps/pep-0008/)
* [Python : Errors and Exceptions](https://docs.python.org/3/tutorial/errors.html)
* [Python : String Method](https://docs.python.org/3/library/stdtypes.html#string-methods)
## 22 Jun 2018
### Facebook Developer Circle: Seoul
Global Hackathon Community Challenge Build day
## 21 Jun 2018
### Udacity Bertelmann's DataScience Scholarship
KR study group meetup
## 14 Jun 2018
### Udacity Bertelmann's DataScience Scholarship
KR study group meetup
* [course summary note translation project](#)
## 6 Jun 2018
* [DeepLearningZeroToAll Youtube(kor)](https://www.youtube.com/playlist?list=PLlMkM4tgfjnLSOjrEJN31gZATbcj_MpUm)
* [http://hunkim.github.io/ml/ (kor)](http://hunkim.github.io/ml/)
* [DeepLearningZeroToAll (kor)](https://github.com/hunkim/DeepLearningZeroToAll)
* [http://holehouse.org/mlclass/](http://holehouse.org/mlclass/)
* [http://cs231n.github.io/](http://cs231n.github.io/)
* [Tensor Ranks, Shapes, Type (kor)](https://tensorflowkorea.gitbooks.io/tensorflow-kr/content/g3doc/resources/dims_types.html)
## 31 May 2018
* [CodeSandbox](https://codesandbox.io)
* [Now.sh](https://zeit.co/now)
* [CssGridGarden](https://cssgridgarden.com/)
* [warriorjs](https://warrior.js.org/)
* [code.org](https://code.org/student/university)
* [python chatbot(kor)](http://static.wooridle.net/lectures/chatbot/)
## 25 May 2018
* [CSSgrid](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout)
* [Grid by Example](https://gridbyexample.com/examples/)
* [Codesandbox](https://codesandbox.io/)
## 24 May 2018
* [basic concepts of Webpack(kor)](http://blog.jeonghwan.net/js/2017/05/15/webpack.html)
* [Webpack](https://webpack.js.org/concepts/)
* [package.json](https://docs.npmjs.com/files/package.json)
## 17 May 2018
* [Art of Clean Pull Request(kor)](http://blog.sonim1.com/224?utm_source=gaerae.com&utm_campaign=%EA%B0%9C%EB%B0%9C%EC%9E%90%EC%8A%A4%EB%9F%BD%EB%8B%A4&utm_medium=social)
## 16 May 2018
### D.talks - SEA: It's potential, challenges, and opportunities. lessons learned from [Snapcart](http://snapcart.global/blog) @Dcamp
## ~ 10 May 2018
* [Native Directory - 335 React Native libraries](https://www.native.directory)
* [django project](https://www.djangoproject.com)
* [Baekjoon online Judge](https://www.acmicpc.net)
* [a study plan to cure javascript fatigue (kor)](https://rhostem.github.io/posts/2016-12-19-A-Study-Plan-To-Cure-JavaScript-Fatigue)
* [android developer tax (kor)](https://semusa.gitbooks.io/android_developer_tax)
* [crypto zombies](https://cryptozombies.io/ko)
* [summer of code 2018](https://1millionwomentotech.com/summerofcode1)
## 3 May 2018
* [React: Presentational and Container Components](https://medium.com/@dan_abramov/smart-and-dumb-components-7ca2f9a7c7d0)
* [Ajax in React: Networking and Fetch](https://facebook.github.io/react-native/docs/network.html)
* [Introduction to ES6 Promises](http://jamesknelson.com/grokking-es6-promises-the-four-functions-you-need-to-avoid-callback-hell/)
* [Async Await vs Promises](https://hackernoon.com/6-reasons-why-javascripts-async-await-blows-promises-away-tutorial-c7ec10518dd9#.8dv1y7ilu)
* [Deploying a Create React App to Github pages](https://medium.freecodecamp.org/surge-vs-github-pages-deploying-a-create-react-app-project-c0ecbf317089)
## 2 May 2018
### css
* [Advanced Media Queries](https://github.com/at-import/breakpoint/wiki/advanced-media-queries)
* [Advanced CSS3 Animation Effects](https://www.sitepoint.com/advanced-css3-animations/)
* [CSS4 Rocks](http://css4.rocks/)
* [Use tomorrow’s CSS syntax, today](http://cssnext.io/)
### web app
* [Configuring Web Applications](https://developer.apple.com/library/content/documentation/AppleApplications/Reference/SafariWebContent/ConfiguringWebApplications/ConfiguringWebApplications.html)
* [Creating a Mobile Web Application with Meta Tags](https://speckyboy.com/creating-a-mobile-web-application-with-meta-tags/)
### javascript
* [Array.prototype.map()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map)
* [Window setTimeout() Method](https://www.w3schools.com/jsref/met_win_settimeout.asp)
* [Arrow functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Arrow_functions)
### react
* [React.Component](https://reactjs.org/docs/react-component.html#the-component-lifecycle)
## 1 May 2018
* [CSS background-position](https://developer.mozilla.org/en-US/docs/Web/CSS/background-position)
* [CSS cursor](https://developer.mozilla.org/en-US/docs/Web/CSS/cursor)
* [CSS Transitions](http://css3.bradshawenterprises.com/transitions/)
* [CSS z-index](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Positioning/Understanding_z_index)
## 30 Apr 2018
### django girls seoul @ GOOGLE CAMPUS KOREA
* [linter](https://subicura.com/2016/07/11/coding-convention.html)
  * flake8
  * [Linting Python in VS Code](https://code.visualstudio.com/docs/python/linting)
* unit test
  * [파이썬 단위테스트](https://til.chann.kr/python/unit_test) import unittest
  * [pytest](https://docs.pytest.org/en/latest/)
* CI(continuous integration) service
  * Jenkins
  * AWS code builder
  * [CircleCI](https://circleci.com/)

### python study
* [pythonstudy.xyz](http://pythonstudy.xyz/)
* [The hitchhiker's Guide to Python](http://python-guide-kr.readthedocs.io/ko/latest/index.html)
* [dive into python3](http://www.diveintopython3.net/index.html)


## 28 Apr 2018
* [Learn D3.js in 5 minutes](https://medium.freecodecamp.org/learn-d3-js-in-5-minutes-c5ec29fb0725)
* SVG(Scalable Vector Graphic)
## 19 Apr 2018
* [hugo](https://gohugo.io/)
* [hugo theme](https://github.com/devcows/hugo-universal-theme)
* [why-learning-to-code-is-so-damn-hard](https://www.vikingcodeschool.com/posts/why-learning-to-code-is-so-damn-hard)
## 18 Apr 2018
* [{ Box-sizing: Border-box } FTW](https://www.paulirish.com/2012/box-sizing-border-box-ftw/)
* [reset.css](https://raw.githubusercontent.com/nomadcoders/kakao-clone/master/css/reset.css)
## 17 Apr 2018
* [emmet cheat-sheet](https://docs.emmet.io/cheat-sheet/)
## 16 Apr 2018
* [netlify](https://www.netlyfycom)
## 15 Apr 2018
* [emmet](https://docs.emmet.io/)
* [Ubuntu Bash Shell](https://blogs.msdn.microsoft.com/eva/?p=7633)
* [macincloud](https://www.macincloud.com/)
* [VSTS](https://www.visualstudio.com/ko/team-services/?rr=https%3A%2F%2Fwww.google.com%2F)
* [library vs framework](https://www.programcreek.com/2011/09/what-is-the-difference-between-a-java-library-and-a-framework/)
* [django overview](https://www.djangoproject.com/start/overview/)
* [VSC](https://code.visualstudio.com/docs/?dv=win)
## 14 Apr 2018
* [getBEM](http://getbem.com/introduction/)
* [BEM keyconcept](https://en.bem.info/methodology/key-concepts/)
* [BEM quick start](https://en.bem.info/methodology/quick-start/)
## 13 Apr 2018
* [Meta tags that Google understands](https://support.google.com/webmasters/answer/79812?hl=en)
* [The Document-level Metadata element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/meta)
* [HTML5 Semantic Elements](https://www.w3schools.com/html/html5_semantic_elements.asp)
* [CSS FLEXBOX FROGGY](http://flexboxfroggy.com/#ko)
* [CSS transition](https://developer.mozilla.org/en-US/docs/Web/CSS/transition)
* [CSS transform](https://developer.mozilla.org/en-US/docs/Web/CSS/transform)
## 12 Apr 2018
* OOP
* MVC
## 11 Apr 2018
* chart.js
* D3js
* [tryruby](tryruby.org)
## 10 Apr 2018
* jQuery UI
## 9 Apr 2018
* jQuery #1: DOM
  $:id /class / eq / nth-child / tagname
  $.append/  $.prepend/  $.remove/  $.text, $.html/  $.attr/  $.css/  $.addClass, $.removeClass/  $.clone
* jQuery #2: Event
  $.click / $.hover / $.focus/  $.mouseover, $.mouseout / $.mouseenter, $.mouseleave/  $.change/function(){}
* Javascript Timer
  setTimeout / setInterval / clearInterval/  $.ready/variable Scope
## 8 Apr 2018
* [Online Interactive HTML Cheat Sheet](http://htmlcheatsheet.com/)
* [Online Interactive CSS Cheat Sheet](http://htmlcheatsheet.com/css/)
* [Online jQuery Cheat Sheet](http://htmlcheatsheet.com/jquery/)
## 7 Apr 2018
* javaschipt for, while
* DOM
* jQuery
## 6 Apr 2018
* [source tree app](https://www.sourcetreeapp.com/)
* [blog - try react](https://blog.naver.com/gi_balja/221224082297)
* [js bin](http://jsbin.com/)
## 5 Apr 2018
* [html-css-js](http://html-css-js.com/)
## 4 Apr 2018
* [markdown](https://guides.github.com/features/mastering-markdown/)
* [google cloud platform](https://sites.google.com/view/cloudstudyjamkr/home)
* edwith
* [github help](https://help.github.com/)
  * [for-a-repo](https://help.github.com/articles/fork-a-repo/)
    * [Keep your fork synced](https://help.github.com/articles/fork-a-repo/#keep-your-fork-synced): To do this, you'll need to use [Git](https://git-scm.com/book/en/v2) on the command line
  * [contribution](https://help.github.com/articles/why-are-my-contributions-not-showing-up-on-my-profile/)
## 3 Apr 2018
* 42
## 1 Apr 2018
### data science course @Gangnam
* pandas visuallization
## 31 Mar 2018
### github seminar @Gangnam
* [how to use github professionally](https://sujinlee.me/professional-github/)
* [jekyll](https://help.github.com/articles/using-jekyll-as-a-static-site-generator-with-github-pages/)
* [udacity nanodegree](https://www.udacity.com)
## 30 Mar 2018
* [git](https://git-scm.com/)
## 29 Mar 2018
* [react-native](https://facebook.github.io/react-native)
## 27 Mar 2018
* react.js
