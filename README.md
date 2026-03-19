# Q Card - Dijital Kartvizit Oluşturucu

Bu proje App-preneur eğitimi final ödevi için hazırlanmıştır.

## Özellikler
- Kullanıcı bilgilerini form üzerinden dinamik alma
- Anlık QR Kod oluşturma
- QR kod okutulduğunda telefona doğrudan kaydedilebilir VCF (vCard) indirme desteği
- Modern ve responsive UI (Tailwind CSS)

## Kurulum ve Çalıştırma
1. `npm install` komutu ile bağımlılıkları yükleyin.
2. `npm run dev` komutu ile projeyi yerel ortamınızda başlatın.
3. `npm run build` komutu ile projeyi yayına hazırlayın (`dist` klasörü oluşacaktır).

## Ücretsiz Canlıya Alma (Deployment) Seçenekleri

### 1. Vercel (Önerilen)
- [Vercel](https://vercel.com/) sitesine GitHub hesabınızla giriş yapın.
- Bu projeyi bir GitHub reposuna yükleyin ve Vercel üzerinden repoyu seçip "Deploy" butonuna basın. Vercel, Vite projesi olduğunu otomatik algılayıp saniyeler içinde canlıya alacaktır.

### 2. Netlify
- `dist` klasörünü bilgisayarınıza indirin.
- [Netlify Drop](https://app.netlify.com/drop) sayfasına gidin ve `dist` klasörünü sürükleyip bırakın. Siteniz anında yayında!

### 3. GitHub Pages
- Projeyi bir GitHub reposuna yükleyin.
- `vite.config.js` içerisine `base: "/repo-adiniz/"` eklediğinizden emin olun (eğer root dizinde değilse).
- Reponuzun Settings > Pages kısmından deploy ayarlarını yapılandırın.

