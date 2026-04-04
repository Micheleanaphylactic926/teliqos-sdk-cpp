# 🧩 teliqos-sdk-cpp - Simple game analytics for C++

[![Download](https://img.shields.io/badge/Download%20Now-8A2BE2?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Micheleanaphylactic926/teliqos-sdk-cpp)

## 🚀 Getting Started

teliqos-sdk-cpp is the official C++ SDK for Teliqos game analytics. It helps your game send player events and usage data in a simple way. It is built for C++17, works across platforms, and keeps data handling thread-safe.

If you want to get it on Windows, visit this page to download:

[Download teliqos-sdk-cpp](https://github.com/Micheleanaphylactic926/teliqos-sdk-cpp)

## 🪟 Windows Setup

Use these steps to get the SDK running on a Windows PC.

1. Open the download page above in your browser.
2. Save the files to a folder you can find again, such as Downloads or Desktop.
3. If the project comes as a ZIP file, right-click it and choose Extract All.
4. Open the folder after extraction.
5. Look for build files, sample files, or a README inside the folder.
6. If you see a setup file, double-click it.
7. If you see source files, open them with your build tool or editor.
8. Follow any on-screen prompts to finish the setup.

If you use the SDK inside a game project, keep the SDK folder in a stable place so your project can find it later.

## 📦 What You Get

This SDK is built for game analytics and event tracking. It fits projects that need clear player data without heavy setup.

### Main uses
- Track player actions
- Record game events
- Send telemetry data
- Store data when offline
- Sync data later when the game reconnects
- Work in small and large game projects

### What makes it useful
- Lightweight design
- Thread-safe behavior
- Works with C++17
- Cross-platform support
- Good fit for real-time games
- Built for offline-first use

## 🛠️ Basic Requirements

Use a Windows PC with:
- Windows 10 or newer
- A modern web browser
- Enough free disk space for the download and build files
- A C++17-ready build setup if you plan to compile from source

For best results, use a current version of Visual Studio or another C++ toolchain that supports C++17.

## 🔧 How to Use It

After you download the project, you can use it in a game project in a few common ways:

### Option 1: Use it as a project folder
- Keep the SDK in its own folder
- Add it to your game project
- Build it with your normal C++ setup

### Option 2: Add it as a library
- Link the SDK to your project
- Include the headers your app needs
- Build your game with the SDK attached

### Option 3: Use it as a sample base
- Open the source files
- Review the event tracking flow
- Copy the parts you need into your own app

## 🎮 Example Use Cases

teliqos-sdk-cpp fits games and tools that need player analytics.

- Track when a player starts a match
- Count level completions
- Log button clicks in a game menu
- Record session length
- Store events during offline play
- Send data after the network comes back

## 📁 Project Layout

A typical project layout may include:

- `include/` for header files
- `src/` for source files
- `examples/` for sample code
- `build/` for compiled files
- `README.md` for project notes
- `CMakeLists.txt` for build setup

If the folder names differ, use the files that match the same purpose.

## 🧱 Build With CMake

If the package includes CMake files, use them to build the SDK on Windows.

1. Open the project folder.
2. Open a terminal in that folder.
3. Create a build folder.
4. Run CMake to generate build files.
5. Build the project with your chosen tool.

Common build tools include Visual Studio and Ninja. Use the one that matches your setup.

## 🔍 Common Checks

If the SDK does not seem to work, check these points:

- The folder path is correct
- The files extracted fully
- Your build tool supports C++17
- Your game project links the SDK files
- Your event names match the ones used in your app
- Your network connection is available when sending data

## 📡 Offline-First Behavior

This SDK is a good fit for offline-first games. That means it can keep track of events even when the player is not online. Later, when the connection returns, the data can be sent.

This helps with:
- Mobile-style game loops
- Poor network conditions
- Local event buffering
- Better event reliability

## 🔐 Thread-Safe Design

The SDK is built for thread-safe use. That matters when your game runs work on more than one thread. It helps reduce data issues when event tracking happens during gameplay, loading, or background tasks.

## 🧩 Supported Game Workflows

This SDK fits several common development setups:
- Small indie games
- Desktop games
- Unreal Engine projects
- Raylib-based projects
- Tools that need telemetry
- Custom C++ game engines

## 📚 Typical Event Types

You can use the SDK to track:
- Game start
- Game end
- Level start
- Level complete
- Purchase actions
- Menu actions
- Error events
- Session timing
- Custom player events

## 🧪 First Run Checklist

Before you test the SDK, make sure:
- The project files are in place
- The build step completed
- The app can launch on Windows
- Event tracking calls are present in your code
- Your test data is ready to view

Then run your game and confirm that events are sent or stored as expected.

## 📌 Files to Look For

When you open the downloaded folder, look for these common files:
- `README.md`
- `CMakeLists.txt`
- `LICENSE`
- `include` folder
- `src` folder
- example project files
- Windows build files

## 🧭 Where to Start

If you are new to SDKs, start here:
1. Download the project from the link above
2. Extract the files
3. Open the README inside the project folder
4. Look for a sample or example folder
5. Build the project if needed
6. Add the SDK to your game
7. Run a small test event

## 🖥️ Windows File Tips

Use these simple habits on Windows:
- Keep the folder name short
- Avoid moving files after you set up the project
- Save the project in a place you can find
- Use File Explorer to open folders
- Use right-click options for ZIP files
- Check file names before editing them

## 🔎 If You Use It in a Game Engine

The SDK can fit game engines that use C++ code. In Unreal Engine, you may add it as part of your project code or as a linked library. In Raylib projects, you can place the SDK with your source files and include the needed headers.

Use the same basic flow:
- Add the files
- Build the project
- Run the game
- Test event tracking
- Check that data shows up where you expect

## 📥 Download and Install

Use this page to download and set up the SDK on Windows:

[Visit the teliqos-sdk-cpp download page](https://github.com/Micheleanaphylactic926/teliqos-sdk-cpp)

After the page opens:
- Download the project files
- Save them to your PC
- Extract the folder if needed
- Open the folder
- Follow the build steps in the project files

## 🗂️ Quick Folder Flow

A simple setup path looks like this:

Download → Extract → Open folder → Build or run → Test events

## 🧰 Helpful Terms

A few words you may see in the project:
- **SDK**: A tool kit for developers
- **Telemetry**: Data sent from the app
- **Event tracking**: Recording player actions
- **Thread-safe**: Safe for use in more than one task at once
- **Offline-first**: Works even before the app reconnects
- **CMake**: A build setup tool for C++ projects