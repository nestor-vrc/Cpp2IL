# Cpp2IL - Reverse Engineering for VRChat 🎮🔍

Welcome to the **Cpp2IL** repository! This tool is designed to **reverse engineer** the Unity IL2CPP toolchain used in the popular VRChat game, allowing developers to access and analyze the game's assembly files. Whether you're a game developer, modder, or just curious about the internals of VRChat, Cpp2IL provides the resources you need.

## 📂 Overview of DLL Files

This repository contains a collection of .dll files extracted from the VRChat game. You can utilize these files with decompiler tools like **ILSpy**, **dnSpy**, and **DotPeek** to analyze the game's structure and functionality. Below is a list of the included .dll files:

| DLL File Name | Size     | Description                          |
|---------------|----------|--------------------------------------|
| Assembly-CSharp-firstpass.dll | 757k    | Core assembly for first pass scripts. |
| Assembly-CSharp.dll | 11M      | Main assembly containing C# code for the game. |
| AVProVideo.Extensions.Timeline.dll | 3.6k    | Extensions for AVPro video timeline functionality. |
| ... | ... | ... (Add more rows as needed) |

*Note: The complete list of .dll files can be found in the root directory.*

## 🛠️ Usage

To use this repository, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/nestor-vrc/Cpp2IL.git
    cd Cpp2IL
    ```

2. **Choose your decompiler**:
   You can use any of the following tools for analysis:
   - [ILSpy](https://github.com/icsharpcode/ILSpy)
   - [dnSpy](https://github.com/dnSpy/dnSpy)
   - [DotPeek](https://www.jetbrains.com/decompiler/)

3. **Load DLLs into your decompiler**:
   Open your decompiler of choice and load the desired .dll file from the Cpp2IL repository.

4. **Analyze and explore**:
   Use the decompiler's features to navigate through the code, view class structures, and examine methods.

---

Happy reversing! 🎉🔧
