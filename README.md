GradleTemplateProject
=====================

Template Android Studio Project using Gradle with dependencies, library projects, version codes etc...

The idea is too add useful gradle tasks that I come accross to the template project to build a up practical working android/gradle reference to use in other projects.

<b>Added:</b>
- compile support lib artifacts
- compile required library projects
- min and target SDK
- version code and version name

<b>To Be Added:</b>
- debug/release keystores
- product flavours
- build time custom tasks
- refactoring
- change package name

<b>Need to Look into:</b>
- including a graddle wrapper
- try git plugin to clone repos
- pull in dependencies from maven
- instrument tests
- gradle.properties

<b>Prerequisites:</b>
- Make sure you have the 'Android Support Repository' downloaded through the SDK Manager. This will mean you can compile in the support repo dependencies using their dependency artifacts instead of using their absolute paths or having to copy a jar into your project. This means you will always have the most upto date downloaded support libs.
