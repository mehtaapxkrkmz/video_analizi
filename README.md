# video_analizi
Evrim Ağacı youtube kanalının videolarını analiz ederek oluşturduğum veri setine k-means uygulanması.
# Video Analizi

Bu repo, YouTube video analizine yönelik verileri içeren bir projeyi barındırır. Proje, video beğeni sayıları ve yorum sayıları arasındaki ilişkiyi incelemeyi amaçlar. Veriler, https://www.youtube.com/channel/UCatnasFAiXUvWwH8NlSdd3A (Evrim Ağacı) youtube kanalından toplanan beğeni ve yorum sayılarını içeren bir CSV dosyasından alınmıştır. Projede Python ve Pandas kütüphanesi kullanılarak veriler işlenmiş ve KMeans kümeleme algoritması uygulanmıştır.

## İçerik

- **`video_analizi2.csv`**: Video beğeni ve yorum sayılarının yer aldığı veri seti.
- **`video_analizi2.ipynb`**: Verilerin işlenmesi, analiz edilmesi ve KMeans kümeleme algoritmasıyla analiz yapılması için kullanılan Jupyter Notebook dosyası.

## Kullanılan Kütüphaneler

- **Pandas**: Veri analizi ve işleme.
- **Scikit-learn**: KMeans kümeleme algoritması.
- **Matplotlib** (isteğe bağlı): Görselleştirme.

## Kullanım

### video_analizi2.ipynb dosyasını açarak veriyi analiz edebilirsiniz. Bu dosya, verileri okur, işlemler uygular ve KMeans algoritmasıyla kümeler oluşturur.
###Verilerin analizi sonrasında kümeler görselleştirilebilir. Notebook içinde gerekli grafikler ve analizler bulunmaktadır.
###Bu projeye katkıda bulunmak isterseniz, lütfen önce bir fork oluşturun ve ardından katkılarınızı pull request olarak gönderin. Herhangi bir hata raporlamak veya öneri sunmak için issues sekmesini kullanabilirsiniz.

###Bu proje, MIT Lisansı altında lisanslanmıştır. Ayrıntılar için LICENSE dosyasını inceleyebilirsiniz.

Projeyi çalıştırmadan önce, gerekli Python kütüphanelerinin yüklü olduğundan emin olun. Aşağıdaki komutu kullanarak kütüphaneleri yükleyebilirsiniz:
```bash
pip install pandas scikit-learn matplotlib






