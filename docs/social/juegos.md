---
title: Mesas de juego
description: Ajedrez, pulso y dardos en DemonCraft - las mesas en 3D, cómo retar a otro jugador, las apuestas, cómo se juega cada uno y qué corta una partida.
---

# Mesas de juego

<p class="dc-entradilla">Ajedrez, pulso y dardos contra otro jugador, en 3D y sentados a la mesa. Con apuesta o sin ella: quien gana se lleva las dos.</p>

## Las mesas

| Mesa | Dónde va | Precio |
|---|---|---|
| **Mesa de Ajedrez** | En el suelo (2 × 4 bloques), con un cojín a cada lado. | 9.000 |
| **Mesa de Pulso** | En el suelo (1 × 3 bloques), con dos taburetes. | 6.000 |
| **Diana de Dardos** | En la pared (2 × 2 bloques). Se tira desde tres bloques por delante. | 7.000 |

Se compran en la tienda de Kohei (estantería **Muebles → Juegos**) y se ponen como cualquier
[mueble](../economia/tiendas.md#los-muebles-japoneses), en tu casa o tu parcela. Puedes jugar en la tuya o en la de otro.

## Retar

<ol class="pasos" markdown>
<li markdown>**Haz clic derecho en la mesa.** En el chat salen, como botones, los jugadores que tienes cerca.</li>
<li markdown>**Elige a tu rival y la apuesta**: sin apuesta o de 100 a 25.000 (solo salen las que te puedes permitir).</li>
<li markdown>**Tu rival acepta** con **[✔ ACEPTAR]** en el chat (o con un clic a la mesa) antes de 60 segundos. Cada uno va a su sitio y empieza la partida.</li>
</ol>

También por comando, después de pinchar la mesa: `/ajedrez retar <jugador> [apuesta]` (o `/pulso`, `/dardos`).
`/ajedrez` a secas te explica cómo se juega.

## Las apuestas

- Los dos ponéis **lo mismo** y quien gana **se lleva las dos**, sin comisión. En tablas, o si la partida se corta sin culpa
  de nadie, cada uno recupera lo suyo.
- Entre **100 y 25.000** cada uno. Para apostar, los dos necesitáis **2 días de servicio**, como para
  [`/pagar`](../economia/index.md#puedo-darle-dinero-a-otro-jugador).
- Desde la misma conexión (dos de la misma casa) se puede jugar, pero sin apuesta.

## El ajedrez

- Las reglas de siempre (enroque, al paso, coronar, ahogado, tablas por repetición…), con **reloj**: 5 minutos cada uno y
  3 segundos más por jugada. A quien se le acaba, pierde (si el otro ya no puede dar mate, tablas).
- **Se juega sobre el tablero 3D**: clic a una figura tuya (se levanta y se marcan sus casillas: un punto verde donde puede
  ir, un aro rojo si come) y clic a la casilla, o arrástrala. Al coronar eliges la figura.
- Verás cómo tu mano lleva la figura a su casilla y cómo lo comido salta a la bandeja de quien come.
- En pantalla, los relojes, lo comido y la ventaja de cada uno y las jugadas. **Tablas** con su botón (el otro tiene que
  aceptarlas) y ++esc++ para rendirte. ++c++ cambia la cámara (detrás o desde arriba) y la rueda la acerca o la aleja.

## El pulso

- Tras la cuenta atrás (3 · 2 · 1 · ¡YA!), **clica sin parar** con el clic izquierdo: el brazo se inclina hacia quien menos
  fuerza hace. Clicar antes del ¡YA! es **salida nula** y le da ventaja al otro.
- Cuenta lo deprisa que clicas, con un tope: un autoclic no gana más. Al borde de perder empujas algo más fuerte: hay
  remontadas.
- De vez en cuando sale una **tecla de fuerza** (++w++, ++a++, ++s++ o ++d++) con un anillo de tiempo: el primero que la
  acierta da un tirón. Si pulsas la que no es, ya no puedes probar.
- Como mucho **45 segundos**: gana quien tenga el brazo de su lado; si está casi en medio, tablas.

## Los dardos

- Al **301**: tres dardos por turno y gana quien llega a **cero justo**. Si te pasas, pierdes el turno y vuelves a lo que
  tenías. Como mucho siete rondas: después gana quien menos tiene. Tienes 25 segundos para cada dardo (si no tiras, cuenta
  como fuera).
- **Es difícil a propósito**: la mano no se está quieta. **Contén la respiración** (clic derecho o ++space++) y tiembla mucho
  menos, pero el aire se acaba en 2,5 segundos y tarda 5,5 en volver.
- **La fuerza**: mantén el clic izquierdo y la barra sube y baja; **suelta en la marca dorada**. Si te quedas corto, el dardo
  cae; si te pasas, sube; lejos de la marca, se abre.
- Cada dardo marca lo que vale donde se clava («T20 · 60», «¡DIANA! 50», «FUERA») y la pizarra te dice cuánto te falta.

## Mientras juegas

- **Estás a salvo**: nada te ataca y no te salen demonios de la noche. Tampoco hay duelos ni entrenamientos.
- La ++t++ abre el chat sin dejar la partida.
- **Pierdes** si te levantas o te vas de tu sitio, sales del servidor o mueres. Si la mesa desaparece o se apaga el servidor,
  la partida se corta y cada uno recupera lo suyo.
- Al acabar ves el resultado (VICTORIA, DERROTA o TABLAS, con lo que ganas o se devuelve) y te levantas solo.
- Quien mira ve la partida en 3D y un letrero sobre la mesa con los dos jugadores.
- En plena pelea con otro jugador (con la [marca de combate](../cazador/combate.md#la-marca-de-combate)) no se juega.

## Comandos

| Comando | Qué hace |
|---|---|
| `/ajedrez` · `/pulso` · `/dardos` | Cómo se juega cada uno. |
| `/ajedrez retar <jugador> [apuesta]` | Retar a quien tengas cerca (después de pinchar la mesa). Igual con `/pulso` y `/dardos`. |
| `/ajedrez rechazar` · `/ajedrez cancelar` | Rechazar el reto que te han hecho · retirar el tuyo. |
| `/ajedrez rendirse` | Dejar la partida (pierdes y, si hay apuesta, la cobra el otro). |
