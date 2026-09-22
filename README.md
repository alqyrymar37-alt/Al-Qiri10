# القيري الأسطورة — Al-Qiri LEGEND
Kotlin + Jetpack Compose (target SDK 34). Arabic UI, RTL, dark + gold theme.
Voice in (SpeechRecognizer ar-YE), voice out (TextToSpeech ar), text in/out.

Files
- MainActivity.kt : the 8 functions (scanPhoneSecurityUltimate, saveToAlQiriFile, getAlQiriFiles,
                    dialAndSpeak / sendSmsToContact / findContactNumber, lookupCallerID, findMyPhone,
                    shareMyLocationWith / requestLocationFrom) + UI + voice
- Brain.kt        : Claude tool-use loop (online), Arabic rule-based router (offline), teacher mode
- SecureStore.kt  : API key stored encrypted

Safety: every call / SMS / location-share needs an on-screen approval (auto-deny after 2 min).
