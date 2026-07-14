# windows-dfir-lab19-recycle-bin-forensic-investigation
## Overview

This lab demonstrates how deleted files can still provide valuable forensic evidence during a Windows investigation.

The objective was to simulate accidental or suspicious file deletion, inspect the Recycle Bin, recover deleted files, and document the investigation process using native Windows tools.

---

## Lab Objectives

- Create sample files
- Delete files to Recycle Bin
- Investigate deleted artifacts
- Restore deleted evidence
- Validate file recovery
- Document forensic findings

---

## Environment

- Windows 10 VM
- VMware Workstation Player
- PowerShell
- Windows File Explorer
- Recycle Bin
- Event Viewer

---

## Skills Practiced

- Windows Forensics
- Evidence Recovery
- File Restoration
- Digital Evidence Handling
- Incident Documentation
- DFIR Methodology

---

## Investigation Workflow

1. Create investigation folder
2. Generate sample files
3. Add sample content
4. Delete evidence
5. Examine Recycle Bin
6. Restore deleted files
7. Verify recovered evidence
8. Document findings

---

## Evidence Collected

- Deleted files
- Restored files
- File timestamps
- PowerShell output
- File Explorer evidence
- Event Viewer screenshots

---

## Key Takeaways

- Deleted files are not immediately destroyed.
- Recycle Bin preserves recoverable evidence.
- File recovery should be documented before further investigation.
- Native Windows artifacts can provide valuable DFIR evidence.

---


## MITRE ATT&CK Mapping

| Technique | Description |
|-----------|-------------|
| T1070 | Indicator Removal on Host |
| T1070.004 | File Deletion |

---

