# Guide for AId Core Solutioners

## 1. Araştırma ve Literatür Taraması
- **Her şeyin başı iyi bir literatür taraması yapmaktır.**
- **Makale bulma kaynakları:**
  - [Papers with Code](https://paperswithcode.com/)
  - [Google Scholar](https://scholar.google.com/)
  - [IEEE Xplore](https://ieeexplore.ieee.org/)

- **Bir makale buldunuz, sizi etkiledi mi?**  
  - Öncelikle makalenin iyi bir akademik dergide (journal) yayınlanıp yayınlanmadığını kontrol edin.  
  - Eğer makale iyi bir dergide değilse ya da güvenilirliği sorgulanabilir durumdaysa şu adımları izleyin:  
    - **İyi makaleleri nasıl bulabilirsiniz?**
      - [Scopus](https://www.scopus.com/)'a giriş yaptıktan sonra makaleyi 'document search' ten aratın. karşınıza çıkan satırda 'Source' sütununda yazan hangi dergide yayınlandığıdır. O derginin linkine tıklayın ve istatistiklerini görüntüleyin. CiteScore, SJR, SNIP ve Percentile skorlarının yüksek; Rank'ının düşük olması iyidir.
      - [Web of Science](https://clarivate.com/webofscience/)
      - Google Scholar üzerinde yüksek alıntı (citation) skorlarına sahip makalelere odaklanın.

---

## 2. Dataset Araştırma ve Kullanımı
- Dataset bulmak için önerilen kaynaklar:
  - [Kaggle](https://www.kaggle.com/datasets)
  - [Papers with Code](https://paperswithcode.com/datasets)
  - [IEEE Dataport](https://ieee-dataport.org/)
  - [Mendeley](https://data.mendeley.com/)
  - [Physionet](https://physionet.org/)

---

## 3. Kaggle Ortamı Kullanımı
- **Dikkat Edilmesi Gerekenler:**  
  - [when to use kaggle accelerators?](https://www.kaggle.com/code/borismbobe/when-to-use-kaggle-accelerators)
  - [How to submit fast during kernel outage?](https://www.kaggle.com/c/aptos2019-blindness-detection/discussion/102718#latest-593892)  
---

## 4. İTÜ-UHEM Ortamı Kullanımı
- [Altay sistemine iş vermek](https://wiki.uhem.itu.edu.tr/w/index.php?title=Altay_sistemine_i%C5%9F_vermek)  
- [Python, Anaconda, Tensorflow, Keras, Caffe Kullanım Kılavuzu](https://wiki.uhem.itu.edu.tr/w/index.php?title=Python,_Anaconda,_Tensorflow,_Keras,_Caffe_Kullan%C4%B1m_K%C4%B1lavuzu)
- Video ve başlangıç scriptleri yüklenecek

---

## 5. Tavsiye Edilen Yazılım ve Araçlar
- **IDE:**
  - Visual Studio Code (Opsiyonel, tercihinize bağlı)
- **Github Copilot Kullanımı:**
  - [GitHub Education Pack](https://education.github.com/pack) üzerinden ücretsiz olarak Copilot erişimi sağlayabilirsiniz.
- **AI chat bot:**
  - **[Poe](https://poe.com/)** ücretsiz limitli gpt, lama, claude sorgusu için
  - **[Google AI Studio](https://aistudio.google.com/)** ücretsiz limitsiz gemini pro sorgusu için

---

## 6. Kodlama Standartları ve İyi Uygulamalar
- **Kod Kalitesi:**  
  - Kodunuzun okunabilir ve sürdürülebilir olmasına özen gösterin.  
  - Kod yazarken şu standartlara uyun:  
    - PEP 8 (Python için)
    - Clean Code prensipleri  
  - **Code Review sürecine önem verin:** Başkalarının kodunu inceleyin ve kendi kodunuzu inceletin.  

- **Versiyon Kontrol Sistemleri:**  
  - Git kullanımı temel bir gerekliliktir. Eğer Git’e yabancıysanız, [Pro Git Kitabı](https://git-scm.com/book/en/v2) ile başlayabilirsiniz.  
  - Önerilen Git iş akışı:  
    - Merge request ve pull request süreçlerini öğrenin.  

- **Kullandığımız proje yönetim araçları:**  
  - **Trello / Jira / ClickUp:** Görevlerinizi takip etmek ve ekibinizle koordinasyon sağlamak için kullanacağız.  
  - Görevler, sprintler ve teslim tarihleri hakkında bilgi sahibi olun.
  - Hızlı iterasyonlar ve düzenli geri bildirimle çalışıyoruz.
---

## 7. Eğitim ve Gelişim Kaynakları
- **Online Eğitim Platformları:**  
  - [Coursera](https://www.coursera.org/) (Özellikle Andrew Ng'nin derslerini öneriyoruz.)  
  - [edX](https://www.edx.org/)  
  - [Udemy](https://www.udemy.com/)  

- **Video Kanalları:**  
  - The Coding Train (YouTube)  
  - StatQuest with Josh Starmer  

---

## 8. Dokümantasyon ve Öğrenilenlerin Paylaşımı
- **Dokümantasyon Alışkanlığı:**  
  - Projelerde yazılan kod ve kullanılan metodolojiler hakkında düzenli dokümantasyon yazın.  
  - Not almak için Notion, Latex ya da Google Docs gibi araçları kullanabilirsiniz.  
- **Bilgi Paylaşımı:**  
  - Haftalık bilgi paylaşım oturumları düzenlenecek. Öğrendiğiniz yeni bir teknolojiyi ya da yöntemleri ekibinizle paylaşmaya özen gösterin.  

---

## 9. Problem Çözme ve Debugging Araçları
- **Debugging Araçları:**  
  - Python için: PDB, PyCharm Debugger  
  - Loglama: Python `logging` modülü, TensorFlow Debugger (tfdbg)  
- **Problem Çözme Teknikleri:**  
  - Sorunu daha küçük parçalara bölün ve adım adım test edin.  
  - StackOverflow, GitHub Issues gibi topluluk kaynaklarından faydalanın.  

---

## 10. Performans ve Verimlilik
- **Kod Optimizasyonu:**  
  - Kodunuzu gereksiz döngüler ve fonksiyon çağrılarından arındırın.  
  - Profiling araçlarını (örneğin, cProfile) kullanarak darboğazları tespit edin.  
- **Kişisel Verimlilik Araçları:**  
  - Pomodoro tekniği ile odaklanma alışkanlığı kazanın.  
  - İş süreçlerinizi organize etmek için Todoist veya Notion gibi araçları kullanın.

---

Bu rehber, AId Core Solutions ekibine yeni katılan yazılımcılar için bir başlangıç noktasıdır. Sorularınız ya da önerileriniz için ekip liderinizle iletişime geçebilirsiniz. 🚀
