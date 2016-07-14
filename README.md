### *Why we should use Angular 2 with typescript*

1. Code Unification

  * Large organizations have the advantage of creating conventions and style guides for their code, this make it so that the code is easily readable by the engineering team. As a startup(kind of) we have no such thing, and this leads to messy code, anti-patterns, and non-scalability of codebase.
  
2. Future-Proofing
  
  * Typescript currently makes available, features of ECMAscript2015 (javascript es6). Though most browsers only support es5, this language will allow you to easily, and with one simple command recomile your typescript code to es6 once support is universal. 
  * It is also worth noting that you can still write es5 javascript in typescript as any version of javascript makes for valid typescript.
  * Additional features:
    * Optional Static Typing
    * Decorators
    * Template Strings + Interpolation (instead of concatenating ``` "<p class='"+variable+"'>" +othervar+"</p>" ``` etc..., instead you would use backticks like so (`` `<p class="${variable}">${othervar}</p>` ``). this makes templating efficient, easier to read and with 1 and 2 way data binding this becomes extremely powerful especially if you are building modular apps with features that generate widgets/ui.
    * Intellisense 
    * +many more!

3. Testing
  
  * As a start up (kind of), and most importantly as a start-up that does not have a QA Engineer, we can benefit massively from the use of TS, because its compiletime error reports will act as a first round of unit tests.
  * Since Angular 2 modules are now just typescript classes, unit testing is even easier and more powerful than ever before.

4. Speed & Performance
  
  * Angular's UI rendering engine is the fastest one out there, no other framework beats it. Many tests have been run by  third parties to confirm this. 
  * Angular brings many technologies together to improve performance, that would require hours upon hours for us to       compile, and make use of such as web workers etc...

5. Supported and Maintained by Top Google Engineers
  
  * A head-dizzying team of genius programmers have built this framework from the ground up, they also update, and maintain it at no charge to anyone.

6. The best at no charge
  
  * With the future of the company moving towards building cross platform applications, the Ionic 2 framework (smarter, better, faster, stronger) will automatically compile any apps we've built with A2 into native code for any platform to which we want to deliver. 
