# Nushell LSP experiment for VSCode

To run: 

* run `npm install`
* Build the `ide` enabled branch of nushell: https://github.com/jntrnr/nushell/tree/ide
* modify the `nu` executable location in server/src/server.ts from `/Users/jt/Source/nushell/target/debug/nu` to the location of your IDE-enabled nushell
* open up this project in vscode and run it `Run -> Start Debugging`
