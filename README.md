# Cod Reducere Elefant

O colecție de coduri de reducere Elefant. Le folosim pentru testarea cuvintelor cheie [cod reducere Elefant](https://cuponescu.ro/magazin/elefant), [voucher Elefant](https://cuponescu.ro/magazin/elefant), [cupon Elefant](https://cuponescu.ro/magazin/elefant), și [cod promotional Elefant](https://cuponescu.ro/magazin/elefant) de pe Cuponescu.ro.

## Instalare

Instalează `cod-reducere-elefant` prin NPM:

```bash
npm install cod-reducere-elefant
```

## Utilizare

Pachetul conține un array de obiecte reprezentând coduri de reducere.

În Node:

```javascript
var codes = require('cod-reducere-elefant')

console.log(codes)

// [
//   {
//     site: 'https://www.elefant.ro',
//     cod_reducere: 'ELEFANT10',
//     reducere: '10% reducere',
//     descriere: 'Reducere de 10% la toate produsele'
//   },
//   ...
// ]
```

## Despre

Cod-reducere-elefant a fost creat de echipa de la [Cuponescu](https://cuponescu.ro/) pentru a ajuta cu testarea.
