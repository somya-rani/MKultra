# MKultra

Compiled with problems:
×
ERROR in ./src/index.jsx
Module build failed (from ./node_modules/react-scripts/node_modules/babel-loader/lib/index.js):
SyntaxError: C:\Windows\System32\sit\src\index.jsx: Identifier 'App' has already been declared. (7:6)

   5 | render(<App />, document.getElementById('root'));
   6 |
>  7 | const App = () => {
     |       ^
   8 |   const handleClick = async () => {
   9 |     // Dynamically import JavaScript module
  10 |     const { default: myModule } = await import("./login.js");
    at instantiate (C:\Windows\System32\sit\node_modules\@babel\parser\lib\index.js:63:32)
    at constructor (C:\Windows\System32\sit\node_modules\@babel\parser\lib\index.js:358:12)
    at FlowParserMixin.raise (C:\Windows\System32\sit\node_modules\@babel\parser\lib\index.js:3255:19)
    at FlowScopeHandler.checkRedeclarationInScope (C:\Windows\System32\sit\node_modules\@babel\parser\lib\index.js:1528:19)
    at FlowScopeHandler.declareName (C:\Windows\System32\sit\node_modules\@babel\parser\lib\index.js:1499:12)
    at FlowScopeHandler.declareName (C:\Windows\System32\sit\node_modules\@babel\parser\lib\index.js:1595:11)
    at FlowParserMixin.declareNameFromIdentifier (C:\Windows\System32\sit\node_modules\@babel\parser\lib\index.js:7511:16)
    at FlowParserMixin.checkIdentifier (C:\Windows\System32\sit\node_modules\@babel\parser\lib\index.js:7507:12)
    at FlowParserMixin.checkLVal (C:\Windows\System32\sit\node_modules\@babel\parser\lib\index.js:7446:12)
    at FlowParserMixin.parseVarId (C:\Windows\System32\sit\node_modules\@babel\parser\lib\index.js:13278:10)
    at FlowParserMixin.parseVarId (C:\Windows\System32\sit\node_modules\@babel\parser\lib\index.js:5718:11)
    at FlowParserMixin.parseVar (C:\Windows\System32\sit\node_modules\@babel\parser\lib\index.js:13256:12)
    at FlowParserMixin.parseVarStatement (C:\Windows\System32\sit\node_modules\@babel\parser\lib\index.js:13096:10)
    at FlowParserMixin.parseStatementContent (C:\Windows\System32\sit\node_modules\@babel\parser\lib\index.js:12679:23)
    at FlowParserMixin.parseStatementLike (C:\Windows\System32\sit\node_modules\@babel\parser\lib\index.js:12584:17)
    at FlowParserMixin.parseStatementLike (C:\Windows\System32\sit\node_modules\@babel\parser\lib\index.js:5130:24)
    at FlowParserMixin.parseModuleItem (C:\Windows\System32\sit\node_modules\@babel\parser\lib\index.js:12561:17)
    at FlowParserMixin.parseBlockOrModuleBlockBody (C:\Windows\System32\sit\node_modules\@babel\parser\lib\index.js:13185:36)
    at FlowParserMixin.parseBlockBody (C:\Windows\System32\sit\node_modules\@babel\parser\lib\index.js:13178:10)
    at FlowParserMixin.parseProgram (C:\Windows\System32\sit\node_modules\@babel\parser\lib\index.js:12460:10)
    at FlowParserMixin.parseTopLevel (C:\Windows\System32\sit\node_modules\@babel\parser\lib\index.js:12450:25)
    at FlowParserMixin.parseTopLevel (C:\Windows\System32\sit\node_modules\@babel\parser\lib\index.js:5935:28)
    at FlowParserMixin.parse (C:\Windows\System32\sit\node_modules\@babel\parser\lib\index.js:14347:10)
    at parse (C:\Windows\System32\sit\node_modules\@babel\parser\lib\index.js:14388:38)
    at parser (C:\Windows\System32\sit\node_modules\react-scripts\node_modules\@babel\core\lib\parser\index.js:41:34)
    at parser.next (<anonymous>)
    at normalizeFile (C:\Windows\System32\sit\node_modules\react-scripts\node_modules\@babel\core\lib\transformation\normalize-file.js:64:38)
    at normalizeFile.next (<anonymous>)
    at run (C:\Windows\System32\sit\node_modules\react-scripts\node_modules\@babel\core\lib\transformation\index.js:21:50)
    at run.next (<anonymous>)
    at transform (C:\Windows\System32\sit\node_modules\react-scripts\node_modules\@babel\core\lib\transform.js:22:41)
    at transform.next (<anonymous>)
    at step (C:\Windows\System32\sit\node_modules\gensync\index.js:261:32)
    at C:\Windows\System32\sit\node_modules\gensync\index.js:273:13
    at async.call.result.err.err (C:\Windows\System32\sit\node_modules\gensync\index.js:223:11)
ERROR in ./src/MainPage.mjs 10:0-108
Module not found: Error: Can't resolve './src/Imagres/WhatsApp Image 2023-06-12 at 12.17.10 PM_waifu2x_noise1_scale4x.png' in 'C:\Windows\System32\sit\src'
ERROR in ./src/MainPage.mjs 11:0-108
Module not found: Error: Can't resolve './src/Imagres/WhatsApp Image 2023-06-12 at 12.20.12 PM_waifu2x_noise1_scale4x.png' in 'C:\Windows\System32\sit\src'
ERROR in ./src/MainPage.mjs 12:0-108
Module not found: Error: Can't resolve './src/Imagres/WhatsApp Image 2023-06-12 at 12.20.19 PM_waifu2x_noise1_scale4x.png' in 'C:\Windows\System32\sit\src'
ERROR in ./src/MainPage.mjs 13:0-44
Module not found: Error: Can't resolve './Landing_Page/dist/Newsletter.css' in 'C:\Windows\System32\sit\src'
ERROR in ./src/MainPage.mjs 14:0-32
Module not found: Error: Can't resolve './Login/dist/index.jsx' in 'C:\Windows\System32\sit\src'
ERROR in ./src/MainPage.mjs 18:18-28
export 'useHistory' (imported as 'useHistory') was not found in 'preact-router' (possible exports: Link, Route, Router, default, exec, getCurrentUrl, route, useRouter)
ERROR in ./src/MainPage.mjs 292:10-20
export 'useHistory' (imported as 'useHistory') was not found in 'preact-router' (possible exports: Link, Route, Router, default, exec, getCurrentUrl, route, useRouter)
ERROR
[eslint] 
src\index.jsx
  Line 7:6:  Parsing error: Identifier 'App' has already been declared. (7:6)
