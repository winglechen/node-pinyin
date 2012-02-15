# node-pinyin

A pinyin parse for nodejs

## installation

npm install pinyin

## usage
            var pinyin = require('pinyin');
            console.log(pinyin('ËïÎò¿Õ'));
                [ [ 'Sun', 'Wu', 'Kong' ], [ 'Xun', 'Wu', 'Kong' ] ]
            console.log(pinyin('ËïÎò¿Õ',true,''));
                SunWuKong
            console.log(pinyin('ËïÎò¿Õ', false, ','));
                Sun,Wu,Kong,Xun,Wu,Kong

## License

GPL V3
