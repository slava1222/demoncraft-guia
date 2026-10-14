---
title: Casas de alquiler
description: Cómo alquilar una casa en DemonCraft, cuánto cuesta, cómo pagar más días, vivir con otros jugadores y qué pasa si se acaba lo pagado.
---

# Casas de alquiler

<p class="dc-entradilla">Tu casa es el único sitio del mapa donde puedes construir, decorar y guardar cosas en cofres. El tutorial te da el dinero para la primera.</p>

## La placa de la puerta

Cada casa tiene junto a la puerta una **placa de madera**. Si está libre, lleva colgada una tira de papel roja y dice
**«SE ALQUILA»**, el nombre de la casa y su precio; si está alquilada, dice **de quién es** (y con quién vive).

<div class="galeria" markdown>
<figure markdown="span">
  ![Placa de una casa libre: SE ALQUILA](../assets/img/capturas/casa-placa-libre.webp){ loading=lazy }
  <figcaption>Una casa libre: «SE ALQUILA», su nombre y su precio.</figcaption>
</figure>
<figure markdown="span">
  ![Placa de una casa alquilada](../assets/img/capturas/casa-placa-alquilada.webp){ loading=lazy }
  <figcaption>Una casa alquilada: el nombre de quien vive en ella.</figcaption>
</figure>
</div>

Acércate a la placa y pulsa **I** (o haz clic derecho en ella): se abre la **pantalla de la casa**. Desde cualquier sitio,
`/casa ver <casa>`.

## Cómo se alquila

1. Busca una casa con la placa de **«SE ALQUILA»**. Cuando una queda libre, el chat lo avisa con dos botones:
   **[Ver la casa]** e **[Ir con el cuervo]**.

    ![Aviso de casa libre en el chat](../assets/img/capturas/casa-libre-chat.webp){ loading=lazy }

2. Ponte en la casa o junto a su placa y pulsa **I**.
3. Elige cuántos días (**7, 15 o 30**), mira lo que cuesta y lo que te quedará, y pulsa **Alquilar**. Te pide confirmar.

<figure markdown="span">
  ![La pantalla de una casa libre](../assets/img/capturas/casa-alquilar.webp){ loading=lazy }
  <figcaption>Una casa libre: su precio, lo que cuesta al día y los días que quieres pagar.</figcaption>
</figure>

- **20.000 cada 30 días reales** (667 al día). Son días del calendario: cuentan también mientras no juegas.
- Solo **una casa** por jugador (la tuya o la de alguien con quien vives).

## Pagar más días

En la pantalla de tu casa (pulsa **I** dentro de ella o junto a su placa, o escribe **`/casa`** desde cualquier sitio) ves
cuántos días te quedan y puedes **pagar +1, +7 o hasta el máximo**: como mucho, **30 días pagados por delante**. También con
`/casa pagar <días>`.

<figure markdown="span">
  ![La pantalla de tu casa](../assets/img/capturas/casa-tuya.webp){ loading=lazy }
  <figcaption>Tu casa: los días que quedan, pagar más días, el pago automático y tus compañeros.</figcaption>
</figure>

- Con el **pago automático** (viene puesto), si se acaba lo pagado mientras estás conectado, se cobra solo. Se quita con
  `/casa automatico no`.
- Con 3 días o menos pagados te avisa al entrar.

## Si se acaba lo pagado

No la pierdes en ese momento: tienes **3 días de mora**. La casa sigue siendo tuya, al entrar te avisa en rojo de lo que
debes y, con el pago automático y dinero, se cobra sola al conectarte. Pasados esos 3 días, la casa vuelve a como estaba y
queda libre. **Lo tuyo no se pierde**: lo que colocaste, los marcos, el trofeo y el contenido de los cofres van a tu
**buzón del Mercado** (K → Subastas → Buzón).

## Vivir con otros jugadores

- **`/casa invitar <jugador>`**: le llega una invitación con **[✔ Aceptar]** y **[✖ Rechazar]** (tiene 2 minutos). Hasta
  **4 compañeros**.
- Tus compañeros **abren los cofres, colocan y quitan lo suyo y pagan días**. Solo tú invitas, quitas (`/casa quitar <jugador>`)
  y dejas la casa.
- Un compañero se va con **`/casa salir`**; lo que colocó se queda en la casa.
- Al acabar el alquiler, lo que puso cada uno vuelve a **su** buzón.

## La casa de otro jugador

Si abres la placa de una casa alquilada ves la **ficha de quien vive allí**: su rango, su título, su clan, si está conectado,
su puntuación en el **Dojo** y los demonios y jefes que ha cazado. Desde ahí puedes **retarle a duelo**.

<figure markdown="span">
  ![La ficha del inquilino](../assets/img/capturas/casa-ficha.webp){ loading=lazy }
  <figcaption>La casa de otro: su ficha y su puntuación en el Dojo.</figcaption>
</figure>

## Qué puedes hacer dentro

- **Colocar bloques** y quitar los que pusiste tú. El edificio en sí no se desmonta.
- Poner y usar **cofres, barriles, hornos**, mesa de trabajo, yunque y afiladora: **solo funcionan en la casa en la que vives**.
- Colgar **cuadros y marcos**, poner **soportes de armadura** y colocar tu **Trofeo del Dojo**.
- Los demás pueden entrar (las puertas funcionan para todos), pero **no tocan nada**.
- No se pueden usar cubos de agua ni de lava.

## Dejar la casa

**`/casa dejar`** (o el botón **Dejar la casa**): lo de dentro va a los buzones y la casa queda libre para otro.
**No se devuelve lo pagado.**
