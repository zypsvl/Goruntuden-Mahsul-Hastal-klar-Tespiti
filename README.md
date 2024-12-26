# Goruntuden-Mahsul-Hastaliklari-Tespiti
Toprak Verilerine Göre Mahsul Önerisi ve Sürdürülebilirlik İçin Mahsul Hastalıkları Tespiti
Açıklama
Bu proje, tarımda veri odaklı yaklaşımlar kullanarak tarımsal verimliliği artırmayı ve sürdürülebilir tarım uygulamalarını desteklemeyi amaçlamaktadır. Proje, iki ana hedefe odaklanmaktadır:

Toprak Verilerine Dayalı Mahsul Önerisi: Toprak bileşenleri ve çevresel faktörlere göre en uygun mahsulü öneren bir sistem geliştirilmiştir.
Bitki Hastalıkları Tespiti: Görüntü tabanlı bir sistemle, beş farklı bitki hastalığını tespit etmek için derin öğrenme modelleri kullanılmıştır.
Proje, tarımsal karar destek sistemleri için güçlü çözümler sunmayı hedeflemektedir.

Özellikler
Toprak Özellikleri ve Mahsul Önerisi: Azot, fosfor, potasyum, sıcaklık, nem gibi toprak ve çevresel faktörlere dayalı mahsul önerileri.
Bitki Hastalıkları Tespiti: Görüntü tabanlı sınıflandırma ile beş farklı bitki hastalığını tespit etme.
Makine Öğrenimi Modelleri: Gradient Boosting, Random Forest, XGBoost, MLP, ResNet50 gibi farklı makine öğrenimi ve derin öğrenme modelleri kullanılmıştır.
Yüksek Doğruluk Oranları: Proje, yüksek doğruluk ve verimlilik sağlamak için optimize edilmiş çeşitli modelleri içermektedir.
Veri Setleri
Proje iki ana veri seti kullanmaktadır:

Toprak Özellikleri ve Mahsul Önerisi Veri Seti: Toprağın kimyasal bileşenleri ve çevresel faktörleri içermektedir.
Bitki Hastalıkları Görüntü Veri Seti: Beş farklı bitki hastalığının sınıflandırılmasını içerir.
Kurulum
Depoyu klonlayın:

bash
Kodu kopyala
git clone https://github.com/kullaniciadi/projeadi.git
cd projeadi
Gereksinimleri yükleyin:

bash
Kodu kopyala
pip install -r requirements.txt
Kullanım
Veri setlerinizi hazırlayın ve uygun formata getirin.
Modeli eğitmek için main.py dosyasını çalıştırın:
bash
Kodu kopyala
python main.py
Eğitim tamamlandıktan sonra modelinizi kullanarak mahsul önerileri ve bitki hastalıklarını tespit edebilirsiniz.
Modellerin Performansı
Farklı modellerin başarıları değerlendirilmiş ve her bir modelin doğruluk, hassasiyet ve F1 skoru gibi metriklerle performansı ölçülmüştür. En iyi sonuçlar, Random Forest ve XGBoost gibi ağaç tabanlı yöntemlerden elde edilmiştir.

Gelecekteki Çalışmalar
Veri Setlerinin Genişletilmesi: Daha geniş ve çeşitli veri setleri ile model performansı artırılabilir.
Gerçek Zamanlı Uygulamalar: Modelin gerçek dünyada test edilmesi ve daha ileri seviyede geliştirilmesi.
Kullanıcı Dostu Araçlar: Son kullanıcılar için web ve mobil uygulamalar geliştirilebilir.
Katkı
Projeye katkıda bulunmak için bir sorun bildirisi açabilir veya pull request gönderebilirsiniz.

Lisans
Bu proje MIT Lisansı ile lisanslanmıştır.
