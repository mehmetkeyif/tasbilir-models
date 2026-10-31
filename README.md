# Taşbilir modelleri

Taşbilir (Stonewise) uygulamasının telefonda çalışan taş tanıma modelleri. Bu depoda kod yoktur; uygulama yalnızca
`manifest.json` dosyasını okur ve yeni sürüm varsa model dosyalarını indirir.

- `manifest.json`: en son sürüm, etiketler, giriş biçimi ve indirme adresleri
- `v<N>/model.tflite`: LiteRT (TensorFlow Lite) modeli
- `v<N>/model.pte`: ExecuTorch modeli (XNNPACK)
- `v<N>/attribution.csv`: eğitimde kullanılan Wikimedia Commons fotoğraflarının yazarları ve lisansları

Eğitim fotoğrafları yalnızca kamu malı, CC0, CC BY ve CC BY-SA lisanslı dosyalardan seçilmiştir.

---

On-device stone recognition models for the Taşbilir (Stonewise) app. Training photos come from Wikimedia Commons
(public domain, CC0, CC BY, CC BY-SA); authors and licences are listed in each version's `attribution.csv`.
