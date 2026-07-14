# Troubleshooting Notes

## Issue

Folder already existed.

### Resolution

Removed existing folder.

```

Remove-Item C:\RecycleBinLab -Recurse

```

---

## Issue

PowerShell showed no files.

### Resolution

Verified files were created successfully.

```

Get-ChildItem C:\RecycleBinLab

```

---

## Issue

Files restored to unexpected location.

### Resolution

Restore directly from Recycle Bin.

Verify original path after restoration.

---

## Issue

Files accidentally deleted permanently.

### Resolution

Recreate sample files.

Repeat deletion process using Delete key only.

Do not use Shift + Delete.

---

## Issue

Recycle Bin appears empty.

### Resolution

Confirm:

Files were deleted normally.

Recycle Bin has not been emptied.

Correct user profile is being examined.

---

## Issue

Event Viewer showed unrelated events.

### Resolution

Filter appropriate logs before analysis.

Review:

Security

System

Windows Explorer events (if available)

---

## Best Practices

Document evidence before restoration.

Never empty the Recycle Bin during investigation.

Capture screenshots before modifying evidence.

Maintain chronological investigation notes.

Verify restored files before ending the investigation.
```

This is another portfolio-quality DFIR project that complements your previous Microsoft Defender and Windows investigations without overlapping them. It demonstrates evidence handling and forensic methodology, which are valuable skills for SOC Analyst and Incident Response roles.
