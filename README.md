# pagosbit
Procesador de pagos Bitcoin / CLP

## Objetivo
- Permitir que negocios en Chile acepten Bitcoin como medio de pago

## Funcionamiento
- Se crea un invoice por una cantidad de pesos
- Se genera la direccin bitcoin a pagar y la cantidad
- Cuando se paga a esa dirección entonces el procesador avisa al comercio que está pagado
- Finalmente se convierten los BTC a CLP de acuerdo con el invoice

## TODO

### Prototipo
- [ ] Revisar la [API de bitpay](https://bitpay.com/api) (para cachar como funcionan ellos)
- [ ] Revisar los [terminos de bitpay](https://bitpay.com/about/terms) (para asegurarse)
- [ ] Investigar [Bircore](https://bitcore.io) (es FOSS, Bitpay esta hecho sobre Bitcore)
- [ ] Revisar los BIP, son estandares del procolo Bitcoin, algunos estandarizan los pagos ([BIP70 por ej](https://blog.bitpay.com/bitpay-launches-payment-protocol-support/))
- [ ] Ver si es necesario un backend, o si lo hacemos 100% realtime
- [ ] Decidir que informacion vamos a guardar en el sistema, las entidades, relaciones, etc
- [ ] Ver en que lenguaje hacemos el backend (Rodrigo y Sebastian: cachamos mas Python)
- [ ] Ver que framework ocupamos para el frontend
- [ ] Muchas cosas mas xD

### Negocio
- [ ] Decidir quien paga el fee, la tienda o el comprador
- [ ] Decidir el % de fee
- [ ] Tantear el terreno con Zmart, PC Factory, etc...
- [ ] Decidir si es necesario postular a algo en [CORFO](http://static.cl1.fidelizador.com/corfo/PMO_2017/Enero/Calendario_Subgerencia_Financiamiento_2017.pdf)
- [ ] Muchas cosas mas xD
