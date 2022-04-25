# Beata Słowik
## Contact
* Email: [beslowik@gmail.com](mailto:beslowik@gmail.com)
* Discord: Beata#9550
* Messenger: [Beata Słowik](https://www.facebook.com/beata.slowik)


## Summary
My goal is to become a frontend developer and some day a frontend teacher. I find fullfuling when I can help somebody to develop him or herself.

## Skills
- HTML
- CSS
- JS
- GIT

## Code example
```
function toWeirdCase(string) {
    let newString = string.split(" ");
    let weirdString = [];
    for (let index = 0; index < newString.length; index++) {
        for (let i = 0; i < newString[index].length; i++) {
            if (i === 0) {
                let letter = newString[index][i].toUpperCase();
                weirdString.push(letter);
            } else if (i % 2 !== 0) {
                let letter = newString[index][i].toLowerCase()
                weirdString.push(letter);
            } else if (i % 2 === 0) {
                let letter = newString[index][i].toUpperCase()
                weirdString.push(letter);
            }
        }
        weirdString.push(' ');
    }
    return weirdString.join('').trim();
}
```
Code example on Github [Website](https://github.com/beaslowik/bhagaskara_website)

## Experience
No commercial experience as a frontend developer. More than 10 years experience as a EU fund specialist.

## Education
Jagiellonian University Masters Degree in Political Sciences.

## Languages
|Language | Level        |
|---------|--------------|
|Polish   |native sepaker|
|English   |B2           |
|Italian   |A1           |
