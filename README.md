# XT-ScalperPro

## Як збирати Release APK через GitHub Actions

1. Додай свої `.py` та `.kv` файли.
2. Завантаж свій keystore у GitHub Secrets:
   - KEYSTORE_BASE64
   - KEYSTORE_ALIAS
   - KEYSTORE_PASSWORD
   - KEY_PASSWORD
3. Комітни і запуш свій код у `main`.
4. Workflow автоматично збере Release APK.
5. Завантажений APK доступний у **Actions → Artifacts**.
