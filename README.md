# Countries Divisions

A comprehensive JSON module containing primary administrative divisions for countries based on the ISO 3166-1 Alpha-3 standard.

## Installation

To use this module in your project, you can install it via npm:

```bash
npm install @blockchainhub/countries-divisions-alpha3
```

## Usage

Once installed, you can `require` it in your JavaScript/Node.js project:

```javascript
const countriesDivisions = require('@blockchainhub/countries-divisions-alpha3');
console.log(countriesDivisions['USA']); // Example output: { type_en: "State", type_local: "State" }
```

## Data Structure

The module exports a JSON object with the structure:

```json
{
    "ISO_3166-1_Alpha-3_Code": {
        "type_en": "Division Name in English",
        "type_local": "Division Name in Local Language"
    },
    …
}
```

For example:

```json
{
    "USA": {
        "type_en": "State",
        "type_local": "State"
    },
    …
}
```

## Exclusions

The following countries are excluded from the list due to lack of divisions:

- GIB (Gibraltar)
- MAF (Saint Martin (French part))
- NFK (Norfolk Island)
- SPM (Saint Pierre and Miquelon)
- VAT (Holy See (Vatican City State))

## License

This project is licensed under the [CORE License](https://github.com/bchainhub/core-license/blob/master/LICENSE). Please see the [LICENSE](https://github.com/bchainhub/core-license/blob/master/LICENSE) file for more details.

## Contributing

1. Fork the repository.
2. Clone your fork.
3. Create a new branch.
4. Make your changes.
5. Commit and push your changes.
6. Create a pull request.
