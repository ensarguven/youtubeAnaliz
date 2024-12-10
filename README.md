# youtubeAnaliz
# **YouTube Video Performansı Analizi**

Bu proje, YouTube Data API kullanılarak YouTube videolarının performansını analiz etmeyi amaçlar. Proje kapsamında, farklı kategorilerdeki videoların görüntüleme, beğeni, yorum gibi metrikleri toplanmış ve analiz edilmiştir. Ayrıca, elde edilen veriler görselleştirilerek her kategorinin popülerlik ve etkileşim düzeyi karşılaştırılmıştır.

---

## **Projenin Amacı**

Bu projede şu sorulara yanıt aranmıştır:
1. Hangi kategoriler daha fazla görüntüleme alıyor?
2. Hangi kategorilerde kullanıcılar daha fazla etkileşim kuruyor (beğeni/görüntüleme oranı)?
3. Videoların yayınlanma tarihleri ve etkileşim oranları arasında bir ilişki var mı?

---

## **Proje Adımları**

### 1. **Veri Toplama**
- YouTube Data API v3 kullanılarak farklı video kategorilerindeki en popüler videolara ilişkin veriler çekilmiştir.
- Toplanan verilerde şu bilgiler yer almaktadır:
  - Video başlıkları
  - Kategori
  - Görüntüleme sayısı
  - Beğeni sayısı
  - Yorum sayısı
  - Yayınlanma tarihi
  - Beğeni/Görüntüleme oranı

### 2. **Veri Temizleme**
- Eksik değerler kontrol edilip, gerekli düzeltmeler yapılmıştır.
- Aykırı değerlerin etkisi incelenmiş ve analiz için uygun veri seti oluşturulmuştur.
- Veriler, daha anlamlı analizler için `pandas` ile yeniden işlenmiştir.

### 3. **Analiz ve Görselleştirme**
- **Kategorilere Göre Görüntüleme ve Beğeni Dağılımı**:
  - Hangi kategorilerin daha fazla görüntüleme ve beğeni aldığı analiz edilmiştir.
- **Beğeni/Görüntüleme Oranı**:
  - Kullanıcıların hangi kategorilerde daha fazla etkileşim kurduğu incelenmiştir.
- **Zaman Serisi Analizi**:
  - Videoların yayınlanma tarihine göre etkileşim oranları ve görüntüleme sayılarına ilişkin trendler incelenmiştir.
- **Kutu Grafikler**:
  - Kategorilere göre beğeni ve yorum dağılımları görselleştirilmiştir.

---

## **Kullanılan Araçlar ve Kütüphaneler**
- **Python**:
  - `pandas`: Veri işleme ve analiz
  - `numpy`: Matematiksel işlemler
  - `matplotlib` ve `seaborn`: Veri görselleştirme
- **YouTube Data API v3**:
  - Verileri toplamak için kullanıldı.
- **Jupyter Notebook**:
  - Analizlerin interaktif bir şekilde yürütülmesi için tercih edildi.

---

## **Sonuçlar**
1. **Popüler Kategoriler**: Bazı kategoriler (ör. Music, Sports) diğerlerinden daha fazla görüntüleme ve etkileşim aldı.
2. **Beğeni/Görüntüleme Oranı**: Etkileşim oranları kategoriye göre büyük farklılıklar göstermektedir. Örneğin, bazı eğitici videolar daha yüksek beğeni oranına sahiptir.
3. **Trendler**: Yayınlanma tarihi, bazı kategorilerde görüntüleme sayıları üzerinde etkili olmuştur.

---



