# Zynzo Android App
**Tagline:** Explore Beyond Limits

यह शुरुआती Android प्रोजेक्ट Kotlin और Jetpack Compose में है।

## इस संस्करण में
- Dark navy, cyan और purple वाली Zynzo home screen
- Web, Images, Videos और News खोज श्रेणियाँ
- खोज ब्राउज़र में Google Search/Google News के जरिए खुलती है
- हाल की खोजें डिवाइस पर सेव होती हैं
- हिंदी/English लेबल बदलने का विकल्प

## सीमाएँ
- यह स्वतंत्र search index नहीं है; खोज ब्राउज़र में Google के जरिए होती है।
- माइक्रोफोन बटन अभी placeholder है।
- Saved searches का अलग save feature अभी लागू नहीं है।
- यह debug APK होगा, Play Store के लिए signed release APK नहीं।

## GitHub से APK बनाना
1. ZIP को फोन में डाउनलोड करके extract करें।
2. GitHub repository में Add file → Upload files चुनें।
3. ZIP अकेली अपलोड न करें। Extract किए गए फ़ोल्डर की अंदर की सभी फाइलें और folders repository root में अपलोड करें, जिसमें `settings.gradle.kts`, `build.gradle.kts`, `app/`, `.github/` शामिल हों।
4. Commit changes दबाएँ।
5. Repository के Actions टैब में `Build Zynzo Android APK` workflow खोलें। `main` पर push के बाद यह अपने आप भी चलेगा; चाहें तो Run workflow दबाएँ।
6. Build पूरा होने पर workflow run खोलें और Artifacts में `Zynzo-debug-APK` डाउनलोड करें।
7. डाउनलोड ZIP के अंदर `app-debug.apk` होगा। केवल भरोसेमंद APK इंस्टॉल करें।

Package: `com.zynzo.app`
Minimum Android: 8.0 (API 26)
