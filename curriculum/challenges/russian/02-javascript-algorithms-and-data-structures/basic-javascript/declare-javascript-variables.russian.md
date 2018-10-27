---
id: bd7123c9c443eddfaeb5bdef
title: Declare JavaScript Variables
challengeType: 1
videoUrl: ''
localeTitle: Объявление переменных JavaScript
---

## Description
<section id="description"> В информатике <dfn>данные</dfn> - это все, что имеет значение для компьютера. JavaScript предоставляет семь разных <dfn>типов данных,</dfn> : <code>undefined</code> , <code>null</code> , <code>boolean</code> , <code>string</code> , <code>symbol</code> , <code>number</code> и <code>object</code> . Например, компьютеры различают числа, такие как число <code>12</code> и строки <code>strings</code> , такие как <code>&quot;12&quot;</code> , <code>&quot;dog&quot;</code> или <code>&quot;123 cats&quot;</code> , которые представляют собой наборы символов. Компьютеры могут выполнять математические операции над числами, но не над строками. <dfn>Переменные</dfn> используются компьютерами для хранения данных и выполнения над ними различных действий. Для этого компьютеры используют не собственно данные, а «метку», которая на них указывает. В переменной может сохраняться любой из семи типов данных. <code>Variables</code> подобны переменным <code>Variables</code> x и y, которые вы используете в математике. Таким образом, они по сути - просто имена для представления данных, к которым мы хотим обратиться. Компьютерные <code>variables</code> отличаются от математических тем, что они могут хранить разные значения в разное время. Мы даем указание, чтобы JavaScript создал или <dfn>объявил</dfn> переменную, поставив перед ней ключевое слово <code>var</code> , например: <blockquote> var ourName; </blockquote> создает <code>variable</code> с именем <code>ourName</code> . В JavaScript операторы заканчиваются точкой с запятой. Имена <code>Variable</code> могут состоять из чисел, букв, а также символов <code>$</code> или <code>_</code> , но они не могут содержать пробелов или начинаться с числа. </section>

## Instructions
<section id="instructions"> Используйте ключевое слово <code>var</code> для создания переменной <code>myName</code> . <strong>намек</strong> <br> Посмотрите на пример <code>ourName</code> если вы застряли. </section>

## Tests
<section id='tests'>

```yml
tests:
  - text: 'Вы должны объявить <code>myName</code> с ключевым словом <code>var</code> , заканчивающимся точкой с запятой'
    testString: 'assert(/var\s+myName\s*;/.test(code), "You should declare <code>myName</code> with the <code>var</code> keyword, ending with a semicolon");'

```

</section>

## Challenge Seed
<section id='challengeSeed'>

<div id='js-seed'>

```js
// Example
var ourName;

// Declare myName below this line

```

</div>


### After Test
<div id='js-teardown'>

```js
console.info('after the test');
```

</div>

</section>

## Solution
<section id='solution'>

```js
// solution required
```
</section>
