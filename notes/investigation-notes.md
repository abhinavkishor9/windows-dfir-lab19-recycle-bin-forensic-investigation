# Investigation Notes

## Incident Summary

During routine forensic analysis, multiple business files were found deleted from the workstation.

The objective was to determine whether the files were permanently removed or could be recovered for investigation.

---

## Investigation Timeline

### Step 1

Created a working directory.

Evidence:

C:\RecycleBinLab

---

### Step 2

Created three sample business files.

EmployeeList.xlsx

Invoice.docx

Passwords.txt

Verified using PowerShell.

---

### Step 3

Added sample content into each file.

Purpose:

Simulate sensitive business documents.

---

### Step 4

Deleted the files.

Files appeared inside Windows Recycle Bin.

---

### Step 5

Opened Recycle Bin.

Verified deleted files remained recoverable.

Observed:

Original filename

Deletion timestamp

Original location

---

### Step 6

Restored deleted files.

Recovery completed successfully.

---

### Step 7

Verified restoration.

Confirmed:

Files returned to

C:\RecycleBinLab

Original names preserved

Contents intact

---

### Step 8

Reviewed Event Viewer.

No security incident related to file deletion was identified.

---

## Findings

Three files were deleted.

Files were recoverable.

No permanent deletion occurred.

Evidence remained intact.

---

## Lessons Learned

Recycle Bin is an important forensic artifact.

Deleted files should be collected before permanent removal.

Recovery actions should always be documented.

Native Windows utilities provide sufficient evidence for basic DFIR investigations.
