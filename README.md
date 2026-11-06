# Diva Vurma (Android)

Oyun bir WebView içinde çalışır. APK, GitHub Actions ile otomatik derlenir.

## APK nasıl alınır
1. Bu klasörün içeriğini bir GitHub reposuna yükle (branch: `main`).
2. Repo'da **Actions** sekmesine gir, **Build APK** çalışmasını bekle.
3. Biten çalışmanın altındaki **DivaVurma-apk** dosyasını indir.
4. İçindeki `app-debug.apk` dosyasını telefona atıp kur (bilinmeyen kaynaklara izin vermen gerekebilir).

## Değiştirmek istersen
- Oyunun kendisi: `app/src/main/assets/index.html`
- Uygulama adı: `app/src/main/res/values/strings.xml`
- Logo: `app/src/main/res/drawable/ic_launcher_foreground.xml` ve `ic_launcher_background.xml`
