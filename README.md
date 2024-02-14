 * Project Archive: GBA-Discord
 * 
 * This repository houses an archived version of the GameBoyCore.js file from grantgalitz/GameBoy-Online, which was previously an NPM module exporting the GameBoyCore.js file. Please note that this project is no longer actively maintained or functional, and it is provided here purely for archival purposes.
 * 
 * Changes and Updates:
 * - Conversion into a module format.
 * - Elimination of global variables for improved modularity.
 * - Streamlined interface for adjusting options.
 * - Compatibility enhancements for both browser and node.js environments.
 * - Removal of JavaScript-based resizing in favor of browser-native methods.
 * - Support for inputting ROM data as Buffer or ArrayBuffer instead of deprecated binary strings.
 * - Implementation of linting for code cleanliness.
 * - Removal of unnecessary dependencies to streamline the project.
 * - Transformation of the main interface into an Emitter pattern.
 * - Integration of debug features for easier troubleshooting.
 * - Addition of server-side usage examples for reference.
 * 
 * How to Use:
 * To utilize this archived version, simply include the GameBoyCore.js file in your project and follow the below usage pattern:
 * 
 * var gb = require('gameboy');
 * gb(canvasElement, romData, opts);
 * 
 * Options:
 * - bootRom: Boot with the boot ROM first (default: true).
 * - gbBootRom: Use GameBoy boot ROM instead of GameBoy Color (default: false).
 * - mbc1: Allow for MCB1 instead of ROM only (default: false).
 * - prioritizeGb: Give priority to GameBoy mode (default: false).
 * - interval: Emulator loop interval (default: 6).
 * - canvas: Custom canvas constructor (default: null).
 * - imageSmoothing: Smooth images when resizing (default: true).
 * - drawEvents: Emit draw events (default: false).
 * - sound: Sound interface (default: null).
 * - volume: Volume level (default: 1).
 * - audioBufferMin: Minimum span amount over x interpreter iterations (default: 10).
 * - audioBufferMax: Maximum span amount over x interpreter iterations (default: 20).
 * - colorizeGb: Colorize GameBoy mode (default: true).
 * - overrideMbc: Override MBC RAM disabling and always allow reading and writing to the banks (default: false).
 * - typedArrays: Use typed arrays (default: true).
 * - channels: User-controlled channel enables (default: [true,true,true,true]).
 * 
 * Events:
 * - draw: Raised only if drawEvents is true whenever a draw to the canvas occurs.
 * - error: Raised when emulation should be paused due to unexpected behavior.
 * 
 * Please be aware that while this codebase may serve as a valuable reference, it is no longer actively maintained or supported.


