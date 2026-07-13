# Mov's More Recipe

A lightweight mod for **Forge 1.20.1** that adds a handful of useful, survival‑friendly recipes.  
All recipes work directly in the **2×2 inventory crafting grid** – no crafting table required.

---

## 📦 Recipes

| Input | Output |
| :--- | :--- |
| Coal ×1 | Black Dye ×1 |
| Nether Quartz ×1 | White Dye ×1 |
| Quartz Block ×1 | Nether Quartz ×4 |
| Diamond ×1 | Cyan Dye ×8 |
| Copper Ingot ×4 *(Shaped 2×2)* | Orange Dye ×16 |
| Redstone ×1 | Red Dye ×2 |

---

## 🛠️ Development Setup

This project is built with the Forge 1.20.1 MDK.

### Prerequisites
- **JDK 17** or higher (JDK 21 is fully compatible)
- **IntelliJ IDEA** (recommended) or Eclipse

### Importing into IntelliJ IDEA
1. Clone or download this repository.
2. In IDEA, select `File` → `Open` and choose the **`build.gradle`** file.
3. Wait for IDEA to sync and download all dependencies (this may take a few minutes the first time).
4. In the Gradle tool window, navigate to `Tasks` → `forgegradle runs` → `runClient`, then double‑click to start the game and test your mod.

### Troubleshooting
- **Slow or failed dependency downloads**: Add a fast mirror (e.g., Aliyun Maven) to the `repositories` block in `build.gradle`.
- **Java 17 not found**: Make sure JDK 17 or 21 is installed and properly set in IDEA's `Project Structure` → `SDK`.

---

## 📜 Mapping Names

This project uses **official Mojang mappings** by default.  
Please review the [Mojang mapping license](https://github.com/MinecraftForge/MCPConfig/blob/master/Mojang.md) before redistributing or modifying the mod.

---

## 🔗 Links

- [Forge Documentation](https://docs.minecraftforge.net/en/1.20.1/)
- [Modrinth Project Page](https://modrinth.com/project/your-project-slug) *(Replace with your actual URL)*

---

## 📝 License

All Rights Reserved.  
*(You can change this to MIT, GPL, or any other open‑source license if you prefer.)*
