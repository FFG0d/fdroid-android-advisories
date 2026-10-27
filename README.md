# F-Droid / Android exported-component vulnerability advisories

**46** independently researched vulnerabilities in Android applications distributed via F-Droid and other sources, disclosed on **2026-10-11**.

## Status of the CVE identifiers

CVE IDs for all 46 findings were requested from the [MITRE CNA of Last Resort](https://mitre.github.io/mitre-cve-roles/CNA-LR) on 2026-09-27 and the publication of the records was requested on 2026-10-11.

**All identifiers were assigned on 2026-10-27.** MITRE CNA-LR replied to the request with one `CVE-2026-1070xx` identifier per finding; the assigned number is shown in each advisory and in the table below. The `CAN-2026-######` numbers are the MITRE **request tracking numbers** from which those IDs were issued — the request form states explicitly: _"You'll get a CAN-YYYY-####### request tracking number (NOT a CVE ID number)"_ and _"please do not use the CAN number as a public vulnerability ID"_. One tracking number covers two findings (Simple Contacts Pro and its Fossify fork share the same inherited provider), and one finding (Bulk Share, `CAN-2026-2053083`) has no identifier yet.

## Advisories

| # | Package | Product | Weakness | CVE ID | Tracking no. | Advisory |
|---:|---|---|---|---|---|---|
| 1 | `eu.faircode.netguard` | NetGuard | CWE-926 | CVE-2026-107039 | `CAN-2026-2038421` | [W6-03](advisories/CVE-2026-107039.md) |
| 2 | `li.klass.fhem` | li.klass.fhem | CWE-926 | CVE-2026-107051 | `CAN-2026-2038423` | [W6-D01](advisories/CVE-2026-107051.md) |
| 3 | `com.simplemobiletools.contacts.pro` | Fossify Contacts, Simple Contacts Pro | CWE-926 | CVE-2026-107015, CVE-2026-107016 | `CAN-2026-2038424` | [W6-H57-01](advisories/CVE-2026-107015-CVE-2026-107016.md) |
| 4 | `allen.town.focus.podcast` | FocusPodcast | CWE-926 | CVE-2026-107046 | `CAN-2026-2053056` | [W6-F01](advisories/CVE-2026-107046.md) |
| 5 | `com.appmindlab.nano` | neutriNote CE | CWE-926 | CVE-2026-107055 | `CAN-2026-2053057` | [W6-H1-05](advisories/CVE-2026-107055.md) |
| 6 | `app.usp` | USP - ZX Spectrum Emulator | CWE-22 | CVE-2026-107042 | `CAN-2026-2053058` | [W6-H10-01](advisories/CVE-2026-107042.md) |
| 7 | `net.bible.android.activity` | AndBible: Bible Study | CWE-926 | CVE-2026-107057 | `CAN-2026-2053059` | [W6-H11-03](advisories/CVE-2026-107057.md) |
| 8 | `net.kollnig.missioncontrol.fdroid` | TrackerControl | CWE-926 | CVE-2026-107036 | `CAN-2026-2053060` | [W6-H11-10](advisories/CVE-2026-107036.md) |
| 9 | `net.typeblog.shelter` | Shelter | CWE-926 | CVE-2026-107058 | `CAN-2026-2053061` | [W6-H12-01](advisories/CVE-2026-107058.md) |
| 10 | `com.tailscale.ipn` | Tailscale | CWE-926 | CVE-2026-107060 | `CAN-2026-2053062` | [W6-H12-07](advisories/CVE-2026-107060.md) |
| 11 | `com.oasisfeng.island.fdroid` | Insular | CWE-926 | CVE-2026-107041 | `CAN-2026-2053063` | [W6-H13-02](advisories/CVE-2026-107041.md) |
| 12 | `net.basov.omn.fdroid` | Open Markdown Notes (OMN) | CWE-79 | CVE-2026-107035 | `CAN-2026-2053064` | [W6-H14-09](advisories/CVE-2026-107035.md) |
| 13 | `de.dennisguse.opentracks` | OpenTracks (Non-reproducible) | CWE-926 | CVE-2026-107056 | `CAN-2026-2053065` | [W6-H14-14](advisories/CVE-2026-107056.md) |
| 14 | `de.yaacc` | YAACC | CWE-926 | CVE-2026-107038 | `CAN-2026-2053066` | [W6-H18-01](advisories/CVE-2026-107038.md) |
| 15 | `com.nononsenseapps.notepad` | NoNonsense Notes | CWE-926 | CVE-2026-107037 | `CAN-2026-2053067` | [W6-H19-01](advisories/CVE-2026-107037.md) |
| 16 | `co.ec.cnsyn.codecatcher` | CodeCatcher | CWE-926 | CVE-2026-107043 | `CAN-2026-2053068` | [W6-H23-01](advisories/CVE-2026-107043.md) |
| 17 | `app.crossword.yourealwaysbe.forkyz` | Forkyz | CWE-926 | CVE-2026-107049 | `CAN-2026-2053069` | [W6-H27-01](advisories/CVE-2026-107049.md) |
| 18 | `com.foobnix.pro.pdf.reader` | Librera Reader | CWE-22 | CVE-2026-107053 | `CAN-2026-2053070` | [W6-H3-39](advisories/CVE-2026-107053.md) |
| 19 | `com.tachibana.downloader` | Download Navi | CWE-926 | CVE-2026-107022 | `CAN-2026-2053071` | [W6-H35-01](advisories/CVE-2026-107022.md) |
| 20 | `org.gnosco.share2archivetoday` | Share 2 Archive Today | CWE-926 | CVE-2026-107024 | `CAN-2026-2053072` | [W6-H36-01](advisories/CVE-2026-107024.md) |
| 21 | `com.mhss.app.mybrain` | com.mhss.app.mybrain | CWE-926 | CVE-2026-107023 | `CAN-2026-2053073` | [W6-H37-01](advisories/CVE-2026-107023.md) |
| 22 | `de.mbutscher.wikiandpad.alphabeta` | de.mbutscher.wikiandpad.alphabeta | CWE-926 | CVE-2026-107025 | `CAN-2026-2053074` | [W6-H38-06](advisories/CVE-2026-107025.md) |
| 23 | `com.mendhak.gpslogger` | GPSLogger | CWE-926 | CVE-2026-107047 | `CAN-2026-2053075` | [W6-H4-58](advisories/CVE-2026-107047.md) |
| 24 | `cn.ac.lz233.tarnhelm` | Tarnhelm | CWE-926 | CVE-2026-107027 | `CAN-2026-2053076` | [W6-H41-01](advisories/CVE-2026-107027.md) |
| 25 | `com.tengu.sharetoclipboard` | Share to Clipboard | CWE-926 | CVE-2026-107026 | `CAN-2026-2053077` | [W6-H42-01](advisories/CVE-2026-107026.md) |
| 26 | `com.wbpxre150.shoppinglist` | ShoppingList | CWE-926 | CVE-2026-107028 | `CAN-2026-2053078` | [W6-H43-01](advisories/CVE-2026-107028.md) |
| 27 | `es.pile` | Pile | CWE-926 | CVE-2026-107029 | `CAN-2026-2053079` | [W6-H44-01](advisories/CVE-2026-107029.md) |
| 28 | `com.craftxbox.yubiclip.xor` | YubiClip XOR | CWE-926 | CVE-2026-107030 | `CAN-2026-2053080` | [W6-H45-01](advisories/CVE-2026-107030.md) |
| 29 | `com.ghostsq.commander` | Ghost Commander | CWE-22 | CVE-2026-107032 | `CAN-2026-2053081` | [W6-H48-01](advisories/CVE-2026-107032.md) |
| 30 | `app.motionui.android` | Motion-UI | CWE-926 | CVE-2026-107048 | `CAN-2026-2053082` | [W6-H5-09](advisories/CVE-2026-107048.md) |
| 31 | `me.alexghr.bulkshare.android.app2` | me.alexghr.bulkshare.android.app2 | CWE-926 | *not yet assigned* | `CAN-2026-2053083` | [W6-H52-01](advisories/CAN-2026-2053083.md) |
| 32 | `de.azapps.mirakelandroid` | de.azapps.mirakelandroid | CWE-926 | CVE-2026-107033 | `CAN-2026-2053084` | [W6-H53-01](advisories/CVE-2026-107033.md) |
| 33 | `com.git.amarradi.leafpad` | Leafpad | CWE-926 | CVE-2026-107034 | `CAN-2026-2053085` | [W6-H54-01](advisories/CVE-2026-107034.md) |
| 34 | `bander.notepad` | bander.notepad | CWE-926 | CVE-2026-107014 | `CAN-2026-2053086` | [W6-H56-01](advisories/CVE-2026-107014.md) |
| 35 | `com.ghostsq.commander` | Ghost Commander | CWE-926 | CVE-2026-107018 | `CAN-2026-2053087` | [W6-H58-01](advisories/CVE-2026-107018.md) |
| 36 | `net.canvoki.vokibot` | Voki Bot | CWE-926 | CVE-2026-107017 | `CAN-2026-2053088` | [W6-H59-01](advisories/CVE-2026-107017.md) |
| 37 | `askanimus.arbeitszeiterfassung2` | Working Time Account | CWE-926 | CVE-2026-107019 | `CAN-2026-2053089` | [W6-H60-01](advisories/CVE-2026-107019.md) |
| 38 | `ru.yanus171.feedexfork` | Handy Reading | CWE-926 | CVE-2026-107020 | `CAN-2026-2053090` | [W6-H61-01](advisories/CVE-2026-107020.md) |
| 39 | `org.liberty.android.fantastischmemo` | AnyMemo | CWE-926 | CVE-2026-107021 | `CAN-2026-2053091` | [W6-H62-01](advisories/CVE-2026-107021.md) |
| 40 | `net.basov.omngo.fdroid` | OMN-Go | CWE-926 | CVE-2026-107040 | `CAN-2026-2053092` | [W6-H7-01](advisories/CVE-2026-107040.md) |
| 41 | `com.wirelessalien.android.moviedb` | ShowCase | CWE-926 | CVE-2026-107054 | `CAN-2026-2053093` | [W6-H7-03](advisories/CVE-2026-107054.md) |
| 42 | `com.nextcloud.client` | Nextcloud | CWE-926 | CVE-2026-107059 | `CAN-2026-2053094` | [W6-N01](advisories/CVE-2026-107059.md) |
| 43 | `com.retroarch` | RetroArch | CWE-94 | CVE-2026-107050 | `CAN-2026-2053095` | [W6-NF-01](advisories/CVE-2026-107050.md) |
| 44 | `org.projectmaxs.module.fileread` | MAXS Module FileRead | CWE-22 | CVE-2026-107052 | `CAN-2026-2053096` | [W6-P02+P03](advisories/CVE-2026-107052.md) |
| 45 | `org.projectmaxs.main` | MAXS Main | CWE-926 | CVE-2026-107044 | `CAN-2026-2053097` | [W6-P04](advisories/CVE-2026-107044.md) |
| 46 | `com.greenart7c3.citrine` | Citrine | CWE-926 | CVE-2026-107045 | `CAN-2026-2053098` | [W6-P07](advisories/CVE-2026-107045.md) |

## What each advisory contains

Summary · vulnerable component · attack vector and prerequisites · **full proof of concept** (environment, reproduction steps, measured result, positive/negative controls) · impact · preconditions · remediation · prior-art check · references · disclosure status.

## Common pattern

All findings share the same class of defect: an Android component (`Activity`, `Service`, `BroadcastReceiver` or `ContentProvider`) that is exported without a permission gate, so any application installed on the device — holding **no runtime permissions at all** — can drive it and cross a trust boundary into the victim application's UID. The dominant CWE is [CWE-926](https://cwe.mitre.org/data/definitions/926.html) (Improper Export of Android Application Components).

## Machine-readable index

- [`advisories/index.json`](advisories/index.json) — the same data, one JSON object per finding (including which source the proof-of-concept text was taken from).

## Provenance and limitations

These findings are third-party research. Each advisory records the artifact hash that was verified, the exported declaration read from the shipped manifest, the code path with file/line citations, and a reproduction on a stock Android 13 (API 33) emulator. Where a project has a security contact the advisory states the upstream status that was verified at the time of writing; several of the affected projects are unmaintained or archived, and for those no fix is available. Affected-version ranges are limited to the builds actually verified. Anything that could not be verified is explicitly marked as such in the text.
