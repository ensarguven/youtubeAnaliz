# youtubeAnaliz
Bu proje, YouTube Data API kullanılarak YouTube videolarının performansını analiz etmeyi amaçlar.
YouTube Video Performansı Analizi
Bu proje, YouTube Data API kullanılarak YouTube videolarının performansını analiz etmeyi amaçlar. Proje kapsamında, farklı kategorilerdeki videoların görüntüleme, beğeni, yorum gibi metrikleri toplanmış ve analiz edilmiştir. Ayrıca, elde edilen veriler görselleştirilerek her kategorinin popülerlik ve etkileşim düzeyi karşılaştırılmıştır.

Projenin Amacı
Bu projede şu sorulara yanıt aranmıştır:

Hangi kategoriler daha fazla görüntüleme alıyor?
Hangi kategorilerde kullanıcılar daha fazla etkileşim kuruyor (beğeni/görüntüleme oranı)?
Videoların yayınlanma tarihleri ve etkileşim oranları arasında bir ilişki var mı?
Proje Adımları
1. Veri Toplama
YouTube Data API v3 kullanılarak farklı video kategorilerindeki en popüler videolara ilişkin veriler çekilmiştir.
Toplanan verilerde şu bilgiler yer almaktadır:
Video başlıkları
Kategori
Görüntüleme sayısı
Beğeni sayısı
Yorum sayısı
Yayınlanma tarihi
Beğeni/Görüntüleme oranı
2. Veri Temizleme
Eksik değerler kontrol edilip, gerekli düzeltmeler yapılmıştır.
Aykırı değerlerin etkisi incelenmiş ve analiz için uygun veri seti oluşturulmuştur.
Veriler, daha anlamlı analizler için pandas ile yeniden işlenmiştir.
3. Analiz ve Görselleştirme
Kategorilere Göre Görüntüleme ve Beğeni Dağılımı:
Hangi kategorilerin daha fazla görüntüleme ve beğeni aldığı analiz edilmiştir.
Beğeni/Görüntüleme Oranı:
Kullanıcıların hangi kategorilerde daha fazla etkileşim kurduğu incelenmiştir.
Zaman Serisi Analizi:
Videoların yayınlanma tarihine göre etkileşim oranları ve görüntüleme sayılarına ilişkin trendler incelenmiştir.
Kutu Grafikler:
Kategorilere göre beğeni ve yorum dağılımları görselleştirilmiştir.
Kullanılan Araçlar ve Kütüphaneler
Python:
pandas: Veri işleme ve analiz
numpy: Matematiksel işlemler
matplotlib ve seaborn: Veri görselleştirme
YouTube Data API v3:
Verileri toplamak için kullanıldı.
Jupyter Notebook:
Analizlerin interaktif bir şekilde yürütülmesi için tercih edildi.
Sonuçlar
Popüler Kategoriler: Bazı kategoriler (ör. Music, Sports) diğerlerinden daha fazla görüntüleme ve etkileşim aldı.
Beğeni/Görüntüleme Oranı: Etkileşim oranları kategoriye göre büyük farklılıklar göstermektedir. Örneğin, bazı eğitici videolar daha yüksek beğeni oranına sahiptir.
Trendler: Yayınlanma tarihi, bazı kategorilerde görüntüleme sayıları üzerinde etkili olmuştur.
Projeyi Çalıştırma
Gereksinimler
Python 3.x
YouTube Data API anahtarı (API anahtarı almak için YouTube API Developer Guide rehberini takip edebilirsiniz).
Adımlar
Bu projeyi yerel bilgisayarınıza klonlayın:
bash
Copy code
git clone https://github.com/kullaniciadi/youtube-video-analiz.git
Gerekli Python kütüphanelerini yükleyin:
bash
Copy code
pip install -r requirements.txt
Projeyi çalıştırmak için notebook.ipynb dosyasını açın ve adım adım çalıştırın.
Gelecek Çalışmalar
Daha fazla veri çekmek için farklı bölgelerdeki (ör. regionCode="US", regionCode="TR") veriler analiz edilebilir.
Video başlıkları ve açıklamalarındaki metinleri analiz ederek, belirli anahtar kelimelerin etkisi incelenebilir.
Makine öğrenmesi yöntemleriyle video performansı tahmin modelleri geliştirilebilir.
Ekran Görüntüleri
Örnek Görselleştirme:
Kategorilere Göre Beğeni Dağılımı

