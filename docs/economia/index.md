---
title: El dinero
description: Cómo funciona el dinero en DemonCraft - dónde ver tu saldo, todas las formas de ganarlo, en qué se gasta y cómo pasar dinero a otro jugador.
---

# El dinero

<p class="dc-entradilla">Hay una sola moneda y no es un objeto: es tu <strong>banco</strong>. No ocupa sitio, no se cae, no te la pueden robar y no se pierde al morir.</p>

## Dónde ves tu saldo

- En la **K**, arriba a la derecha (en dorado) y en la pestaña **Perfil** → *Dinero*.
- En la lista de jugadores (++tab++): **«Bolsa»**.
- En las tiendas (*«Tu bolsa»*) y en el Mercado (*«tu saldo»*).

## Cómo se gana

| Fuente | Cuánto |
|---|---|
| **Tutorial** | 25.000 para tu primera casa. |
| **Misiones** (historia, Pilares, campañas, encargos) | Cada paso paga lo suyo: *«+X a tu banco»*. |
| **Recompensa nocturna** | Lo que cazas de noche, cobrado al amanecer. [Ver la noche](../mundo/noche.md). |
| **Encargos del día** | Entre 250 y 600 cada uno, y +600 si haces los tres. [Ver el tablón](../misiones/encargos.md#encargos-del-dia). |
| **Luna de Sangre** | 2.500 por ayudar a derrotar a la Luna Inferior. |
| **Cazar a un jugador demonio** con precio | 300 + 60 por cada punto de su notoriedad. |
| **Caja del Cuartel** | Una tirada gratis al día; a veces toca una bolsa de dinero. |
| **Mercado** | Lo que vendes a otros jugadores, menos un 5 %. |
| **Temporada del dojo** | 15.000 / 8.000 / 4.000 para los tres primeros del mes. |
| **Apuestas** en los duelos | Si aciertas, te repartes lo que pierden los demás. |

Con un **[rango VIP](../vip.md)** todo lo que paga el servidor (misiones, encargos, noche, Luna) es un **25 % más**.

!!! demonio "Si eres demonio"
    Tus misiones y tus encargos de la noche también pagan. No tienes recompensa nocturna, Luna de Sangre ni Caja del Cuartel.

## En qué se gasta

| Gasto | Precio |
|---|---|
| [Casa de alquiler](casas.md) | 20.000 cada 30 días |
| [Viajes](../mundo/viajar.md) en cuervo | 60 + 0,4 por bloque (máximo 1.200; VIP, la mitad) |
| [Tiendas](tiendas.md) | Comida, provisiones, muebles y materiales |
| [Reforja](../cazador/katana.md#si-pierdes-tu-katana-la-reforja) de tu katana | Desde 4.000 |
| [Equipo de la Aldea](aldea.md) | Prendas de 1.000 a 55.000, amuletos de 400 a 42.000, templar la katana de 1.000 a 15.000 |
| Fundar un [clan](../social/clanes.md) | 5.000 |
| Comisión del [Mercado](mercado.md) | 5 % de cada venta |

## ¿Puedo darle dinero a otro jugador?

**Sí, con `/pagar`.** El otro jugador tiene que estar conectado.

<ol class="pasos" markdown>
<li markdown>Escribe **`/pagar <jugador> <cantidad>`**, por ejemplo `/pagar Pepe 5000`.</li>
<li markdown>Te enseña el pago: *«Vas a pagar 5.000 a Pepe. Te quedarán 15.000.»* Todavía no se ha movido nada.</li>
<li markdown>Si está bien, pulsa **[✔ PAGAR]** en el chat (++t++ para abrirlo). Los dos lo veréis: *«Has pagado…»* y *«+5.000 · … te ha pagado»*.</li>
</ol>

Ten en cuenta:

- **Un pago no se puede deshacer.** Mira bien el nombre y los ceros antes de pulsar.
- El botón **vale una sola vez y durante un minuto**. Si caduca, vuelve a escribir la orden.
- Para pagar necesitas llevar **2 días de servicio**. No puedes pagarte a ti mismo ni pagar a alguien desconectado,
  en la pantalla de muerte o congelado por la moderación.
- Entre un pago y el siguiente hay que esperar 3 segundos.

!!! warning "Cuidado con los tratos"
    Si cambias algo por dinero, **págalo solo cuando tengas lo tuyo**. Si es un objeto, mejor véndelo en el
    [Mercado](mercado.md): allí nadie se queda sin pagar ni sin cobrar.

Otras formas de mover dinero:

- **El [Mercado](mercado.md):** véndele algo al precio que acordéis.
- **El tesoro del clan:** cualquier miembro aporta con `/clan tesoro aportar <cantidad>` y **solo el Fundador**
  retira con `/clan tesoro retirar <cantidad>`.
- Los objetos se pueden tirar con ++q++ para que otro los coja (salvo los ligados).

??? info "¿Y las monedas que tengo en el inventario?"
    Las monedas físicas no sirven para comprar en DemonCraft. Si entras con alguna, se convierten solas en saldo de tu
    banco: *«Se han guardado en tu banco X que llevabas encima»*.
