### Week 8
https://github.com/turbolinks/turbolinks/blob/master/README.md

https://www.softwarearchitekt.at/post/2019/01/27/building-angular-elements-with-the-cli.aspx



### Week 7
- SWC: An alternative to Babel  
https://swc-project.github.io/blog/2019/02/08/Introducing-swc-1.0  
A transpiler much faster than Babel with the same features... really?

- Lazy Load Non-Routable Modules in Angular  
https://netbasal.com/the-need-for-speed-lazy-load-non-routable-modules-in-angular-30c8f1c33093
A guide how you can implement lazy-loading in Angular without being coupled to the Angular router. Crazy complicated, compared to other frameworks ... I think [`<lazy-af>`](https://www.npmjs.com/package/@herodevs/lazy-af) is warpping that aproach into a component.

- easy-peasy - a state management library for react  
https://github.com/ctrlplusb/easy-peasy  
This looks like the version of the Redux pattern I like. The advantages of Redux but the ease of use of traditional OO: calling functions to modify state. Of course leveraging React Hooks.

- Immutability Changes Everything  
http://cidrdb.org/cidr2015/Papers/CIDR15_Paper16.pdf  
Interesting paper. Some arguments why immutability becomes more popular recently.

- Effective Snapshot Testing  
https://blog.kentcdodds.com/effective-snapshot-testing-e0d1a2c28eca  
I still have not used snapshot testing in any of my projects. I am still sceptical about its value. This article adresses some of the scepticism.

- UI AS AN AFTERTHOUGHT  
https://michel.codes/blogs/ui-as-an-afterthought  
Thooughts about state management in React from the creator of MobX. The big topic is decoupling logic from presentation. Especially interesting the claim that [react-apollo](https://github.com/apollographql/react-apollo) leads to unwanted coupling.

- Hacker News: Discussion about decoupling logic and presentation  
https://news.ycombinator.com/item?id=19067302
Some intersting points in these discussions concerning mangaing state in a component tree.

- Lambda and serverless is one of the worst forms of proprietary lock-in we've ever seen.  
https://www.theregister.co.uk/2017/11/06/coreos_kubernetes_v_world/  
Old article but still interesting read. Especially the monthly AWS cost of 1 Mio ...



### Week 5
- Why do people prefer TypeScript with most of the JavaScript frameworks?  
https://www.quora.com/Why-do-people-prefer-TypeScript-with-most-of-the-JavaScript-frameworks/answers/119423108  
A good summary of the advantages of TypeScript.

- Automated testing of each commit != CI  
https://medium.com/@Jakeherringbone/automated-testing-of-each-commit-ci-6f718d93d0da   
A critical reflection about micro-services in regard to continuous integration. Also a good argumentation why relying on API contracts often does not work in the real world.

- The Big List of Naughty Strings  
https://github.com/minimaxir/big-list-of-naughty-strings  
A list of strings which have a high probability of causing issues when used as user-input data.

- Micro Frontends – a strive for fully Verticalized Systems (David Leitner)  
https://www.youtube.com/watch?v=oxVRG71rF3w  
A great talk about micro frontends. Slides are available [here](https://speakerdeck.com/duffleit/microfrontends-c587441e-d8e7-4883-9e14-c9dfaf8e36e3).

- Detecting "Agile BS"   
https://media.defense.gov/2018/Oct/09/2002049591/-1/-1/0/DIB_DETECTING_AGILE_BS_2018.10.05.PDF  
A paper from the Department of Defense, describing the real values of Agile to differenciate projects that just claim to be agile.

- CSS in JavaScript with Angular  
https://medium.com/creative-technology-concepts-code/css-in-javascript-with-angular-61da79111804  
CSS-in-JS is going crazy in the React ecosystem. Do we really want the crazyness in Angular?

### Week 4

- The TypeScript Tax  
https://medium.com/javascript-scene/the-typescript-tax-132ff4cb175b  
A critical evaluation of the cost vs. benefits of TypeScript.

- `<lazy-af>` for lazy loading in Angular  
https://www.npmjs.com/package/@herodevs/lazy-af  
A felxible way to do lazy loading of modules in Angular without being coupled to the router.

- MobX for Angular and Ionic Apps  
https://levelup.gitconnected.com/how-to-manage-state-in-ionic-2-apps-with-mobx-df659de6a8aa  
An introduction to MobX for Angular developers. Contains also a short comparison to NgRx/Redux.

- Opinionated guidelines for large nx angular projects  
https://blog.strongbrew.io/opinionated-guidelines-for-large-nx-angular-projects/  
Good tips on structuring an Angular application.

- The differences between ElementRef, TemplateRef, ViewContainerRef | Ashnita Bali & Marcin Ryzycki  
https://www.youtube.com/watch?v=uQqp1z7FpJY  
The talk gives an overview about the deeper templating constructs of Angular. It's scary ...

- How to configure Webpack 4 with Angular 7
https://medium.freecodecamp.org/how-to-configure-webpack-4-with-angular-7-a-complete-guide-9a23c879f471   
Setting up an Angular project without the Angular CLI is difficult. Here is an example.

- Vue Enterprise Boilerplate   
https://github.com/chrisvfritz/vue-enterprise-boilerplate  
An ever-evolving, very opinionated architecture and dev environment for new Vue SPA projects using Vue CLI 3.

- Salary Comparison for Software Engineers  
https://www.levels.fyi/SE/Google/Facebook/Microsoft  
Crazy! According to that numbers, we should all try to go work in the US ...

#### Tweets
- WebFrameworks & Abstraction   
https://twitter.com/garybernhardt/status/1088523317089169408
An interesting thread on twitter critizising the leaky abstractions of all current web frameworks.

- "Agility at scale" is nuts  
https://twitter.com/allenholub/status/1083845056346243072



