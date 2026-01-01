# Simple MIDI Player

A lightweight Windows MIDI player built with C# and NAudio. Designed for precise General MIDI playback, device routing, and responsive UI controls.

## Features
- General MIDI instrument support
- Accurate playback timing using NAudio
- Speed/tempo adjustment
- Device output selection
- Start / Stop / Pause controls
- Clean WinForms interface
- Error handling and recovery

## Architecture Overview
- `SimpleMidiPlayer` handles device output, timing, and instrument changes.
- WinForms UI provides routed control over playback and device selection.
- Uses NAudio's `MidiOut` and clocking mechanisms.

## Requirements
- .NET Framework or .NET 6+ (specify)
- Windows OS
- NAudio

## Installation & Usage
Clone, build, run.

## Roadmap
- Improved timing precision
- Track visualization
- Instrument library selection

Created by **Max Christian Heinrich Flinker**.
