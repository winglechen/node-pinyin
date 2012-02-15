# node-pinyin

A pinyin parse for nodejs

## installation

npm install pinyin

## usage
            var pinyin = require('pinyin');
            console.log(pinyin('�����'));
                [ [ 'Sun', 'Wu', 'Kong' ], [ 'Xun', 'Wu', 'Kong' ] ]
            console.log(pinyin('�����',true,''));
                SunWuKong
            console.log(pinyin('�����', false, ','));
                Sun,Wu,Kong,Xun,Wu,Kong

## License

GPL V3
