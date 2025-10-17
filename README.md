# MSCS-533-A01-Project

## MAUI Heatmap Tracker
Simple cross-platform .NET MAUI app that records device GPS and visualizes a heatmap using MapCircles and SQLite.

### Features
- Periodic location sampling
- Persist locations to local SQLite DB
- Heatmap visualization via semi-transparent circles
- Start / Stop / Refresh / Clear UI controls

### Requirements
- Visual Studio with .NET MAUI workload
- NuGet: sqlite-net-pcl, CommunityToolkit.Mvvm, Microsoft.Maui.Controls.Maps

### Run
1. Clone repo
2. `dotnet restore`
3. Open in Visual Studio, set platform (Android/iOS)
4. Add platform permissions (see Platforms/ folder)
5. Deploy to device or emulator

