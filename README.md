# SV Scan

Live barcode scanner for the Sevier Vapor count app. The count app runs inside Google Apps Script, whose frame blocks the live camera. So "Scan with camera" opens this page, which reads the barcode and sends it back to the app as `?store=...&code=...`.

This page holds no data or keys. The count app still requires an approved seviervapor.com Google sign-in.
