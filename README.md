# CPU Monitor for ClearOS

CPU Monitor is a lightweight ClearOS plugin for real-time processor monitoring.

It displays total CPU usage, per-core load, CPU model information, and core count directly in the ClearOS Webconfig interface.  
The plugin also includes a dashboard widget for quick access to current processor activity.

## Features

- Real-time total CPU usage display
- Per-core CPU load visualization
- CPU model and core count display
- ClearOS Webconfig integration
- Dashboard widget support
- Lightweight implementation without external monitoring services

## Description

Displays real-time CPU load, including total CPU usage and per-core usage.

## Data sources

The plugin reads processor information from standard Linux system sources:

- `/proc/stat`
- `/proc/cpuinfo`

## Purpose

This project provides a simple built-in way to observe CPU load on a ClearOS server without requiring external monitoring tools.
