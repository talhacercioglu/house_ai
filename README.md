# Real Estate Price Prediction

## Overview

This project aims to predict real estate prices based on various input features such as location, property type, and physical attributes. The prediction model is trained using machine learning, specifically a gradient boosting model.

## Files

- `il_avg_label.txt`: Average price labels for cities.
- `il_id_label.json`: City IDs and corresponding labels.
- `ilce_avg_label.txt`: Average price labels for districts.
- `ilce_id_label.json`: District IDs and corresponding labels.
- `mahalle_avg_label.txt`: Average price labels for neighborhoods.
- `mahalle_id_label.json`: Neighborhood IDs and corresponding labels.
- `konut_tipi_id_label.json`: Property type IDs and corresponding labels.
- `bulundugu_kat_id_label.json`: Floor IDs and corresponding labels.
- `konut_kat_kombinasyon_id_label.json`: Combination of property type and floor IDs with corresponding labels.
- `gradient_boosting_model_2.pkl`: Trained gradient boosting model.

## Prerequisites

Before running the prediction script, make sure you have the following installed:

- Python
- Required Python packages (NumPy, pandas, scikit-learn, joblib)

Install the necessary packages using the following command:

```bash
pip install numpy pandas scikit-learn joblib

## Usage
Clone the repository:
git clone https://github.com/yourusername/your-repository.git

--------------------------------------------------------------------------------------------------------------------------------
# Emlak Fiyat Tahmini

## Genel Bakış

Bu proje, konum, mülk türü ve fiziksel özellikler gibi çeşitli girdi özelliklerine dayanarak emlak fiyatlarını tahmin etmeyi amaçlamaktadır. Tahmin modeli, özellikle bir gradient boosting modeli kullanılarak eğitilmiştir.

## Dosyalar

- `il_avg_label.txt`: Şehirler için ortalama fiyat etiketleri.
- `il_id_label.json`: Şehir ID'leri ve ilgili etiketler.
- `ilce_avg_label.txt`: İlçeler için ortalama fiyat etiketleri.
- `ilce_id_label.json`: İlçe ID'leri ve ilgili etiketler.
- `mahalle_avg_label.txt`: Mahalleler için ortalama fiyat etiketleri.
- `mahalle_id_label.json`: Mahalle ID'leri ve ilgili etiketler.
- `konut_tipi_id_label.json`: Mülk türü ID'leri ve ilgili etiketler.
- `bulundugu_kat_id_label.json`: Kat ID'leri ve ilgili etiketler.
- `konut_kat_kombinasyon_id_label.json`: Mülk türü ve kat ID'lerinin kombinasyonu ile ilgili etiketler.
- `gradient_boosting_model_2.pkl`: Eğitilmiş gradient boosting modeli.

## Gereksinimler

Tahmin betiğini çalıştırmadan önce aşağıdakilere sahip olduğunuzdan emin olun:

- Python
- Gerekli Python paketleri (NumPy, pandas, scikit-learn, joblib)

Aşağıdaki komutu kullanarak gerekli paketleri yükleyin:

```bash
pip install numpy pandas scikit-learn joblib

## Kullanım
Depoyu klonlayın:
git clone https://github.com/kullaniciadiniz/proje-reponuz.git
