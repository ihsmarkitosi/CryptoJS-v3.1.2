CryptoJS

This repo is straight unmodified-in-any-way copy of Google Code hosted CryptoJS project at https://code.google.com/p/crypto-js/ . This is hosted at github to add bower package so future updates can be managed better.

Directory Structure

You have two folders:

components
rollups
The files in rollups folder is concatenation of one or more files in components folder followed by minification. This makes files in rollups folder standalone includable in your projects without worrying about its dependencies. You can view relation between files in rollup and components here: https://code.google.com/p/crypto-js/source/browse/tags/3.1.2/builder/build.yml
