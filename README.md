
# is-vowel

 [![Support me on Patreon][badge_patreon]][patreon] [![Buy me a book][badge_amazon]][amazon] [![PayPal][badge_paypal_donate]][paypal-donations] [![Version](https://img.shields.io/npm/v/is-vowel.svg)](https://www.npmjs.com/package/is-vowel) [![Downloads](https://img.shields.io/npm/dt/is-vowel.svg)](https://www.npmjs.com/package/is-vowel)

> Checks if an input letter is a vowel or not.

## :cloud: Installation

```sh
$ npm i --save is-vowel
```


## :clipboard: Example



```js
// Dependencies
var IsVowel = require("is-vowel");

console.log(IsVowel("a"));
// => true

console.log(IsVowel("e"));
// => true

console.log(IsVowel("c"));
// => false
```

## :memo: Documentation


### `IsVowel(input)`
Checks if the input is a vowel.

#### Params
- **String** `input`: The input letter.

#### Return
- **Boolean** `true`, if the input is a vowel, `false` otherwise.



## :yum: How to contribute
Have an idea? Found a bug? See [how to contribute][contributing].


## :sparkling_heart: Support my projects

I open-source almost everything I can, and I try to reply everyone needing help using these projects. Obviously,
this takes time. You can integrate and use these projects in your applications *for free*! You can even change the source code and redistribute (even resell it).

However, if you get some profit from this or just want to encourage me to continue creating stuff, there are few ways you can do it:

 - Starring and sharing the projects you like :rocket:
 - [![PayPal][badge_paypal]][paypal-donations]—You can make one-time donations via PayPal. I'll probably buy a ~~coffee~~ tea. :tea:
 - [![Support me on Patreon][badge_patreon]][patreon]—Set up a recurring monthly donation and you will get interesting news about what I'm doing (things that I don't share with everyone).
 - **Bitcoin**—You can send me bitcoins at this address (or scanning the code below): `1P9BRsmazNQcuyTxEqveUsnf5CERdq35V6`

    ![](https://i.imgur.com/z6OQI95.png)

Thanks! :heart:


## :dizzy: Where is this library used?
If you are using this library in one of your projects, add it in this list. :sparkles:


 - [`khaan`](https://github.com/zuzak/node-khaan) (by Douglas Gardner)—Word elongator
 - [`name-it`](https://github.com/IonicaBizau/name-it#readme)—Generate project names from given keywords.
 - [`never-bored`](https://github.com/geekytime/never-bored#readme) (by GeekyTime)—Generate 100s of fun and easy activities for kids to do on their own.
 - [`unvowel-last`](https://github.com/IonicaBizau/unvowel-last#readme)—Removes the last letter from a string if it is a vowel.

## :scroll: License

[MIT][license] © [Ionică Bizău][website]

[badge_patreon]: http://ionicabizau.github.io/badges/patreon.svg
[badge_amazon]: http://ionicabizau.github.io/badges/amazon.svg
[badge_paypal]: http://ionicabizau.github.io/badges/paypal.svg
[badge_paypal_donate]: http://ionicabizau.github.io/badges/paypal_donate.svg
[patreon]: https://www.patreon.com/ionicabizau
[amazon]: http://amzn.eu/hRo9sIZ
[paypal-donations]: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=RVXDDLKKLQRJW
[donate-now]: http://i.imgur.com/6cMbHOC.png

[license]: http://showalicense.com/?fullname=Ionic%C4%83%20Biz%C4%83u%20%3Cbizauionica%40gmail.com%3E%20(https%3A%2F%2Fionicabizau.net)&year=2015#license-mit
[website]: https://ionicabizau.net
[contributing]: /CONTRIBUTING.md
[docs]: /DOCUMENTATION.md
