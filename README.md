# ZOrk-Text-Game-C++
A C++ text-based adventure game inspired by classic Zork. Navigate through 10+ rooms, interact with objects, unlock doors using keys, and manage an inventory. Features include look, take, drop, and use commands, with logical item interactions and room-based progression.
# ZOOrk Adventure Game – C++ Text-Based Game

A console-based interactive text adventure game inspired by classic Zork. Built using object-oriented programming in C++, the game allows players to explore over 10 rooms, collect and use items, and unlock restricted areas with specific keys.

---

## 🚀 Features

- 🔁 **10+ Navigable Rooms**: Explore an interconnected map with meaningful room-to-room progression.
- 🧭 **Directional Movement**: Move using commands like `go north`, `go south`, etc.
- 🗺️ **Room Descriptions**: Use the `look` or `inspect` command to view the current room and its items.
- 🧰 **Inventory System**: Take and drop items using `take <item>` and `drop <item>`. View your inventory with the `inventory` command.
- 🔐 **Key-Lock Mechanism**: Certain rooms (e.g., **Basement**, **Tool Shed**, **Bedroom**, **Gate**) are locked and require specific keys to unlock using the `go` command.
- 🧪 **Use Command**: Interact meaningfully with collected items via `use <item>` (e.g., `use knife`, `use torch`).
- 💬 **Dynamic Feedback**: Actions provide immersive console-based responses.

---

## 🧱 Tech Stack

- **Language**: C++
- **OOP Concepts**: Inheritance, composition, and encapsulation
- **Core Classes**:
  - `ZOOrkEngine`: Manages game loop and command handling
  - `Room`, `Passage`, `Item`, `Player`, `Location`, `GameObject`

---
