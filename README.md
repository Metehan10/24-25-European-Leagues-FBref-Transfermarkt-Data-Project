
# 24-25-European-Leagues-FBref-Transfermarkt-Data-Project

📌 Proje Hakkında 

Bu repo, 2024/25 sezonu için şu liglerden toplanan verilerle oluşturulan bir çalışma içerir. Proje yalnızca eğitim/araştırma amaçlıdır. İlgili sitelerin kullanım şartlarına ve robots.txt kurallarına uyulmuştur. Toplu veri dağıtımı yapılmaz; kodlar aracılığıyla veriyi yerelde üretmeniz beklenir. 

Kapsam Dahilindeki Ligler:

- 🇬🇧 Premier League (İngiltere)

- 🇬🇧2 Championship (İngiltere)

- 🇪🇸 La Liga (İspanya)

- 🇫🇷 Ligue 1 (Fransa)

- 🇳🇱 Eredivisie (Hollanda)

- 🇧🇪 Pro League (Belçika)

- 🇮🇹 Serie A (İtalya)

- 🇵🇹 Primeira Liga (Portekiz)

- 🇩🇪 Bundesliga (Almanya)

--------------------------------------------------------------------
📊 Veri Kaynakları [FBref](https://fbref.com/) ve [Transfermarkt](https://www.transfermarkt.com/). 

- 🎯 Advanced Goalkeeping

- 🛡️ Defensive Actions

- 📋 Miscellaneous Stats

- 🎯 Passing

- 🗂 Passing Types

- ⏱ Playing Time

- 🔄 Possession

- 🎯 Shooting

------------------------------------------------------------------------

1.  Scraping ve İşleme Süreci

- Veri Toplama

  [📄 FbrefScraping.ipynb](FbrefScraping.ipynb) → FBref verilerinin çekilmesi
  
  [📄 TransfermarktScraping.ipynb](TransfermarktScraping.ipynb) → Transfermarkt verilerinin çekilmesi

- Veri Manipülasyonu
    
    [📄 FbrefGruplama.ipynb](notebooks/FbrefGruplama.ipynb) → Gruplama işlemleri
  
    [📄 FbrefConcat.ipynb](notebooks/FbrefConcat.ipynb) → Lig verilerinin birleştirilmesi (concat)
  
    [📄 FbrefDataFixing.ipynb](notebooks/FbrefDataFixing.ipynb) → Veri düzeltme adımları
  
    [📄 FbrefKolonİsimleriniUzatma.ipynb](notebooks/FbrefKolonİsimleriniUzatma.ipynb) → Pivot sonrası kolon adlarının tam forma çevrilmesi

    [📄 TransfermarktDataCleaning.ipynb](notebooks/TransfermarktDataCleaning.ipynb) → Veri temizleme adımları

2.  Veri Görselleştirme İşlemi
   
     [📄 Football.pbix](Football.pbix) → İşlenen verilerin Power BI aracılığıyla görselleştirilmesi
