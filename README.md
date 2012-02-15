# node-pinyin

A simple pinyin parser for nodejs

## installation

npm install pinyin

## usage
            var pinyin = require('pinyin');
            console.log(pinyin('孙悟空'));
                [ [ 'Sun', 'Wu', 'Kong' ], [ 'Xun', 'Wu', 'Kong' ] ]
            console.log(pinyin('孙悟空',true,''));
                SunWuKong
            console.log(pinyin('孙悟空', false, ','));
                Sun,Wu,Kong,Xun,Wu,Kong

## License

GPL V3
