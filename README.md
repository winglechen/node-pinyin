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
     * [https://raw.github.com/hotoo/pinyin.js/ pinyin.js]
     * [https://code.google.com/p/chinese-character-2-pinyin/ 将汉字转换成拼音]
     * [http://www.cnblogs.com/jinweijie/archive/2008/02/03/1063289.html 字符转拼音 javascript pinyin] ([http://cid-80b2ed83de3c7c17.skydrive.live.com/self.aspx/Code/pinyin.rar pinyin.rar])
     * [http://jsime.sourceforge.net/ Javascript Input Method Editors] ([http://leen.name/ime/pinyin.html 中文], [http://leen.name/ime/english.html En])
