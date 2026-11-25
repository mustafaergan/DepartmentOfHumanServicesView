# Department Of Human Services View

Bir "Department of Human Services" arayüzü için başlatılmış, ancak yapım aşamasında kalmış React projesi.
Kod, [react-boilerplate](https://github.com/react-boilerplate/react-boilerplate) 3.4.0 şablonunun neredeyse
değiştirilmemiş hâlidir; projeye özgü ekran henüz yazılmamıştır.

> **Not:** Bu depo 2017 yılında örnek amaçlı açıldı ve artık güncellenmiyor. Bağımlılıkları eskidir ve bilinen
> güvenlik açıkları içerir; üretimde kullanmayın.

## İçerik

| Klasör | Ne yapar |
|---|---|
| `app/` | Uygulama kodu: şablonun bileşenleri (`components/`) ve sayfaları (`containers/`: HomePage, FeaturePage, NotFoundPage, dil seçimi) |
| `server/` | Geliştirme ve üretim için Express sunucusu (varsayılan port 3000) |
| `internals/` | Webpack, test, kod üreteci (plop) ve yardımcı betikler |
| `docs/` | react-boilerplate'in kendi belgeleri |

Şablondaki örnek ana sayfa, girilen GitHub kullanıcısının depolarını listeler.

## Teknolojiler

- React 15.4, Redux 3.6, redux-saga 0.14, Immutable.js 3.8, React Router 3
- styled-components 1.1, Webpack 2, Babel 6, Jest 18
- Express 4.14

## Çalıştırma

Bağımlılıklar 2017 tarihli olduğundan güncel Node sürümleriyle kurulum büyük olasılıkla hata verir; Node 6 veya 8
gibi eski bir sürüm (örneğin `nvm` ile) kullanın.

```bash
npm install
npm start          # http://localhost:3000
npm run build      # üretim derlemesi build/ klasörüne
npm test
```

## Lisans

react-boilerplate MIT lisanslıdır, Copyright (c) 2017 Maximilian Stoiber. Ayrıntı için `LICENSE.md`.
