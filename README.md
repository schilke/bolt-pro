# genesis-foundation

Welcome to the Genesis / Foundation starter theme. This is a developer theme meant to be a launchpad for developing with the Genesis Framework. It utilizes the Foundation Framework for front-end development.

I have tried to leave the Genesis Framework as untouched as possible.

##Production Gulp Task

I'm aiming to provide all the tools that Foundation has developed but help you keep the filesizes very small. There are Gulptasks written to strip out unused code, and minimize the final files.

If you enter all the important pages into the production gulp task located in /assets/gulp/tasks/production.js the production task will compile all sass files rip out any css that isnt used on the pages listed and then minify the output file.
