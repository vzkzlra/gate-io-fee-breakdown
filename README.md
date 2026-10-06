# comisiones gate io: cuánto te cobra de verdad en spot, futuros y retiros, y cómo bajar la factura

Hiciste una operación en Gate, entraste al historial y apareció un cargo que no cuadra con lo que tenías en la cabeza. La duda es siempre la misma: ¿de dónde sale ese número?

La respuesta corta es que Gate no cobra "una comisión". Cobra por bloques separados —trading, derivados, retiros, P2P, servicios como acciones o Alpha— y la tarifa que te toca dentro de cada bloque depende de dos cosas: si tu orden añade o consume liquidez, y tu nivel VIP.

Antes de entrar al detalle, los números base:

> Spot en VIP0: 0,1 % maker y 0,1 % taker. Futuros perpetuos con margen en USDT desde 0,020 % maker y 0,050 % taker. Depósitos en cripto: gratis. Retiros: coste de red, variable y visible antes de confirmar. P2P: 0 % de comisión de plataforma. Y si pagas las comisiones spot con GT, ese 0,1 % baja a 0,09 %.

El detalle útil está en las excepciones: dónde el descuento deja de funcionar, qué niveles no cambian nada y qué costes no son comisiones pero se te cobran igual.

## Todas las comisiones que puedes acabar pagando en Gate

No todo lo que resta saldo es una comisión de trading. Conviene separar:

- **Comisión spot** (maker/taker) sobre la parte ejecutada de cada orden.
- **Comisión de futuros y margen**, con tabla propia y más baja que la spot.
- **Opciones y contratos Alpha**, que se cobran aparte.
- **Comisión de acciones y CFD**, con estructura independiente.
- **Coste de retiro**: se paga a la red, no como comisión de trading.
- **Depósitos en fiat** por tarjeta o transferencia: depende del proveedor y del país.
- **Funding de perpetuos**: cada 8 horas, y no es una comisión.
- **Interés de préstamo** en margen, si mantienes deuda abierta.
- **Comisión P2P de plataforma**: cero en Gate.

Los dos últimos son los que más sorpresas generan. El funding puede superar en pocos días lo que pagaste en comisiones al abrir la posición, y el interés de margen se acumula mientras el préstamo siga vivo. En ambos casos Gate no te está cobrando una tarifa suya: son pagos entre usuarios o al pool de préstamo.

## Spot: maker, taker y por qué la diferencia importa poco al principio

Gate usa el modelo maker/taker. Maker es quien deja una orden en el libro y espera; taker es quien entra y cruza el spread de inmediato. La clasificación se decide en cada ejecución, no por el botón que pulsaste: una orden limitada que se cruza al instante se cobra como taker.

En los primeros niveles de la tabla esa distinción casi no sirve de nada. VIP0, VIP1, VIP2 y VIP3 tienen la misma tarifa para maker y taker: 0,1 %, 0,099 %, 0,098 % y 0,097 %. Recién a partir de VIP4 la columna maker empieza a separarse (0,095 % frente a 0,096 %).

El cálculo es directo. Si vendes 2 ETH a 2.000 USDT son 4.000 USDT de volumen; a 0,1 % de taker, la comisión es de 4 USDT. Y solo se cobra sobre la parte ejecutada: si tu orden se llena a medias, pagas sobre esa mitad.

Aquí entra el truco más fácil de aplicar sin cambiar de estrategia: activar el pago de comisiones con GT. No es un descuento enorme —baja el 0,1 % a 0,09 %, en la práctica un 10 % menos— pero se aplica desde el primer día, sin volumen previo. Requiere tener saldo en GT, porque si se agota el sistema vuelve automáticamente a la tarifa VIP estándar y tú no te enteras.

👉 [Abrir cuenta en Gate y revisar tus comisiones actuales](https://bit.ly/GateVIP)

## Futuros, opciones y productos que tienen su propia tarifa

En perpetuos, VIP0 paga 0,020 % maker y 0,050 % taker, independientemente del apalancamiento, porque la comisión se calcula sobre el valor de la posición y no sobre el margen inmovilizado. Abrir y cerrar es lo que cuesta; una orden cancelada no genera comisión.

Tres matices que suelen pasarse por alto:

1. **Las tarifas taker de futuros se pueden cubrir con puntos**, a una tasa fija del 0,075 % y con un mínimo combinado de 0,0225 %. Las comisiones maker, en cambio, no admiten puntos.
2. **El funding va aparte.** Se liquida cada 8 horas entre largos y cortos. En posiciones mantenidas varios días puede pesar más que las comisiones de entrada y salida juntas.
3. **El 1 de septiembre de 2026 cambió la estructura de los perpetuos con margen en USDT.** Los contratos TradFi (acciones, metales, índices, divisas y materias primas) pasaron a una estructura propia: maker entre 0,0000 % y 0,0200 % según nivel, taker entre 0,0120 % y 0,0500 %. Además arrancó una campaña de descuento en taker según cuota de volumen: 9 %, 16 % o 20 %.

También hay productos con comisión fija, sin escalones por VIP. Alpha se cobra al 0,8 % en todos los niveles, y las opciones se negocian alrededor del 0,03 %. En acciones, Gate viene ofreciendo comisión cero para acciones y ETF estadounidenses elegibles desde el 1 de agosto, aunque siguen aplicándose las tasas de liquidación y los cargos regulatorios de terceros; cuando ese programa termine, la estructura vuelve a ser escalonada y arranca en 0,1 %.

Antes de operar en un producto nuevo, mira la tarifa en la ventana de confirmación de la orden. Ahí aparece el número que realmente se te va a descontar, y no siempre coincide con lo que recuerdas de una guía.

## La tabla completa de niveles VIP: los 17 escalones

Esta es la estructura vigente en el sitio oficial. La columna de la izquierda es el requisito de volumen; la de la derecha, lo que pagas si además tienes activado el pago con GT.

| Nivel | Volumen 30 días (USD) | Comisión VIP (Maker/Taker) | Pagando con GT | Empezar |
| --- | --- | --- | --- | --- |
| VIP0 | 0 | 0,1 % / 0,1 % | 0,09 % / 0,09 % | [ Registrarme en Gate](https://bit.ly/GateVIP) |
| VIP1 | 60.000 | 0,099 % / 0,099 % | 0,089 % / 0,089 % | [ Ver requisitos del nivel](https://bit.ly/GateVIP) |
| VIP2 | 120.000 | 0,098 % / 0,098 % | 0,088 % / 0,088 % | [ Consultar tarifas](https://bit.ly/GateVIP) |
| VIP3 | 240.000 | 0,097 % / 0,097 % | 0,087 % / 0,087 % | [ Abrir cuenta](https://bit.ly/GateVIP) |
| VIP4 | 500.000 | 0,095 % / 0,096 % | 0,086 % / 0,086 % | [ Ver mi nivel](https://bit.ly/GateVIP) |
| VIP5 | 1.000.000 | 0,09 % / 0,095 % | 0,081 % / 0,085 % | [ Consultar tarifas](https://bit.ly/GateVIP) |
| VIP6 | 3.000.000 | 0,085 % / 0,09 % | 0,076 % / 0,081 % | [ Abrir cuenta](https://bit.ly/GateVIP) |
| VIP7 | 8.000.000 | 0,08 % / 0,085 % | 0,07 % / 0,076 % | [ Ver mi nivel](https://bit.ly/GateVIP) |
| VIP8 | 20.000.000 | 0,075 % / 0,08 % | 0,06 % / 0,072 % | [ Consultar tarifas](https://bit.ly/GateVIP) |
| VIP9 | 50.000.000 | 0,07 % / 0,075 % | 0,05 % / 0,068 % | [ Abrir cuenta](https://bit.ly/GateVIP) |
| VIP10 | 100.000.000 | 0,04 % / 0,058 % | — | [ Ver mi nivel](https://bit.ly/GateVIP) |
| VIP11 | 120.000.000 | 0,03 % / 0,045 % | — | [ Consultar tarifas](https://bit.ly/GateVIP) |
| VIP12 | 240.000.000 | 0,02 % / 0,037 % | — | [ Abrir cuenta](https://bit.ly/GateVIP) |
| VIP13 | 440.000.000 | 0,01 % / 0,03 % | 0,01 % / 0,03 % | [ Ver mi nivel](https://bit.ly/GateVIP) |
| VIP14 | 800.000.000 | 0,008 % / 0,023 % | — | [ Consultar tarifas](https://bit.ly/GateVIP) |
| VIP15 | 1.600.000.000 | 0 % / 0,02 % | 0 % / 0,02 % | [ Abrir cuenta](https://bit.ly/GateVIP) |
| VIP16 | 3.000.000.000 | 0 % / 0,0175 % | — | [ Ver mi nivel](https://bit.ly/GateVIP) |

Dos cosas que se leen entre líneas y conviene tener claras. Primero, el maker llega a 0 % recién en VIP15, así que "comisión cero" en Gate no es una tarifa de entrada. Segundo, el descuento por pagar con GT deja de existir en los niveles altos: a partir de VIP10 la tabla oficial ya no muestra una tarifa GT más baja, y en VIP13 ambas columnas son idénticas.

Además del volumen, el límite de retiros en 24 horas también sube con el nivel: 3.000.000 USD desde abajo, 5.000.000 en VIP5, 8.000.000 en VIP9, 10.000.000 en VIP12 y hasta 50.000.000 en VIP16.

## Cómo se sube de nivel (y por qué dos traders con el mismo volumen pagan distinto)

El nivel no depende solo del volumen. Gate aplica el criterio más favorable entre dos caminos: el volumen operado en los últimos 30 días o tu tenencia media diaria de GT en los últimos 14 días. Por eso hay gente con poca actividad que igual accede a tarifas mejores: sostener GT cuenta como si operaras.

El volumen, además, se pondera por producto:

- Spot (incluido Convert) y acciones: cuentan al 100 %.
- Perpetuos con margen en USDT, perpetuos con margen en BTC y entregas en USDT: al 40 %.
- Futuros en USD1 y opciones: al 20 %.
- CFD: al 10 %.

Traducido: si mueves un millón en futuros, no es lo mismo que mover un millón en spot. El sistema lo recalcula de forma automática y periódica, sin que tengas que solicitarlo. En VIP1 el requisito alternativo mencionado en la tabla oficial es de 50 GT de tenencia media; en VIP5 sube a 2.000 GT.

Hay un techo: VIP15 y VIP16 no están abiertos por volumen normal. La propia página indica que los usuarios VIP habituales no pueden ascender a esos niveles; se reservan para perfiles institucionales y, en la práctica, requieren gestión específica.

## Depósitos y retiros: donde no existe una tarifa fija

Depositar cripto en Gate es gratis como comisión de plataforma. No hay cargo por recibir activos. Lo que sí existe es el coste de red que pagaste en el exchange o la billetera de origen.

Retirar es otra historia. La comisión de retiro se fija por moneda y por red, y Gate la ajusta aproximadamente cada hora según la congestión de la cadena. No hay un "0,1 % de retiro": hay un número concreto para BTC por la red X y otro para USDT por TRC20. Aparece en la pantalla de retiro, junto al mínimo, antes de que confirmes.

Reglas prácticas que evitan sobrecostes:

- Elige la red con criterio, no por costumbre. Para USDT, las redes tipo TRC20, BEP20, Solana o TON suelen salir bastante más baratas que ERC20.
- Las transferencias internas entre cuentas de Gate (por UID, correo o GateCode) son gratuitas e instantáneas, pero solo sirven dentro de Gate.
- En varias jurisdicciones se aplica una restricción T+1: tras comprar cripto con dinero fiat, no puedes retirarla durante 24 horas.
- Los depósitos y retiros en fiat por tarjeta o transferencia bancaria dependen del proveedor y del país, así que la comisión que veas en España no tiene por qué ser la misma que en México o Argentina.
- El KYC es obligatorio para retirar. No hay nivel sin verificar.

## P2P: 0 % de comisión de plataforma, con el coste en otro lugar

En las operaciones P2P, la comisión de plataforma de Gate es del 0 %. Ni el comprador ni el vendedor pagan un porcentaje a Gate por el intercambio, algo que ya no es universal: otras plataformas introdujeron comisiones maker en P2P para algunos pares fiat.

Eso no significa que el P2P sea gratis. El coste real está en:

- **El spread.** El precio que publica el anunciante incluye un margen sobre el mercado, y en pares con poca liquidez ese margen puede ser amplio.
- **Los métodos de pago.** Banco, billetera electrónica o procesador pueden cobrar lo suyo, y varía por región.
- **La red.** Mover esos fondos fuera de Gate cuesta lo mismo que cualquier otro retiro.
- **La restricción T+1**, donde aplique.

Para comparar de verdad, suma el precio final que pagas por USDT y réstalo del precio spot del momento. Esa diferencia es tu comisión real, y en muchos casos sigue siendo competitiva frente a una compra con tarjeta.

## Cómo pagar menos sin operar más

Reducir comisiones no implica aumentar volumen. De hecho, la advertencia obvia: operar de más solo para subir de nivel suele costar más en pérdidas de mercado que lo que ahorras en tarifas.

Lo que sí funciona, en orden de esfuerzo:

1. Activar el pago de comisiones con GT. Es un ajuste en la configuración de comisiones, y el ahorro aplica desde la primera operación.
2. Usar órdenes limitadas cuando la estrategia lo permita. A partir de VIP4 la diferencia maker/taker se abre y deja de ser simbólica.
3. Revisar la red de retiro antes de confirmar. Un clic de diferencia puede ser un múltiplo del coste.
4. Mantener GT si vas a operar de forma sostenida. La ruta de tenencia media de 14 días es una alternativa real al volumen.
5. Agrupar movimientos internos en lugar de retiros on-chain cuando el destino sea otra cuenta de Gate.
6. Mirar los eventos VIP periódicos, que entregan mejoras de nivel o aceleradores sin exigir cambiar de estrategia.

Un punto de honestidad: para alguien que opera 1.000 USDT al mes en spot, todo el sistema VIP es irrelevante. Pagará 1 USDT por operación con o sin nivel, y su decisión debería girar en torno a las comisiones de retiro y al spread del P2P, no a la tabla de makers y takers.

## Preguntas frecuentes sobre las comisiones de Gate

**¿Cuánto cobra Gate por depositar cripto?**
Nada como comisión de plataforma. El coste de red lo asume quien envía los fondos desde fuera.

**¿Cuál es la comisión de trading más común?**
En spot, 0,1 % maker y 0,1 % taker en VIP0, o 0,09 % en ambos lados pagando con GT. En futuros perpetuos, 0,020 % maker y 0,050 % taker en el nivel base.

**¿Puedo pagar la comisión de futuros con puntos?**
Solo la parte taker, a una tasa fija de 0,075 %, con un mínimo combinado de 0,0225 %. Las comisiones maker no admiten puntos.

**¿El descuento con GT sirve en todos los niveles?**
No. Es útil en los niveles bajos y desaparece en los altos: desde VIP10 la tabla oficial ya no publica una tarifa GT inferior.

**¿Cuánto cuesta retirar USDT?**
Depende de la red que elijas y del momento. Gate ajusta la tarifa aproximadamente cada hora según la congestión, y el importe exacto aparece en pantalla antes de confirmar.

**¿Cuándo cambiaron las tarifas por última vez?**
La estructura global de comisiones spot y futuros se ajustó el 9 de abril de 2026, y el 1 de septiembre de 2026 se actualizaron los perpetuos con margen en USDT, con estructura independiente para los contratos TradFi. Por eso conviene verificar la tabla vigente antes de planificar operaciones grandes.

**¿Todas las cuentas pagan lo mismo?**
No. Además del nivel VIP, cuentan factores como el uso de API o el volumen institucional, que derivan a condiciones específicas.

Antes de abrir una posición seria, revisa tu tarifa real en la configuración de comisiones, porque es la única que se va a aplicar. Y si vienes de comparar exchanges, mira el conjunto: comisión de entrada, comisión de salida, funding si usas derivados y coste de retiro. La comisión más baja en la tabla no siempre es la cuenta más barata al final del mes.

👉 [Crear cuenta en Gate y consultar el cuadro de comisiones completo](https://bit.ly/GateVIP)
