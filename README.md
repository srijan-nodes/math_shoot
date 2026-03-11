JUSt a stupid game to enjoy simple keyboard plus trackpad focused controls for playabilty in classes 
hold down ctrl to aim and shift to increase zoom


now the chatgpt readme:
# Math Shoot

A browser-based **3D FPS sandbox game** built with **Three.js** where survival depends on both combat skills and algebra.

Fight enemies in a procedurally generated city, collect weapons, manage ammo reserves, and solve algebra problems to revive after death.

The game combines classic arcade shooter mechanics with an educational twist.

---

# Features

* First-person and third-person camera modes
* Multiple weapons with different mechanics
* Grenades and explosive damage
* Procedurally generated city with enterable buildings
* Elevators to access rooftops
* Enemy AI (rushers and campers)
* Ammo reserve system
* Inventory management
* Weapon pickups across the city
* Algebra-based revive system after death

---

# How to Run

Simply open the game in a browser:

```
open index.html
```

or double-click the file.

No installation required.

---

# Controls

## Movement

| Key       | Action        |
| --------- | ------------- |
| **W**     | Move forward  |
| **A**     | Move left     |
| **S**     | Move backward |
| **D**     | Move right    |
| **Space** | Jump          |

---

## Combat

| Key / Mouse     | Action        |
| --------------- | ------------- |
| **Left Click**  | Shoot         |
| **Right Click** | Aim           |
| **R**           | Reload weapon |
| **F**           | Throw grenade |

Automatic weapons will continue firing while holding the trigger.

---

## Weapon Management

| Key   | Action              |
| ----- | ------------------- |
| **1** | Equip weapon slot 1 |
| **2** | Equip weapon slot 2 |
| **3** | Equip weapon slot 3 |
| **G** | Drop current weapon |

Inventory supports **up to 3 weapons**.

Picking up a weapon already in inventory gives **extra ammo reserves**.

---

## Camera & Aiming

| Key                      | Action                                  |
| ------------------------ | --------------------------------------- |
| **C**                    | Toggle First-person / Third-person view |
| **Right Click**          | Aim down sights                         |
| **Shift (while aiming)** | Zoom                                    |

---

## Interaction

| Key   | Action                       |
| ----- | ---------------------------- |
| **E** | Use elevator                 |
| **E** | Heal using money when low HP |

Health packs are automatically purchased if your health becomes critically low and you have enough cash.

---

# Weapons

| Weapon      | Description                   |
| ----------- | ----------------------------- |
| **Pistol**  | Balanced starter weapon       |
| **SMG**     | Fast automatic weapon         |
| **Shotgun** | High damage at close range    |
| **Rifle**   | Medium range automatic weapon |
| **Sniper**  | Long range high damage weapon |

Each weapon uses:

```
Magazine Ammo / Reserve Ammo
```

Reload transfers ammo from reserves to the magazine.

---

# Enemies

Two enemy types exist:

### Rushers

* Fast melee attackers
* Charge directly toward the player

### Campers

* Stay on rooftops
* Shoot at long range

---

# Grenades

Grenades explode after a short delay and deal **area damage** to nearby enemies.

---

# Death & Revival

When the player dies:

1. A **WASTED** screen appears
2. A **random algebra equation** is generated
3. Solve for **x** to revive

Example:

```
2x + 5 = 15
```

Correct answer revives the player with full health.

---

# HUD Elements

Top UI shows:

* **HP** – Player health
* **Weapon inventory**
* **Magazine ammo / reserve ammo**
* **Grenade count**
* **Cash**

---

# Technologies Used

* **Three.js**
* **JavaScript**
* **HTML5 / WebGL**

---

# Author

Srijan Das
