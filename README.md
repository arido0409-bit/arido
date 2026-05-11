# Arido

تطبيق Flutter عالي الأداء يجمع بين Firebase و Agora للاتصالات الفيدية والدردشة في الوقت الفعلي.

## المتطلبات المثبتة

تم إضافة المتطلبات التالية إلى المشروع:

```yaml
dependencies:
  flutter:
    sdk: flutter
  firebase_core: ^2.0.0        # Core Firebase functionality
  firebase_auth: ^4.0.0        # Firebase Authentication
  cloud_firestore: ^4.0.0      # Cloud Firestore Database
  agora_rtc_engine: ^6.0.0     # Agora Video/Audio SDK
```

## البدء

### المتطلبات الأساسية
- Flutter SDK 3.0.0 أو أحدث
- Dart SDK المتضمن مع Flutter
- iOS Deployment Target 11.0 أو أحدث (إذا كنت تطور لـ iOS)
- Android minSdkVersion 21 أو أحدث (إذا كنت تطور لـ Android)

### التثبيت

1. استنساخ المستودع:
```bash
git clone [repository-url]
cd arido
```

2. تثبيت المتطلبات:
```bash
flutter pub get
```

3. تشغيل التطبيق:
```bash
flutter run
```

## هيكل المشروع

```
arido/
├── lib/              # الملفات الأساسية للتطبيق
├── test/             # اختبارات الوحدة
├── android/          # ملفات Android
├── ios/              # ملفات iOS
├── web/              # ملفات الويب
├── pubspec.yaml      # تعريف المتطلبات
└── README.md         # هذا الملف
```

## الميزات

- 🔐 مصادقة آمنة مع Firebase Auth
- 💾 قاعدة بيانات في الوقت الفعلي مع Cloud Firestore
- 📹 اتصالات فيديو عالية الجودة مع Agora
- 🔄 مزامنة البيانات تلقائياً

## الترخيص

تحديد الترخيص الخاص بك هنا (مثل MIT, Apache 2.0, إلخ)