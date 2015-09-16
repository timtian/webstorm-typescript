# webstorm-typescript

## ts-compiler-host-impl
when use &lt;= webstorm 10.0.4  + typescript 1.6
TypeScript Compiler will got some error
because ts-compiler-host-impl not support typescript 1.6

>Error:Cannot start compiler process:  Error: Cannot read tsconfig

OR

>Error:Error has occurred in the compile process TypeError: Object [object Object] has no method 'fileExists'

OR 

>Total process result time NaN

you can download [ts-compiler-host-impl-1.6.fix.js](https://raw.githubusercontent.com/timtian/webstorm-typescript/master/ts-compiler-host-impl-1.6.fix.js) file to overwrite 
JetBrains\WebStorm 10.0.4\plugins\JavaScriptLanguage\typescriptCompiler\ts-compiler-host-impl.js
