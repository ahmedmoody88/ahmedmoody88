# مصادر GitHub - الأدلة الجنائية الرقمية (Digital Forensics)
> تاريخ الجمع: يوليو 2026 — للاستخدام كمرجع عند بناء برامج أدلة جنائية رقمية مخصصة

## القوائم المرجعية (Awesome Lists)
- https://github.com/Cugu/awesome-forensics
- https://github.com/meirwah/awesome-incident-response

## الهواتف المحمولة (Mobile Forensics)
- https://github.com/mvt-project/mvt
- https://github.com/abrignoni/iLEAPP
- https://github.com/abrignoni/ALEAPP
- https://github.com/den4uk/andriller
- https://github.com/libimobiledevice/libimobiledevice
- https://github.com/mvt-project/androidqf
- https://github.com/MobSF/Mobile-Security-Framework-MobSF

## تحليل الذاكرة (Memory Forensics)
- https://github.com/volatilityfoundation/volatility3
- https://github.com/ufrisk/MemProcFS
- https://github.com/volatilityfoundation/volatility  (مؤرشف - Volatility2، للرجوع التاريخي فقط)

## تحليل القرص وأنظمة الملفات (Disk Forensics)
- https://github.com/sleuthkit/autopsy
- https://github.com/sleuthkit/sleuthkit
- https://github.com/fox-it/dissect
- https://github.com/google/turbinia  (EOL - وضع صيانة، الخليفة OpenRelik)

## تحليل الشبكة (Network Forensics)
- https://github.com/zeek/zeek
- https://github.com/arkime/arkime
- https://github.com/wireshark/wireshark
- https://github.com/KimiNewt/pyshark
- https://github.com/gcla/termshark

## تحليل البرمجيات الخبيثة (Malware Analysis)
- https://github.com/kevoreilly/CAPEv2
- https://github.com/mandiant/capa
- https://github.com/VirusTotal/yara  (وضع صيانة - الخليفة YARA-X)
- https://github.com/mandiant/flare-floss
- https://github.com/decalage2/oletools

## الاستحواذ على الأدلة وتصوير الأقراص (Acquisition & Imaging)
- https://github.com/Velocidex/velociraptor
- https://github.com/libyal/libewf
- https://github.com/google/grr
- https://github.com/dfir-orc/dfir-orc
- https://github.com/simsong/bulk_extractor

## الـ Timeline والسجلات (Timeline & Logs)
- https://github.com/log2timeline/plaso
- https://github.com/google/timesketch
- https://github.com/log2timeline/dftimewolf
- https://ericzimmerman.github.io  (EZ Tools - EvtxECmd, RECmd, MFTECmd, PECmd, LECmd)
- https://github.com/keydet89/RegRipper3.0
- https://github.com/airbus-cert/regrippy
- https://github.com/obsidianforensics/hindsight

## مكتبات لبناء برنامج مخصص (Reusable Libraries)
- https://github.com/libyal/libyal
- https://github.com/log2timeline/dfvfs
- https://github.com/log2timeline/dfwinreg
- https://github.com/sleuthkit/sleuthkit  (pytsk bindings)

## البصمات والوجه (Fingerprint / Face Matching)
- https://github.com/robertvazan/sourceafis-java
- https://github.com/robertvazan/sourceafis-net
- https://github.com/neilharan/openafis
- https://github.com/cmusatyalab/openface
- https://github.com/ageitgey/face_recognition
- https://github.com/Faceplugin-ltd/Open-Source-Face-Recognition-SDK

---
## ملاحظات هامة
- Volatility 2 مؤرشف رسمياً منذ إصدار Volatility3 v2.26.0 (مايو 2025) — استخدم Volatility3 فقط في أي مشروع جديد.
- YARA الكلاسيكي في وضع صيانة منذ إطلاق YARA-X 1.0.0 (يونيو 2025) — فضّل YARA-X للمشاريع الجديدة.
- Turbinia في وضع EOL/صيانة — الخليفة الموصى بها هي OpenRelik.
- عند البناء على أي من هذه المكتبات في أداة تُستخدم كدليل قضائي، يجب توثيق منهجية التحقق (validation) من دقة النتائج.
