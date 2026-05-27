<h1 align="center">Mem Reduct</h1>

<p align="center">
	<a href="https://github.com/henrypp/memreduct/releases"><img src="https://img.shields.io/github/v/release/henrypp/memreduct?style=flat-square&include_prereleases&label=version" /></a>
	<a href="https://github.com/henrypp/memreduct/releases"><img src="https://img.shields.io/github/downloads/henrypp/memreduct/total.svg?style=flat-square" /></a>
	<a href="https://github.com/henrypp/memreduct/issues"><img src="https://img.shields.io/github/issues-raw/henrypp/memreduct.svg?style=flat-square&label=issues" /></a>
	<a href="https://github.com/henrypp/memreduct/graphs/contributors"><img src="https://img.shields.io/github/contributors/henrypp/memreduct?style=flat-square" /></a>
	<a href="https://github.com/henrypp/memreduct/blob/master/LICENSE"><img src="https://img.shields.io/github/license/henrypp/memreduct?style=flat-square" /></a>
</p>

-------

<p align="center">
	<img src="/images/memreduct.png?cachefix" />
</p>

### Beschreibung:
Leichtgewichtige Echtzeit-Speicherverwaltungsanwendung zur Überwachung
und Bereinigung des Systemspeichers auf Ihrem Computer.

Das Programm nutzt undokumentierte interne Systemfunktionen (Native API) zur Bereinigung des System-Caches (System Working Set, Working Set, Standby-Seitenlisten, Modified-Seitenlisten) mit variablem Ergebnis ~10-50%. Die Anwendung ist kompatibel mit <s>Windows XP SP3</s> Windows 7 SP1 und höheren Betriebssystemen.

Sie können entweder die Installer- oder Portable-Version herunterladen. Für die korrekte Funktion benötigen Sie Administratorrechte.

```
Um den portablen Modus zu aktivieren, erstellen Sie "memreduct.ini" im Anwendungsordner oder verschieben Sie sie aus "%APPDATA%\Henry++\Mem Reduct".
```

### Systemanforderungen:
- Windows 7, 8, 8.1, 10, 11 64-bit/ARM64
- Eine SSE2-fähige CPU
- <s>KB2533623</s> [KB3063858](https://www.microsoft.com/en-us/download/details.aspx?id=47442) Update für Windows 7 war erforderlich

### Spenden:
- [Bitcoin](https://www.blockchain.com/btc/address/1LrRTXPsvHcQWCNZotA9RcwjsGcRghG96c) (BTC)
- [Ethereum](https://www.blockchain.com/explorer/addresses/eth/0xe2C84A62eb2a4EF154b19bec0c1c106734B95960) (ETH)
- [Yandex Money](https://yoomoney.ru/to/4100115776040583) (RUB)
- [Paypal](https://paypal.me/henrypp) (USD)

### GPG-Signatur:
Binärdateien haben eine GPG-Signatur `memreduct.exe.sig` im Anwendungsordner.

- Öffentlicher Schlüssel: [pubkey.asc](https://raw.githubusercontent.com/henrypp/builder/master/pubkey.asc) ([pgpkeys.eu](https://pgpkeys.eu/pks/lookup?op=index&fingerprint=on&search=0x5635B5FD))
- Schlüssel-ID: 0x5635B5FD
- Fingerabdruck: D985 2361 1524 AB29 BE73 30AC 2881 20A7 5635 B5FD
---
- Webseite: [github.com/henrypp](https://github.com/henrypp)
- Support: sforce5@mail.ru
---
(c) 2011-2026 Henry++
