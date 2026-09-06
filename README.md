# 🧭 Özgür Tercih

**Geleceğini burada keşfet.**

Özgür Tercih, YÖK Atlas verilerine dayanan, öğrencilerin puanlarına, ilgi alanlarına ve hayallerine göre üniversite/bölüm keşfetmesini sağlayan bir mobil uygulamadır. Yapay zeka destekli danışman özelliğiyle kullanıcıya kişiselleştirilmiş tercih önerileri sunar.

---

## 📱 Özellikler

- **Keşfet** — Puana, şehre, üniversite türüne (devlet/vakıf) ve dile göre filtrelenebilen bölüm arama.
- **Listem** — Kaydedilen bölümlerin tek ekranda takibi.
- **Karşılaştır** — İki bölümü şehir, taban puan, kontenjan gibi kriterlere göre yan yana karşılaştırma.
- **AI Danışman** — Puanını ve tercihlerini yazarak yapay zekadan yol haritası alma.
- **Profil** — Hedef puan, tercih edilen şehirler ve bildirim ayarlarını kişiselleştirme.

---

## 🖼️ Ekran Görüntüleri

> Görsellere tıklayarak orijinal boyutunda görüntüleyebilirsiniz.

<table>
  <tr>
    <td align="center"><b>Profil</b><br/>
      <a href="https://github.com/user-attachments/assets/ce32bdf0-4c19-4e24-bfaa-fbb1607c21bd">
        <img src="https://github.com/user-attachments/assets/ce32bdf0-4c19-4e24-bfaa-fbb1607c21bd" width="200"/>
      </a>
    </td>
    <td align="center"><b>AI Danışman</b><br/>
      <a href="https://github.com/user-attachments/assets/9f23323c-b9a9-4c67-a259-5b7f2dfeb46f">
        <img src="https://github.com/user-attachments/assets/9f23323c-b9a9-4c67-a259-5b7f2dfeb46f" width="200"/>
      </a>
    </td>
    <td align="center"><b>Listem</b><br/>
      <a href="https://github.com/user-attachments/assets/a2bbdd5f-7320-498c-bcdf-0aaa17b64d03">
        <img src="https://github.com/user-attachments/assets/a2bbdd5f-7320-498c-bcdf-0aaa17b64d03" width="200"/>
      </a>
    </td>
  </tr>
  <tr>
    <td align="center"><b>Keşfet</b><br/>
      <a href="https://github.com/user-attachments/assets/7781b07a-3139-48cb-b3c7-c2a2104e9b46">
        <img src="https://github.com/user-attachments/assets/7781b07a-3139-48cb-b3c7-c2a2104e9b46" width="200"/>
      </a>
    </td>
    <td align="center"><b>Karşılaştır</b><br/>
      <a href="https://github.com/user-attachments/assets/4e4b598e-3f9e-4448-883c-d2c522dd9169">
        <img src="https://github.com/user-attachments/assets/4e4b598e-3f9e-4448-883c-d2c522dd9169" width="200"/>
      </a>
    </td>
    <td></td>
  </tr>
</table>

---

## 🛠️ Kullanılan Teknolojiler

- Flutter / Dart
- YÖK Atlas 2026 verileri
- AI destekli tercih danışmanlığı (backend entegrasyonu: `--dart-define=AI_API_URL`)

---

## 🚀 Kurulum

```bash
git clone https://github.com/kullanici-adi/ozgur-tercih.git
cd ozgur-tercih
flutter pub get
flutter run --dart-define=AI_API_URL=<backend-adresin>
```

---

## 📌 Yol Haritası

- [ ] Gerçek zamanlı YÖK Atlas veri entegrasyonu
- [ ] Bildirim sistemi (tercih dönemi hatırlatmaları)
- [ ] Kullanıcı hesabı senkronizasyonu
- [ ] Daha fazla karşılaştırma kriteri

---

## 📄 Lisans

Bu proje [MIT Lisansı](LICENSE) ile lisanslanmıştır.

---

## 🤝 Katkıda Bulunma

Katkılarınızı memnuniyetle karşılarız! Bir pull request açmadan önce lütfen bir issue oluşturarak neyi değiştirmek istediğinizi tartışın.
