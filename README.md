# VetAI

VetAI, çiftlik hayvanlarının sağlık ve davranış takibini kolaylaştırmak için geliştirilen yapay zeka destekli bir web platformudur. Proje; veteriner hekimlerin, çiftçilerin ve çiftlik yöneticilerinin sürü sağlığını ve hayvan doğumlarını tek panel üzerinden takip etmesini, riskleri erken fark etmesini ve kritik durumlarda hızlı aksiyon almasını hedefler.

## Özellikler

- Gerçek zamanlı davranış ve sağlık takibi
- Yeni doğan ve doğum süreci analizi
- Bölgesel salgın ve risk takibi
- Akıllı aşı ve bakım yönetimi
- Yapay zeka destekli veteriner asistanı
- Kritik uyarılar için Telegram bildirimi
- Türkçe arayüz ve kullanıcı odaklı panel deneyimi

## Kullanılan Teknolojiler

- Next.js 15
- React 18
- TypeScript
- Tailwind CSS
- Firebase Studio
- Genkit AI
- Google Gemini
- TensorFlow.js
- MapLibre / React Map GL
- Telegram Bot API

## Yapay Zeka Özellikleri

Projede Genkit ve Google Gemini modeli kullanılarak çeşitli yapay zeka akışları hazırlanmıştır:

- Uyarı özetleme: Sistemden gelen hayvan sağlığı uyarılarını özetler ve önerilen aksiyonları üretir.
- Yeni kullanıcı yönlendirmesi: Kullanıcının rolüne göre kişiselleştirilmiş başlangıç rehberi oluşturur.
- Doğum videosu analizi: İnek doğum belirtilerini video üzerinden analiz eder ve sonucu Türkçe açıklar.

## Proje Yapısı
src/
  ai/
    flows/              # Yapay zeka akışları
    genkit.ts           # Genkit yapılandırması
  app/                  # Next.js sayfaları
  components/           # Arayüz bileşenleri
  lib/                  # Yardımcı dosyalar
  services/             # Harici servis bağlantıları
  

