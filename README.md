# Swamp Scoop Bucket

[Scoop](https://scoop.sh/) bucket for [Swamp](https://swamp-lang.org) CLI.

## Installation

1. Install Scoop

Open **PowerShell** and run:

```powershell
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
Invoke-RestMethod -Uri https://get.scoop.sh | Invoke-Expression
```

2. Add Swamp Bucket URL (only needed first time)

Run the following command to add this repository to your Scoop installation:

```powershell
scoop bucket add swamp https://github.com/swamp/scoop-bucket
```

3. Install Swamp

```powershell
scoop install swamp
```

## Updating

To update swamp tools:

```powershell
scoop update swamp
```
