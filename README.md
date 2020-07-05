# Javascript Programs

### Program-1: Camalized the following types of string 'border-bottm-left' to 'borderBottomLeft'
```
const strValue = ' border-bottm-left';

const camelizeString = str => str.split('-').map((word, index) => index === 0 ? word : word[0].toUpperCase() + word.slice(1)).join('');

camalizedString(strValue)

```
