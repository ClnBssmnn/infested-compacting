# Infested Stone Compacting

A tiny Fabric mod for Minecraft 1.20.1 that adds a Create compacting recipe:

**4x Infested Stone → Stone Bricks + Experience Nugget**

Using a Mechanical Press over a Basin.

---

## How to build the jar

### Requirements
- Java 17 (JDK) installed

### Steps

1. Open a terminal in this folder
2. Run:

**On Linux/Mac:**
```bash
chmod +x gradlew
./gradlew build
```

**On Windows:**
```
gradlew.bat build
```

3. The jar will appear at:
```
build/libs/infested-compacting-1.0.0.jar
```

4. Drop that jar into your `mods/` folder alongside Create. Done!

---

## Dependencies (on the server/client)
- Fabric Loader
- Fabric API
- Create (Fabric edition) for 1.20.1
