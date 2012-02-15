# node-pinyin

A pinyin parser for nodejs

## Installation

npm install pinyin

## Usage
            var pinyin = require('pinyin');
            console.log(pinyin('孙悟空'));
                [ [ 'Sun', 'Wu', 'Kong' ], [ 'Xun', 'Wu', 'Kong' ] ]
            console.log(pinyin('孙悟空',true,''));
                SunWuKong
            console.log(pinyin('孙悟空', false, ','));
                Sun,Wu,Kong,Xun,Wu,Kong

## License

GPL V3

## Resource
    * [pinyin.js](https://raw.github.com/hotoo/pinyin.js/)
    * [将汉字转换成拼音](https://code.google.com/p/chinese-character-2-pinyin/)
