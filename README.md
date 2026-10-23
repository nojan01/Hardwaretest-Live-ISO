# Hardwaretest Live-ISO

Bootfähiges Debian-13-(trixie)-Live-System (amd64, BIOS und UEFI) zum Testen von
PCs, Workstations und Servern mit der Anwendung
[Hardwaretest](https://github.com/nojan01/Ubuntu-Stresstest).

Download: siehe [Releases](../../releases).

## Inhalt

- Hardwaretest (CPU-, RAM-, Datenträger-, NVMe-, Netzwerk-, IPMI/ECC- und NVIDIA-Tests)
- NVIDIA-Treiber 595 (Open-Kernelmodul) mit **GPU-Lasttest** (Rechenlast + VRAM-Mustertest)
  für alle NVIDIA-GPUs ab Turing: GeForce GTX 16xx / RTX 20xx–50xx, RTX/Quadro,
  Rechenzentrums-GPUs (T4, A100, H100 …)
- Prime95/mprime, stress-ng, fio, smartmontools, nvme-cli, ipmitool, HPE iLOrest u. a.
- memtest86+ im Bootmenü
- Leichter Desktop (Openbox), keine automatische Update-Prüfung im Live-System

Nicht enthalten (im Gegensatz zur internen Variante): NVIDIA DCGM, MemTest86 Pro.

## Auf USB-Stick schreiben

```bash
sudo dd if=hardwaretest-live-*.iso of=/dev/sdX bs=4M status=progress conv=fsync
```

Oder mit balenaEtcher / Rufus (DD-Modus).

## Lizenzen

- **Eigene Bestandteile** (Hardwaretest, Build-Konfiguration, Hintergründe):
  MIT-Lizenz, siehe [LICENSE](LICENSE).
- **Alle übrigen Bestandteile** (Linux-Kernel, Debian-Pakete, Firmware, Qt/PySide6 u. a.)
  stehen unter ihren jeweiligen Lizenzen (GPL, LGPL, BSD, MIT, …). Die MIT-Lizenz gilt
  **nicht** für das ISO als Ganzes.
  - Vollständige Lizenztexte: im laufenden System unter `/usr/share/doc/<paket>/copyright`.
  - Liste aller Pakete mit Version und Lizenz: [THIRD-PARTY-LICENSES.md](THIRD-PARTY-LICENSES.md)
    sowie die `.packages`-Datei im jeweiligen Release.

### Quellcode

Alle Debian-Pakete stammen unverändert aus dem offiziellen Debian-Archiv. Der Quellcode
der exakt enthaltenen Versionen ist erhältlich über

- `apt source <paket>=<version>` bzw. https://sources.debian.org/
- https://snapshot.debian.org/ (archivierte Versionen)

Auf Anfrage stelle ich den Quellcode der im ISO enthaltenen GPL-Pakete für mindestens
drei Jahre ab Veröffentlichung des jeweiligen Release bereit
(Kontakt: Issue in diesem Repository).

Quellcode von Hardwaretest: https://github.com/nojan01/Ubuntu-Stresstest

## Haftungsausschluss

Stresstests belasten die Hardware stark. Destruktive Datenträgertests löschen Daten.
Nutzung auf eigene Gefahr, ohne Gewährleistung (siehe LICENSE).
