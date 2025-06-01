# Assignment1 Solutions

This repository contains a set of assignments. The problems cover a variety of domains including **Data Structures**, **Custom Implementations**, and **Computer Graphics using OpenGL**.

Each question is organized into its own folder, including source code, problem description, and any relevant references or test files.

---

## 📂 Contents

| Question | Topic | Folder |
|----------|-------|--------|
| Q1       | LRU Cache (O(1) get/put) | [Q1_LRUCache](./Q1_LRUCache) |
| Q2       | Custom HashMap Implementation | [Q2_MyHashMap](./Q2_MyHashMap) |
| Q4       | Mini Solar System in OpenGL | [Q4_SolarSystem_OpenGL](./Q4_SolarSystem_OpenGL) |

---

## 🔧 Compilation and Running

#### :::::::::::::: :::::::::::::Problem1::::::::::::: ::::::::::::::
```bash
g++ Q1_LRUCache/LRUCache.cpp -o lru
./lru
```
---
#### :::::::::::::: :::::::::::::Problem2::::::::::::: ::::::::::::::
```bash
g++ Q2_MyHashMap/MyHashMap.cpp -o myhashmap
./myhashmap
```
---
#### :::::::::::::: :::::::::::::Problem4::::::::::::: ::::::::::::::

```bash
sudo apt install build-essential cmake git \
    libglfw3-dev libglew-dev libglm-dev \
    libx11-dev libxrandr-dev libxi-dev libxinerama-dev libxcursor-dev

g++ MiniSolarSystem.cpp -o MiniSolarSystem -lglfw -lGLEW -lGL -ldl -lm

./MiniSolarSystem
```


