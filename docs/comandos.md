---
title: Comandos
description: Todos los comandos que puede usar un jugador en DemonCraft - cuenta, chat, clanes, duelos, mesas de juego, casas y parcelas, Mercado, VIP, entrenamiento, el Árbol de la Sangre, el Pase Estelar, las cajas y más.
---

# Todos los comandos

<p class="dc-entradilla">Casi todo se hace desde la K y hablando con los personajes. Estos son los comandos que puede usar cualquier jugador.</p>

!!! info "Si un comando no funciona"
    Los demás comandos están cerrados para los jugadores: *«✖ Ese comando no está disponible para jugadores. Todo lo que
    necesitas está en la K…»*. No hay `/spawn`, `/home` ni `/tpa`: se viaja con el [cuervo](mundo/viajar.md). Para pasar
    dinero a otro jugador, [`/pagar`](economia/index.md#puedo-darle-dinero-a-otro-jugador).

## Cuenta

| Comando | Qué hace |
|---|---|
| `/register <contraseña> <contraseña>` | Crear tu cuenta la primera vez (también `/reg`). |
| `/login <contraseña>` | Iniciar sesión (también `/l`). |
| `/changepassword <actual> <nueva>` | Cambiar tu contraseña (también `/cambiarclave`). |

## Chat y ayuda

| Comando | Qué hace |
|---|---|
| `/msg <jugador> <texto>` | Mensaje privado (también `/tell` y `/w`). |
| `/me <acción>` | Describir una acción en el chat. |
| `!<mensaje>` | Escribir solo a tu clan (no es un comando: empieza el mensaje por `!`). |
| `/report <jugador>` | Reportar a alguien (también `/reportar`). [Ver](social/chat.md#reportar-a-alguien) |
| `/discord` | Enlace al Discord. |
| `/list` · `/help` | Quién está conectado · ayuda. |
| `/voicechat join` · `invite <jugador>` · `leave` | Grupos del chat de voz. |
| `/skin set mojang <nombre>` · `/skin set web classic <enlace>` · `/skin clear` | Cambiar tu skin. |

## Tu personaje

| Comando | Qué hace |
|---|---|
| `/entrenar` | Abrir los entrenamientos del aliento. [Ver](cazador/entrenamiento.md) |
| `/bando` | Tu estado entre cazador y demonio, y lo que te falta para cambiar. [Ver](demonio/cura.md#el-comando-bando) |
| `/sangre` | Demonio: el Árbol de la Sangre (heredar y activar sangres). [Ver](demonio/artes.md#el-arbol-de-la-sangre) |
| `/cabezas` | Los cinco cazadores conectados cuya cabeza vale más para los demonios (300 + 60 por punto de fama). [Ver](demonio/combate.md#cabezas-con-precio) |
| `/botin` | Tu consigna: el botín que no te cupo en el inventario. Te dice qué te espera y te da lo que quepa. [Ver](economia/objetos.md#el-botin-que-no-te-cabe-la-consigna) |
| `/pase` | El Pase Estelar: tus niveles, lo que puedes recoger y los desafíos de la semana (también **K → ✦ Pase**). [Ver](pase.md) |
| `/caja` | La Caja del Cuartel desde donde estés (también **K → Caja**); si eres demonio, tu [Caja de Sangre](economia/objetos.md#la-caja-de-sangre-demonios). [Ver](economia/objetos.md#la-caja-del-cuartel-k-caja) |
| `/kohaku` | Llamar o despedir a Kohaku, el niño fantasma, si le protegiste sin caer en «El Colgante de las Almas». Va en lugar de tu mascota VIP. [Ver](misiones/colgante.md#kohaku-tu-companero) |

## Economía

| Comando | Qué hace |
|---|---|
| `/pagar <jugador> <cantidad>` | Pagar a otro jugador conectado: te enseña el pago y pulsas **[✔ PAGAR]**. [Ver](economia/index.md#puedo-darle-dinero-a-otro-jugador) |
| `/casa` | Tu casa: los días que te quedan, pagar más, tus compañeros. Junto a la placa de una casa, la tecla **I**. [Ver](economia/casas.md) |
| `/casa ver <casa>` · `/casa ir <casa>` | Ver una casa desde cualquier sitio · ir hasta su puerta con el cuervo |
| `/casa pagar <días>` · `/casa automatico si\|no` | Pagar días de tu casa · el pago automático |
| `/casa invitar <jugador>` · `aceptar` · `rechazar` | Vivir juntos (hasta 4 compañeros) |
| `/casa quitar <jugador>` · `/casa salir` · `/casa dejar` | Quitar a un compañero · irte de la casa en la que vives · dejar tu casa |
| `/casa pvp si\|no` | Poner o quitar el PvP dentro de tu casa (solo el inquilino). [Ver](economia/casas.md#pvp-en-tu-casa) |
| `/parcela` | Tu parcela para construir: lo mismo que `/casa` (`ver`, `ir`, `pagar`, `automatico`, `invitar`, `quitar`, `salir`, `dejar`, `pvp`…). [Ver](economia/casas.md#parcelas-para-construir) |
| `/parcela lista` · `/parcela obras <jugador> si\|no` | Las parcelas libres · dar o quitar a un compañero el permiso de obra |
| `/mercado` | Abrir el Mercado (también `/subastas`). [Ver](economia/mercado.md) |
| `/buy` | Abrir la tienda de rangos y extras. [Ver](vip.md) |

## Halloween 2026 (hasta el 1 de noviembre)

| Comando | Qué hace |
|---|---|
| `/halloween` | La pantalla del evento: el camino de las calabazas, la tienda de la Anciana y la clasificación (también **K → Halloween**). [Ver](eventos/halloween.md) |
| `/halloween sustos on` · `off` | Encender o apagar tus sustos. |

## Clanes

| Comando | Qué hace |
|---|---|
| `/clan fundar <etiqueta> <nombre>` | Fundar un clan (5.000). |
| `/clan invitar <jugador>` | Invitar (Pilar o Fundador). |
| `/clan aceptar` · `/clan rechazar` | Responder a una invitación. |
| `/clan salir` · `/clan disolver` | Dejar el clan · disolverlo (Fundador). |
| `/clan expulsar` · `ascender` · `degradar` · `traspasar <miembro>` | Gestionar miembros. |
| `/clan lema <texto>` · `/clan color <color>` | Lema y color de la bandera (Fundador). |
| `/clan tesoro aportar <cantidad>` · `retirar <cantidad>` | Tesoro (retirar solo el Fundador). |
| `/clan info [clan]` · `/clan lista` | Ficha de un clan · los 10 mejores. |

[Todo sobre los clanes](social/clanes.md)

## Duelos

| Comando | Qué hace |
|---|---|
| `/duelo retar <jugador>` | Retar a duelo. |
| `/duelo aceptar` · `/duelo rechazar` | Responder a un reto. |
| `/duelo rendirse` | Rendirte. |
| `/duelo apostar <duelista> <cantidad>` | Apostar (50 a 5.000). |
| `/duelo dojo` · `/duelo ver` | Pantalla del dojo · ver el combate desde la grada. |
| `/duelo top` · `/duelo marcador [jugador]` | Clasificación · marcador. |
| `/duelo trofeo` | Recoger tu Trofeo del Dojo. |

[Todo sobre los duelos](social/duelos.md)

## Mesas de juego

| Comando | Qué hace |
|---|---|
| `/ajedrez` · `/pulso` · `/dardos` | Cómo se juega cada uno. |
| `/ajedrez retar <jugador> [apuesta]` | Retar a quien tengas cerca, después de pinchar la mesa (igual con `/pulso` y `/dardos`). |
| `/ajedrez rechazar` · `cancelar` · `rendirse` | Rechazar un reto · retirar el tuyo · dejar la partida. |

[Todo sobre las mesas de juego](social/juegos.md)

## Rangos VIP

| Comando | Qué hace |
|---|---|
| `/vip info` | Tu rango, tus ventajas (también tu marca, si es un rango del Cuerpo) y cuándo te toca el próximo kit. |
| `/vip mascota` | Llamar o despedir a tu mascota. |
| `/vip mascota <cuál>` | Con varios rangos: elegir tu mascota (`koi`, `gorrion`, `lechuza`, `fenix`, `avelira`, `jabato`, `zorro`, `mariposa`, `farol`, `dragon`, `tren`, `brujula`, `nino`, `luna` o `ropa`). |
| `/vip titulo` | Con varios rangos: elegir el rango que enseñas (sobre tu cabeza, en el chat y en tu título). |
| `/kit` · `/kit <id>` | Ver tus kits · recoger el kit de tu rango (cada semana; el del Amanecer, cada mes). |

[Todo sobre los rangos VIP](vip.md)

## Teclas que hacen de «comando»

| Tecla | Qué abre |
|---|---|
| ++k++ | Tu perfil (la K). |
| ++j++ | Tu diario de misiones. |
| ++m++ | El mapa del mundo. |
| ++b++ | Tu mochila. |
| ++i++ | Junto a la placa de una casa o al cartel de una parcela: su pantalla. |
| ++v++ | El menú del chat de voz. |
| ++tab++ | La lista de jugadores. |

[Todas las teclas](empezar/controles.md)
