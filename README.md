# Gene Brawl

A Frida-based research and debugging toolkit for analyzing Brawl Stars client behavior.  
**Supported versions:** `62.250` or iOS `62.258` (partial support)

## Features

- Runtime function tracing  
- Method argument inspection  
- Educational research on game client internals  
- Debugging aid for security researchers (authorized environments only)

> No game modification, cheating, or injection capabilities are provided or intended.

## Usage

**Install dependencies**:  
```npm install```   

**Build the script**:  
```npm run build_dev``` – DEBUG version  
```npm run build``` – PRODUCTION version  

**Build & attach**:  
```npm run gadget``` – DEBUG version, Gadget mode  
```npm run gadget_prod``` – PRODUCTION version, Gadget mode  
```npm run frida_mac_dev``` – DEBUG version on macOS (requires PlayCover installation with bundle name `gene.brawl.dev`)*  
```npm run ios_laser``` – PRODUCTION version on iOS device (bundle name `com.supercell.laser`)*  
```npm run ios_laser_dev``` – DEBUG version on iOS device (bundle name `com.supercell.laser`)*  

\* Bundle names can be changed in `package.json`.

## Contributions

Contributions for research, educational, or debugging improvements are welcome. Please open a pull request.

# Disclaimer

This project is **not affiliated with, endorsed by, sponsored by, or approved by Supercell**.  
**Supercell** is a trademark of **Supercell Oy**.  

This tool is intended **exclusively for**:
- Authorized security research  
- Debugging on devices you own or have explicit permission to test  
- Educational purposes  

The author does not condone or support any use that violates Supercell’s Terms of Service, including cheating, unfair advantage, or modification of the game client behavior.  
Use at your own risk.