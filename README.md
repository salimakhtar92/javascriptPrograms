# Javascript Programs

### Program-1: Camalized the following types of string 'border-bottm-left' to 'borderBottomLeft'
```
const str = ' border-bottm-left';

const camalizedString = (str) => str.split('-').map((word, index) => index === 0 ? word : word[0].toUpperCase() + word.slice(1)).join('');

camalizedString(str)

```
