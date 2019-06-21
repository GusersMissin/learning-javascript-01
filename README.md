# learning-javascript-01

テクノロジー（藤原）JavaScriptの練習 (1)

## Q1の回答「コメントを解除したことで、どう変化しましたか？」

ウェブサイトのウィンドウズでこんにちは！と出ました。

## Q2の回答「エラーの原因は何でしょうか？（調べてみましょう）」

windowというコマンドが定義されていないから

## Chromeデベロッパーツール：Consoleの実行結果

```
VM13 main.js:4 Good morning.
index.html:18 おはよう！
index.html:56 Live reload enabled.
index.html:51 [Violation] 'message' handler took 1090ms
index.html:18 おはよう！
Navigated to http://127.0.0.1:5500/index.html
index.html:52 [Intervention] Blocked attempt to show a 'beforeunload' confirmation panel for a frame that never had a user gesture since its load. https://www.chromestatus.com/feature/5082396709879808
socket.onmessage @ index.html:52
Navigated to http://127.0.0.1:5500/index.html
VM73 main.js:4 Good morning.
index.html:18 おはよう！
index.html:52 [Intervention] Blocked attempt to show a 'beforeunload' confirmation panel for a frame that never had a user gesture since its load. https://www.chromestatus.com/feature/5082396709879808
socket.onmessage @ index.html:52
Navigated to http://127.0.0.1:5500/index.html
main.js:4 Good morning.
index.html:18 おはよう！
```

## ターミナルの実行結果

```
(base) Ans-MacBook-Pro:03藤原先生 missingusers$ cd fujiwara/
(base) Ans-MacBook-Pro:fujiwara missingusers$ ls
hello-git		sample-web-server
learning-http-message	simple-web-site
(base) Ans-MacBook-Pro:fujiwara missingusers$ clear

(base) Ans-MacBook-Pro:fujiwara missingusers$ git clone git@github.com:GusersMissin/learni
Cloning into 'learni'...
^C
(base) Ans-MacBook-Pro:fujiwara missingusers$ git clone git@github.com:GusersMissin/learni
Cloning into 'learni'...
ERROR: Repository not found.
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
(base) Ans-MacBook-Pro:fujiwara missingusers$ git clone git@github.com:GusersMissin/learning-javascript-01.git
Cloning into 'learning-javascript-01'...
remote: Enumerating objects: 10, done.
remote: Counting objects: 100% (10/10), done.
remote: Compressing objects: 100% (8/8), done.
remote: Total 10 (delta 0), reused 7 (delta 0), pack-reused 0
Receiving objects: 100% (10/10), done.
(base) Ans-MacBook-Pro:fujiwara missingusers$ cd learning-javascript-01/
(base) Ans-MacBook-Pro:learning-javascript-01 missingusers$ code .
(base) Ans-MacBook-Pro:learning-javascript-01 missingusers$ code .
(base) Ans-MacBook-Pro:learning-javascript-01 missingusers$ node node-main.js
/Users/missingusers/Desktop/01授業資料/01テクノロジー/03藤原先生/fujiwara/learning-javascript-01/node-main.js:1
window.alert("Hello, Node.js!!");
^

ReferenceError: window is not defined
    at Object.<anonymous> (/Users/missingusers/Desktop/01授業資料/01テクノロジー/03藤原先生/fujiwara/learning-javascript-01/node-main.js:1:1)
    at Module._compile (internal/modules/cjs/loader.js:774:30)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:785:10)
    at Module.load (internal/modules/cjs/loader.js:641:32)
    at Function.Module._load (internal/modules/cjs/loader.js:556:12)
    at Function.Module.runMain (internal/modules/cjs/loader.js:837:10)
    at internal/main/run_main_module.js:17:11
(base) Ans-MacBook-Pro:learning-javascript-01 missingusers$ node node-main.js
/Users/missingusers/Desktop/01授業資料/01テクノロジー/03藤原先生/fujiwara/learning-javascript-01/node-main.js:1
window.alert("Hello, Node.js!!");
^

ReferenceError: window is not defined
    at Object.<anonymous> (/Users/missingusers/Desktop/01授業資料/01テクノロジー/03藤原先生/fujiwara/learning-javascript-01/node-main.js:1:1)
    at Module._compile (internal/modules/cjs/loader.js:774:30)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:785:10)
    at Module.load (internal/modules/cjs/loader.js:641:32)
    at Function.Module._load (internal/modules/cjs/loader.js:556:12)
    at Function.Module.runMain (internal/modules/cjs/loader.js:837:10)
    at internal/main/run_main_module.js:17:11
(base) Ans-MacBook-Pro:learning-javascript-01 missingusers$ node node-main.js
/Users/missingusers/Desktop/01授業資料/01テクノロジー/03藤原先生/fujiwara/learning-javascript-01/node-main.js:1
window.alert("Hello, Node.js!!");
^

ReferenceError: window is not defined
    at Object.<anonymous> (/Users/missingusers/Desktop/01授業資料/01テクノロジー/03藤原先生/fujiwara/learning-javascript-01/node-main.js:1:1)
    at Module._compile (internal/modules/cjs/loader.js:774:30)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:785:10)
    at Module.load (internal/modules/cjs/loader.js:641:32)
    at Function.Module._load (internal/modules/cjs/loader.js:556:12)
    at Function.Module.runMain (internal/modules/cjs/loader.js:837:10)
    at internal/main/run_main_module.js:17:11
(base) Ans-MacBook-Pro:learning-javascript-01 missingusers$ node node-main.js
/Users/missingusers/Desktop/01授業資料/01テクノロジー/03藤原先生/fujiwara/learning-javascript-01/node-main.js:1
window.alert("Hello, Node.js!!");
^

ReferenceError: window is not defined
    at Object.<anonymous> (/Users/missingusers/Desktop/01授業資料/01テクノロジー/03藤原先生/fujiwara/learning-javascript-01/node-main.js:1:1)
    at Module._compile (internal/modules/cjs/loader.js:774:30)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:785:10)
    at Module.load (internal/modules/cjs/loader.js:641:32)
    at Function.Module._load (internal/modules/cjs/loader.js:556:12)
    at Function.Module.runMain (internal/modules/cjs/loader.js:837:10)
    at internal/main/run_main_module.js:17:11
(base) Ans-MacBook-Pro:learning-javascript-01 missingusers$ node node-main.js
Goodmorning, Node.js!!
(base) Ans-MacBook-Pro:learning-javascript-01 missingusers$ node node-main.js
Goodmorning, Node.js!!
(base) Ans-MacBook-Pro:learning-javascript-01 missingusers$ node node-main.js
Goodmorning, Node.js!!

```

