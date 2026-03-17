# 🔴 Yerike-0.5 (Experimental Build)

**Author:** `Docenkoviktorrr-hash`
**Status:** Alpha / Potentially Destructive Art Project

---

## ⚠️ WARNING: READ BEFORE EXECUTION

This program is designed as a **digital horror experience**. It performs heavy visual and auditory manipulations that may be dangerous for certain users.

* **EPILEPSY WARNING:** This software generates rapidly moving patterns and high-contrast flickering. DO NOT run this if you have photosensitive epilepsy.
* **HEART CONDITIONS:** The program utilizes high-frequency audio (reverse "Song of Healing") and sudden system-level changes that may cause stress or anxiety.
* **SYSTEM IMPACT:** This is a "living" creepypasta. It will lock your input, override system volume, and intentionally trigger a **Critical System Error (BSOD)** via `NtRaiseHardError`.

**USE AT YOUR OWN RISK.** The author is not responsible for unsaved data loss or heart attacks.

---

## 📂 Features

- **Audio Hijack:** Automatic system volume set to 100% with a looped ambient track.
- **Input Lock:** Mouse cursor is force-anchored to the screen center.
- **GDI Corruption:** Real-time "bleeding" screen effect using Windows GDI.
- **Persistence:** Self-injects into `HKCU\Software\Microsoft\Windows\CurrentVersion\Run` as `WindowsKernel`.
- **The End:** Hard-coded timer (1m 26s) leading to a kernel-level crash.

---

## 🛠 Compilation (g++)

To build the executable from source, use the following command in your terminal:

```bash
g++ main.cpp -o Yerike-0.5.exe -lwinmm -lntdll -lole32 -mwindows -static
