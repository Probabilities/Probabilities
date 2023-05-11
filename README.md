<p align="center"><img src="https://gpvc.arturio.dev/Probabilities" alt="Visitors"></a>
<img src="https://img.shields.io/badge/dynamic/json?&label=Total%20Stars&color=bb2527&style=flat&style=for-the-badge&query=%24.stars&url=https://api.github-star-counter.workers.dev/user/Probabilities" alt="Profile Stars"></a>
<img src="https://img.shields.io/badge/dynamic/json?&label=Total%20Forks&color=bb2527&style=flat&style=for-the-badge&query=%24.forks&url=https://api.github-star-counter.workers.dev/user/Probabilities" alt="Profile Forks"></a>

```js
class Probabilities {
    constructor() {
        this.alias  = [ 'Probabilities', 'Socket' ]
    }

    contact() {
        const discord  = 'Socket#0002'
        const telegram = 't.me/gaveaway'
        const email    = 'xmlrequest@proton.me'
        
        return discord, telegram, email
    }

    life() {
        const age        = 18
        const occupation = 'Student (Studying Computing & IT Media)'
        const hobbies    = [ 'Programming', 'Reverse Engineering', 'Reading' ]
        
        return age, occupation, hobbies
    }

    programming() {
        const languages         = [ 'Javascript (Node.js Framework)', 'Python', 'C#' ];
        const learning          = [ 'Golang' ];
        const ide               = 'Visual Studio Code';

        const preferredLanguage = languages[0];

        return languages, learning, ide, preferredLanguage
    }
}

module.exports = Probabilities
```
