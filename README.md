# Cpp2IL - Reverse Engineering for VRChat 🎮🔍

Welcome to the **Cpp2IL** repository! The Unity IL2CPP of the popular game **VRChat** allows developers to reverse engineer and analyze the game's assembly files. Whether you're a game developer, modder, or just curious about the internals of **VRChat**, the **Cpp2IL** repository provides the necessary resources.

## 📂 Overview of DLL Files

This repository contains a collection of .dll files extracted from the VRChat game. You can utilize these files with decompiler tools like **ILSpy**, **dnSpy**, and **DotPeek** to analyze the game's structure and functionality. Below is a list of the included .dll files:

| DLL File Name                  | Size     | Description                          |
|---------------------------------|----------|--------------------------------------|
| Assembly-CSharp-firstpass.dll   | 738KB    | Core assembly for first pass scripts. |
| Assembly-CSharp.dll             | 10.2MB   | Main assembly containing C# code for the game. |
| AVProVideo.Extensions.Timeline.dll | 3.00KB | Extensions for AVPro video timeline functionality. |
| ...                             | ...      | ... (Add more rows as needed)         |

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

## Credit

This repository leverages [Il2CppDumper-GUI](https://github.com/AndnixSH/Il2CppDumper-GUI) to dump .dll files from GameAssembly.dll and global-metadata.dat. If you're looking for a powerful tool for IL2CPP reversing, be sure to check it out.

Happy reversing! 🎉🔧
