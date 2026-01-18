# ProcDump v11.1

Download latest version from Releases:       
https://github.com/askprog/ProcDump/releases/tag/v11.1

## Introduction

ProcDump is a lightweight command-line utility for capturing process dumps during crashes, hangs, high CPU spikes, or specific exception conditions on Windows systems. Designed for administrators, developers, and incident responders, it helps you collect forensic-quality memory snapshots that can be analyzed later in WinDbg, Visual Studio, or other debugging tools. With flexible trigger options, ProcDump can generate dumps when a process exceeds a CPU threshold for a defined duration, stops responding, or throws an unhandled exception, enabling reliable evidence collection without constant manual supervision.

The tool supports both full and mini dumps, giving you control over file size versus diagnostic depth. ProcDump can attach to an existing process by PID or name, monitor services, and run continuously to capture multiple events over time. Advanced options allow you to limit dump counts, set custom dump locations, and define naming patterns for easy triage and correlation with logs. It also integrates well with automation: you can run it from scripts, scheduled tasks, or remote management workflows to standardize crash capture across fleets.

Because ProcDump operates with minimal overhead and produces consistent, repeatable artifacts, it is widely used in production troubleshooting and post-incident analysis. Whether you are investigating intermittent application freezes, diagnosing memory corruption, or collecting data for vendor support, ProcDump provides a practical, professional way to capture the information you need quickly and accurately.
