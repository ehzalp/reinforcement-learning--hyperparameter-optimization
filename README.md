# YZR502 - Mobil Robot Navigasyonu için Takviyeli Öğrenme ile Hiperparametre Analizi

Bu repo, YZR502 Robotik Sistemler ve Algoritmalar dersi kapsamında hazırlanan **Mobil Robot Navigasyonu için Takviyeli Öğrenme ile Hiperparametre Analizi** ödevine ait kodları, eğitim çıktıları, modelleri ve grafik sonuçlarını içermektedir.

Çalışmada, MiniGrid ortamında bir mobil robotun hedefe ulaşma davranışı **PPO (Proximal Policy Optimization)** algoritması ile eğitilmiştir. Farklı hiperparametre ayarları kullanılarak öğrenme performansı karşılaştırılmıştır.

---

## Proje Amacı

Bu çalışmanın temel amacı, mobil robot navigasyonu problemini bir **Markov Karar Süreci (MDP)** olarak modellemek ve PPO algoritmasının farklı hiperparametre ayarları altındaki performansını analiz etmektir.

Bu kapsamda özellikle şu hiperparametrelerin etkisi incelenmiştir:

- Learning rate
- Gamma / discount factor
- Eğitim süresi
- Ortalama bölüm ödülü
- Öğrenme eğrilerinin kararlılığı

---

## Kullanılan Ortam

Çalışma tamamen **Google Colab** üzerinde yürütülmüştür. Yerel kurulum gerektirmez.

Kullanılan temel kütüphaneler:

```python
gymnasium
minigrid
stable-baselines3
matplotlib
numpy
pandas
