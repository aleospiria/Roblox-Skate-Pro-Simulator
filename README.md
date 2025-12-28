# 🛹 Skate Pro Simulator

> **Roblox Incremental / Progression Skateboarding Game**

Skate Pro Simulator es un juego de progresión incremental en Roblox centrado en **skateboarding**, donde el jugador aumenta su **Velocidad** de forma constante simplemente patinando.

El juego se basa en una progresión de números cada vez mayores, circuitos progresivamente más exigentes y mundos que requieren velocidades absurdamente altas para ser completados, creando un ciclo de progreso continuo y altamente adictivo.

---

## 🎮 Concepto general

El jugador comienza con un skate básico y una **velocidad extremadamente baja**, apenas suficiente para moverse.  
Cada **paso realizado sobre la skate** incrementa la **Velocidad** del jugador en **+1**, haciendo que, con el tiempo, se mueva cada vez más rápido.

### Al inicio:
- El movimiento es lento
- Los saltos son cortos
- Completar el circuito parece imposible

### Conforme el jugador patina:
- La velocidad aumenta de forma constante
- Los saltos se vuelven más largos
- El circuito se vuelve cada vez más fácil

Al completar secciones del circuito y alcanzar **checkpoints**, el jugador obtiene **Victorias**, que funcionan como la moneda principal del juego.

---

## 🧠 Filosofía del diseño

Este juego **no busca realismo**, sino progresión exagerada:

- Números grandes = progreso satisfactorio
- Mundos nuevos = reinicio relativo de dificultad
- La misma velocidad puede sentirse:
  - Muy alta en un mundo
  - Ridículamente baja en el siguiente

Esto permite escalar el juego indefinidamente sin romper la experiencia.

---

## 🔁 Gameplay Loop

```
Patinar
   ↓
Ganar +Velocidad por cada paso
   ↓
Moverse y saltar más lejos
   ↓
Alcanzar checkpoints del circuito
   ↓
Ganar Victorias
   ↓
Comprar Mascotas / Skates
   ↓
Aumentar la ganancia de Velocidad
   ↓
Completar el circuito más fácilmente
   ↓
Desbloquear mundos más difíciles
↺
```

---

## 🧠 Mecánicas principales

### 🛹 Movimiento y Velocidad

- **Velocidad** es la estadística principal del juego
- Cada paso realizado sobre la skate otorga: +1 Velocidad


La velocidad afecta directamente:
- Rapidez de desplazamiento
- Distancia de salto
- Facilidad para completar el circuito

No existen penalizaciones por caer:
- Caer **no reduce la velocidad**
- El progreso nunca se pierde
- El juego premia la persistencia

---

## 🛣️ Mapas / Circuitos

- Circuitos lineales con rampas, gaps y checkpoints
- Cada circuito tiene:
- Una velocidad mínima recomendada
- Checkpoints progresivos
- A mayor velocidad:
- Más fácil completar el circuito
- Más checkpoints alcanzados

---

## 🏆 Victorias (Moneda principal)

Las **Victorias** representan el progreso dentro de los circuitos.

### Obtención
- Alcanzar checkpoints
- Completar el circuito completo

### Ejemplo
- 1er checkpoint → **+1 Victoria**
- 2 checkpoints → **+2 Victorias**
- Circuito completo → **+5 Victorias**

Las Victorias se usan para:
- Comprar mascotas
- Comprar nuevas tablas
- Desbloquear nuevos mundos
- Progresión futura (Rebirths)

---

## 🐾 Sistema de Mascotas

### Equipamiento
- Máximo **3 mascotas equipadas**
- Las mascotas **multiplican la velocidad ganada por paso**

### Compra
- Se compran con Victorias
- Mascota inicial:
- Costo: **3 Victorias**

### Rarezas

| Rareza    | Multiplicador |
|-----------|---------------|
| Common    | x1.2          |
| Rare      | x1.5          |
| Epic      | x2.0          |
| Legendary | x3.0          |

> **Futuro:** fusión, evolución y mascotas exclusivas por Rebirth

---

## 🛹 Tablas de Skate

Las tablas funcionan como mejoras de progresión.

### Función
- Multiplican las **Victorias obtenidas**
- No afectan la velocidad directamente

### Ejemplo
- **Skate inicial**
- Victorias: x1.0

- **Segundo skate**
- Costo: **10 Victorias**
- Victorias: **x1.5**

> En el futuro podrán existir tablas exclusivas o cosméticas.

---

## 🌍 Mundos

- Cada mundo tiene:
- Circuitos más largos
- Saltos más exigentes
- Requisitos de velocidad mucho mayores

Aunque el jugador conserva su velocidad:
- En un mundo nuevo, esa velocidad se siente nuevamente lenta
- Se reinicia la sensación de progreso sin borrar estadísticas

---

## 📈 Progresión del jugador

### Inicio
- Velocidad muy baja
- Progreso rápido
- Circuito desafiante

### Medio
- Velocidad alta
- Circuitos cada vez más fáciles
- Optimización de mascotas y tablas

### Tardío
- Velocidades absurdas
- Mundos desbloqueados

---

## 🧪 MVP (Primera versión jugable)

✔ 1 mundo  
✔ 1 circuito  
✔ 1 stat principal (Velocidad)  
✔ Sistema básico de Victorias  
✔ Mascotas básicas  

---

