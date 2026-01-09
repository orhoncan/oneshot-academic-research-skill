# Academic Research Skill / Akademik Araştırma Skill'i

> 🇬🇧 **English** | 🇹🇷 **Türkçe**

---

## 🇬🇧 English

### Overview

A comprehensive Claude skill for deep academic literature research with 12-50+ sources through 5-15 iterative search cycles. Automatically detects your language and creates research notes in Obsidian markdown or PDF format with APA7 footnote citations.

### Key Features

- **Deep Coverage:** 12-50+ sources depending on research mode
- **Iterative Search:** 5-15 strategic search cycles with gap identification
- **Auto Language Detection:** Write in English → Get English output, Write in Turkish → Get Turkish output
- **Dual Format:** Choose Obsidian markdown (with vault integration) or PDF
- **Footnote Citations:** Clean APA7 citations using Obsidian's native footnote system
- **Visual Overviews:** Mindmap/concept map at the beginning of each note
- **Source Diversity Tracking:** Geographic, temporal, methodological, and perspective balance
- **Confidence Scoring:** 5-star research quality assessment

### Research Modes

| Mode | Sources | Search Cycles | Quality Target | Use Case |
|------|---------|---------------|----------------|----------|
| **Focused** | 12-18 | 5-7 | 50%+ high-impact | Narrow topics, quick overview |
| **Comprehensive** | 25-35 | 8-12 | 60%+ high-impact | Broad topics, thorough review |
| **Deep** | 40-50+ | 12-15+ | 65%+ high-impact | Very broad, exhaustive coverage |
| **Synthesis** | 15-25 | 6-9 | 55%+ high-impact | Comparative analysis (X vs Y) |

### Quick Start

1. **Install** the `.skill` file in Claude
2. **Ask** Claude to research a topic: *"Research cognitive load theory"*
3. **Answer** a few questions:
   - Format: Obsidian markdown or PDF?
   - Save location?
   - Vault search? (if Obsidian)
   - Any specific focus?
4. **Wait** while Claude performs 5-15 iterative search cycles
5. **Receive** a comprehensive research note with 12-50+ sources

### Iterative Search Process

**4-Phase Strategic System:**

1. **Broad Scan (Cycles 1-2):** Identify key concepts, major authors, seminal works
2. **Targeted Search (Cycles 3-5):** Find high-impact papers, meta-analyses, reviews
3. **Gap Filling (Cycles 6-8):** Locate critical perspectives, alternative views, contradictions
4. **Validation (Cycles 9+):** Verify claims, find recent work, practical applications

Each cycle: Search → Evaluate → Identify gaps → Plan next query → Cross-validate → Document → Repeat

### Output Structure

Every research note includes:

- **Visual Overview:** Mindmap showing key concepts and relationships
- **Source Metrics:** Quality distribution, geographic spread, temporal range
- **Confidence Score:** 5-star assessment of research quality
- **Main Content:** Organized by themes with subsections
- **Historical Development:** How the field evolved
- **Theoretical Frameworks:** Different perspectives and approaches
- **Methodological Analysis:** Research methods used in the field
- **Critical Discussion:** What we know, what's debated, what's missing
- **Application Areas:** Real-world uses
- **Research Gaps:** What needs more study
- **Footnote Citations:** Clean APA7 format using `[^1]` notation
- **Process Log:** Detailed documentation of search strategy

### Example Output Metrics

For "Cognitive Load Theory" (Comprehensive mode):
- **32 sources** (28 🟢 high-impact, 3 🟡 moderate, 1 🔴 limited)
- **10 search cycles** across 4 phases
- **Geographic:** 12 countries, 4 continents
- **Temporal:** 1988-2024 (60% within 5 years)
- **Methods:** 18 RCT, 4 meta-analyses, 6 theoretical, 4 qualitative
- **Perspectives:** Supporting + Critical + Alternative views

### Obsidian Integration

When you choose Obsidian format:

- **Vault Search:** Finds related notes already in your vault
- **Wikilinks:** Automatic `[[Note Name]]` links to related topics
- **MOC Integration:** Adds entry to your Map of Content if it exists
- **Smart Tags:** Suggests relevant tags (no # prefix, Obsidian adds it)
- **Dataview Metadata:** Custom fields for queries (`source_count`, `quality_score`, etc.)
- **TikZ etc. Support**

### Turkish Language Support

Full Turkish academic writing support:

- **Auto-Detection:** Write prompt in Turkish → Get Turkish output
- **Academic Language:** Proper Turkish academic style (formal, passive voice)
- **Natural Terminology:** "Ek aramalar" not "Takip aramaları", "Literatür haritası" not "Atıf manzarası"
- **Technical Terms:** Keeps English with Turkish explanation: "bilişsel yük (cognitive load)"
- **Spelling Rules:** Follows Turkish orthography and academic conventions

### File Naming

- **English:** `Cognitive Load Theory.md` (Title Case)
- **Turkish:** `Bilişsel Yük Kuramı.md` (Başlık Formatı)
- Always descriptive, never abbreviated (❌ "CLT.md")

### Continue Research

Can expand existing notes:
1. Say "continue researching [topic]" or "expand this note"
2. Claude loads the existing note
3. Identifies gaps from research log
4. Asks which gap to address
5. Performs 3-5 additional cycles
6. Integrates new findings
7. Updates metadata

### What Makes This Different

- **Truly Deep:** 25-50+ sources standard, not 10-15
- **Iterative:** Multiple search cycles with gap identification, not one-shot
- **Strategic:** 4-phase approach ensures comprehensive coverage
- **Balanced:** Requires multiple perspectives (supporting, critical, alternative)
- **Documented:** Every search cycle logged for transparency
- **Smart:** Auto-detects language and topic complexity

### Requirements

- Claude.ai, Claude desktop app, or Claude API access
- For Obsidian: Vault path (e.g., `/home/user/Documents/vault/`)
- For PDF: Save location

### Tips for Best Results

- **Be specific** about scope and exclusions
- **Trust the process:** 8-12 cycles takes 3-4 hours but produces deep coverage
- **Use Comprehensive mode** for thesis/dissertation literature reviews
- **Use Synthesis mode** for comparing theories or approaches
- **Continue research** to fill specific gaps later

---

## 🇹🇷 Türkçe

### Genel Bakış

Claude için kapsamlı akademik literatür araştırma skill'i. 5-15 iteratif arama döngüsü ile 12-50+ kaynak kullanır (bazen daha da fazla). Dilinizi otomatik algılar ve Obsidian markdown veya PDF formatında APA7 dipnotlu araştırma notları oluşturur. İsterseniz bitince komut vererek araştırmayı uzatabilirsiniz/derinleştirebilirsiniz.

### Ana Özellikler

- **Derin Kapsam:** Araştırma moduna göre 12-50+ kaynak
- **İteratif Arama:** Boşluk tespitli 5-15 stratejik arama döngüsü
- **Otomatik Dil Algılama:** Türkçe yazın → Türkçe çıktı alın, İngilizce yazın → İngilizce çıktı alın
- **Çift Format:** Obsidian markdown (vault entegrasyonlu) veya PDF
- **Dipnot Atıfları:** Obsidian'ın gömülü dipnot sistemiyle temiz APA7 atıflar
- **Görsel Genel Bakış:** Her notun başında kavram haritası/zihin haritası
- **Kaynak Çeşitliliği Takibi:** Coğrafi, zamansal, metodolojik ve perspektif dengesi
- **Güven Skoru:** 5 yıldızlı araştırma kalitesi değerlendirmesi

### Araştırma Modları

| Mod | Kaynak | Arama Döngüsü | Kalite Hedefi | Kullanım Alanı |
|-----|--------|---------------|---------------|----------------|
| **Odaklı** | 12-18 | 5-7 | %50+ yüksek etki | Dar konular, hızlı genel bakış |
| **Kapsamlı** | 25-35 | 8-12 | %60+ yüksek etki | Geniş konular, detaylı tarama |
| **Derin** | 40-50+ | 12-15+ | %65+ yüksek etki | Çok geniş, eksiksiz kapsam |
| **Sentez** | 15-25 | 6-9 | %55+ yüksek etki | Karşılaştırmalı analiz (X vs Y) |

### Hızlı Başlangıç

1. `.skill` dosyasını Claude'a **yükleyin**
2. Claude'dan bir konu araştırmasını **isteyin**: *"Bilişsel yük kuramını araştır"*
3. Birkaç soruyu **yanıtlayın**:
   - Format: Obsidian markdown mı PDF mi?
   - Kayıt yeri?
   - Vault araması? (Obsidian seçildiyse)
   - Belirli bir odak var mı?
4. Claude 5-15 iteratif arama döngüsü gerçekleştirirken **bekleyin**
5. 12-50+ kaynaklı kapsamlı araştırma notunu **alın**

### İteratif Arama Süreci

**4 Fazlı Stratejik Sistem:**

1. **Geniş Tarama (Döngü 1-2):** Ana kavramlar, önemli yazarlar, temel eserler
2. **Hedefli Arama (Döngü 3-5):** Yüksek etkili makaleler, meta-analizler, derlemeler
3. **Boşluk Doldurma (Döngü 6-8):** Eleştirel bakış açıları, alternatif görüşler, çelişkiler
4. **Doğrulama (Döngü 9+):** İddiaları teyit etme, son çalışmalar, pratik uygulamalar

Her döngü: Ara → Değerlendir → Boşlukları tespit et → Sonraki sorguyu planla → Çapraz doğrula → Belgele → Tekrarla

### Çıktı Yapısı

Her araştırma notu şunları içerir:

- **Görsel Genel Bakış:** Ana kavramları ve ilişkileri gösteren zihin haritası
- **Kaynak Metrikleri:** Kalite dağılımı, coğrafi yayılım, zaman aralığı
- **Güven Skoru:** 5 yıldızlı araştırma kalitesi değerlendirmesi
- **Ana İçerik:** Temalara göre düzenlenmiş alt bölümlerle
- **Tarihsel Gelişim:** Alanın nasıl evrildiği
- **Teorik Çerçeveler:** Farklı perspektifler ve yaklaşımlar
- **Metodolojik Analiz:** Alanda kullanılan araştırma yöntemleri
- **Eleştirel Tartışma:** Ne biliyoruz, neler tartışılıyor, neler eksik
- **Uygulama Alanları:** Gerçek dünya kullanımları
- **Araştırma Boşlukları:** Daha fazla çalışma gereken alanlar
- **Dipnot Atıfları:** `[^1]` notasyonuyla temiz APA7 formatı
- **Süreç Günlüğü:** Arama stratejisinin detaylı belgelenmesi

### Örnek Çıktı Metrikleri

"Bilişsel Yük Kuramı" için (Kapsamlı mod):
- **32 kaynak** (28 🟢 yüksek etki, 3 🟡 orta, 1 🔴 sınırlı)
- **10 arama döngüsü** 4 faz boyunca
- **Coğrafi:** 12 ülke, 4 kıta
- **Zamansal:** 1988-2024 (son 5 yılda %60)
- **Yöntemler:** 18 RCT, 4 meta-analiz, 6 teorik, 4 nitel
- **Perspektifler:** Destekleyici + Eleştirel + Alternatif görüşler

### Obsidian Entegrasyonu

Obsidian formatını seçtiğinizde:

- **Vault Araması:** Vault'unuzda zaten olan ilgili notları bulur
- **Wikilink'ler:** İlgili konulara otomatik `[[Not Adı]]` bağlantıları
- **MOC Entegrasyonu:** Varsa İçerik Haritanıza (MOC) giriş ekler
- **Akıllı Etiketler:** İlgili etiketler önerir (# ön eki yok, Obsidian ekler)
- **Dataview Metadatası:** Sorgular için özel alanlar (`source_count`, `quality_score`, vb.)
- **TikZ vb. Desteği**

### Türkçe Dil Desteği

Tam Türkçe akademik yazım desteği:

- **Otomatik Algılama:** Türkçe prompt yazın → Türkçe çıktı alın
- **Akademik Dil:** Doğru Türkçe ve akademik üslup (resmi, edilgen yapı)
- **Doğal Terminoloji:** "Ek aramalar" değil "Takip aramaları", "Literatür haritası" değil "Atıf manzarası" (dilin uyum sağlaması için özellikle)
- **Teknik Terimler:** İngilizce'yi Türkçe açıklamayla birlikte belirtir: "bilişsel yük (cognitive load)"
- **İmla Kuralları:** Türkçe yazım kuralları ve akademik gelenekleri takip eder

### Dosya İsimlendirme

- **İngilizce:** `Cognitive Load Theory.md` (Title Case)
- **Türkçe:** `Bilişsel Yük Kuramı.md` (Başlık Formatı)
- Her zaman açıklayıcı, asla kısaltılmış değil (❌ "BYK.md")

### Araştırmayı Sürdürme

Mevcut notları genişletebilir:
1. "araştırmayı sürdür [konu]" veya "bu notu genişlet" yazın
2. Claude mevcut notu yükler
3. Araştırma günlüğünden boşlukları tespit eder
4. Hangi boşluğun ele alınacağını sorar
5. 3-5 ek döngü gerçekleştirir
6. Yeni bulguları entegre eder
7. Metadatayı günceller

### Farkı Yaratan Özellikler

- **Derinlemesine Araştırma:** Standart 25-50+ kaynak (10-15 yerine)
- **İteratif:** Boşluk tespitli çoklu arama döngüleri (tek seferlik yerine)
- **Stratejik:** 4 fazlı yaklaşım kapsamlı ele alış sağlar
- **Dengeli:** Çoklu perspektifle bakar (destekleyici, eleştirel, alternatif)
- **Belgelenmiş:** Şeffaflık için her arama döngüsü kaydedilir
- **Akıllı:** Dil ve konu karmaşıklığını otomatik algılar

### Gereksinimler

- Claude.ai, Claude masaüstü uygulaması veya Claude API erişimi
- Obsidian için: Vault yolu (örn: `/home/user/Documents/vault/`)
- PDF için: Kayıt konumu

### En İyi Sonuçlar İçin İpuçları

- Kapsam ve hariç tutulacaklar konusunda **spesifik olun**
- **Süreci bekleyin:** Biraz vakit alıyor :) (en kapsamlı araştırma 4 saatlik kotanın %40'ı civarına denk geliyor)
- Tez/doktora literatür taramaları için **Kapsamlı mod kullanın**
- Teori veya yaklaşımları karşılaştırmak için **Sentez mod kullanın**
- Belirli boşlukları doldurmak için sonra **araştırmayı sürdürün**

---

## 📊 Comparison / Karşılaştırma

| Feature / Özellik | English | Türkçe |
|-------------------|---------|--------|
| **Auto Language Detection** / **Otomatik Dil Algılama** | ✅ | ✅ |
| **Obsidian Integration** / **Obsidian Entegrasyonu** | ✅ | ✅ |
| **PDF Export** / **PDF Dışa Aktarım** | ✅ | ✅ |
| **Footnote Citations** / **Dipnot Atıfları** | ✅ APA7 | ✅ APA7 |
| **Source Range** / **Kaynak Aralığı** | 12-50+ | 12-50+ |
| **Search Cycles** / **Arama Döngüleri** | 5-15 | 5-15 |
| **Academic Style** / **Akademik Üslup** | Formal | Resmi, Edilgen |
| **Visual Overviews** / **Görsel Genel Bakış** | Mindmaps | Zihin Haritaları |

---

## 🚀 Installation / Kurulum

1. Download / İndir: `academic-research-unified.skill`
2. Install in Claude / Claude'a yükle
3. Start researching / Araştırmaya başla!

---

## 📝 License / Lisans

MIT License - Free to use / Kullanımı ücretsiz

---

## 🤝 Contributing / Katkıda Bulunma

Feel free to fork!

---

## ⭐ Support / Destek

**English:** If this skill helps your research, please star the repository!

**Türkçe:** Bu beceri araştırmanıza yardımcı oluyorsa, lütfen repository'yi yıldızlayın!

--- 

# Sample Ouputputs / Örnek Çıktılar

[DeFi Markets in Türkiye](https://blog.orhon.net.tr/Ara%C5%9Ft%C4%B1rmalar/DeFi+and+Crypto+Markets+in+T%C3%BCrkiye) (English)
