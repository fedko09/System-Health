System Health Snapshot Tool

Overview
This PowerShell-based desktop tool provides a full system health assessment for Windows 10 and Windows 11 machines. It is designed for technicians, sysadmins, power users, and support staff who need a clean, fast, and unified interface for diagnosing a workstation or server.

The tool launches a WPF-powered GUI and performs detailed scans, displaying data in sortable, filterable grids. It also generates exportable CSVs and a full HTML snapshot report suitable for documentation, tickets, audits, or diagnostics.

Features
• Hardware and OS specifications
• Disk analysis with health flags, percent free calculation, and risk levels
• Full service inventory with status, start type, and problem detection
• Installed software listing (with optional “installed within last 30 days” filter)
• Defender, Firewall, BitLocker, UAC, and domain/security posture information
• Network adapter details and basic connectivity tests
• CPU and RAM snapshot
• Top processes by CPU usage
• Event log summary (last 24 hours)
• Automated findings for security, updates, and network issues
• Search box for filtering each tab
• Sorting by column headers
• Context menus for copying rows
• Service management (Start/Stop/Restart) when run as administrator
• CSV exports for any tab
• Snapshot HTML report with full system summary
• Technician summary: a plain-text health overview ready for tickets or documentation
• Global loading overlay to prevent “Not Responding” behavior during scans

Usage
Run the script with PowerShell 5 or newer.
No installation required.
If service control or certain security checks are needed, run PowerShell as Administrator.

Files Produced
• CSV exports generated on demand
• HTML snapshot reports generated to the desktop using system hostname and timestamp

Notes
• Best performance is achieved on systems with PowerShell running in STA mode (handled automatically).
• Snapshot generation may take longer on systems with large software inventories.
• All data is gathered locally; no information is transmitted outside the system.

Created by
Bogdan Fedko