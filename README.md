
# Customer Segmentation with Unsupervised Learning

<img src="https://github.com/baynazoglu/Customer-Segmentation-with-Unsupervised-Learning/blob/main/Customer-Segmentation.png" alt="Image" width="800" height="320">

The aim of this project is to segment customers of FLO, a company, and determine marketing strategies based on these segments. The goal is to create groups based on customers' behaviors and characteristics.

## Business Problem

FLO aims to better understand its customers and develop targeted marketing strategies. Segmenting customers into groups with similar characteristics based on their shopping behaviors will enable the company to provide personalized experiences to customers and optimize its marketing efforts. In this project, unsupervised learning techniques will be used to perform a segmentation analysis on the data derived from customers' shopping behaviors.

## Dataset Story

This dataset consists of historical shopping data of customers who made both online and offline purchases from FLO between 2020 and 2021. The dataset contains various variables related to customer behavior, and by analyzing these variables, customer segments will be created. 

The variables in the dataset are defined as follows:

- **master_id**: Unique customer identifier
- **order_channel**: Channel used for the purchase (Android, ios, Desktop, Mobile)
- **last_order_channel**: Channel used for the last purchase
- **first_order_date**: Date of the first purchase by the customer
- **last_order_date**: Date of the last purchase by the customer
- **last_order_date_online**: Date of the last online purchase by the customer
- **last_order_date_offline**: Date of the last offline purchase by the customer
- **order_num_total_ever_online**: Total number of purchases made by the customer on online platforms
- **order_num_total_ever_offline**: Total number of purchases made by the customer offline
- **customer_value_total_ever_offline**: Total amount spent by the customer on offline purchases
- **customer_value_total_ever_online**: Total amount spent by the customer on online purchases
- **interested_in_categories_12**: List of categories in which the customer has made purchases in the last 12 months

By performing unsupervised learning analysis on this dataset, the project aims to assist FLO in segmenting its customers into different groups and developing targeted marketing strategies based on the identified segments.

## Installation

1. Clone this project: `git clone https://github.com/YOUR_USERNAME/Feature-Engineering.git`
2. Navigate to the project directory: `cd Feature-Engineering`
3. Install the required dependencies: `pip install -r requirements.txt`
4. Run the project: `python main.py`

## Usage

1. Add the dataset to the "data" folder.
2. Run the project files.
3. Perform data analysis and feature engineering steps.
4. Develop a machine learning model to predict whether individuals have diabetes or not.
5. Evaluate the model's performance and analyze the results.

## Contributing

1. Fork this project.
2. Create a new branch: `git checkout -b feature/NewFeature`
3. Make your changes and commit them: `git commit -am 'Added a new feature'`
4. Push your branch to the forked repository: `git push origin feature/NewFeature`
5. Create a pull request.



--------------------------------------------

# Gözetimsiz Öğrenme ile Müşteri Segmentasyonu

Bu proje, FLO adlı bir şirketin müşterilerini segmentlere ayırarak pazarlama stratejilerini belirlemeyi amaçlamaktadır. Müşterilerin davranışlarını tanımlayarak bu davranışlara dayalı olarak gruplar oluşturulacaktır.

## İş Problemi

FLO, müşterilerini daha iyi anlamak ve hedef odaklı pazarlama stratejileri geliştirmek istemektedir. Müşterilerin alışveriş davranışlarını analiz ederek benzer özelliklere sahip gruplara segmentlere ayrılmaları, şirketin müşterilere özelleştirilmiş bir deneyim sunmasına ve pazarlama çabalarını optimize etmesine olanak tanıyacaktır. Bu projede, gözetimsiz öğrenme teknikleri kullanılarak, müşterilerin alışveriş davranışlarından elde edilen veriler üzerinde bir segmentasyon analizi gerçekleştirilecektir.

## Veri Seti Hikayesi

Bu veri seti, FLO müşterilerinin 2020-2021 yılları arasında gerçekleştirdikleri online ve offline alışverişlerine ait geçmiş verilerden oluşmaktadır. Veri setinde müşterilere ait farklı değişkenler bulunmaktadır ve bu değişkenlerin analizi yapılarak müşteri segmentleri oluşturulacaktır.

Veri setindeki değişkenlerin anlamları şu şekildedir:

- **master_id**: Eşsiz müşteri numarası
- **order_channel**: Alışveriş yapılan platforma ait hangi kanalın kullanıldığı (Android, ios, Desktop, Mobile)
- **last_order_channel**: En son alışverişin yapıldığı kanal
- **first_order_date**: Müşterinin yaptığı ilk alışveriş tarihi
- **last_order_date**: Müşterinin yaptığı son alışveriş tarihi
- **last_order_date_online**: Müşterinin online platformda yaptığı son alışveriş tarihi
- **last_order_date_offline**: Müşterinin offline platformda yaptığı son alışveriş tarihi
- **order_num_total_ever_online**: Müşterinin online platformda yaptığı toplam alışveriş sayısı
- **order_num_total_ever_offline**: Müşterinin offline'da yaptığı toplam alışveriş sayısı
- **customer_value_total_ever_offline**: Müşterinin offline alışverişlerinde ödediği toplam ücret
- **customer_value_total_ever_online**: Müşterinin online alışverişlerinde ödediği toplam ücret
- **interested_in_categories_12**: Müşterinin son 12 ayda alışveriş yaptığı kategorilerin listesi

Bu veri seti üzerinde gerçekleştirilecek gözetimsiz öğrenme analizi, FLO'nun müşterilerini farklı segmentlere ayırarak hedef odaklı pazarlama stratejileri geliştirmesine yardımcı olacaktır.

## Kurulum

1. Bu projeyi klonlayın: `git clone https://github.com/YOUR_USERNAME/Feature-Engineering.git`
2. Proje dizinine gidin: `cd Feature-Engineering`
3. Gerekli bağımlılıkları yükleyin: `pip install -r requirements.txt`
4. Projeyi çalıştırın: `python main.py`

## Kullanım

1. Veri setini "data" klasörüne ekleyin.
2. Proje dosyalarını çalıştırın.
3. Veri analizi ve özellik mühendisliği adımlarını gerçekleştirin.
4. Makine öğrenmesi modeli geliştirerek, kişilerin diyabet hastası olup olmadığını tahmin edin.
5. Modelin performansını değerlendirin ve sonuçları analiz edin.

## Katkıda Bulunma

1. Bu projeyi fork edin.
2. Yeni bir dal oluşturun: `git checkout -b feature/YeniOzellik`
3. Değişikliklerinizi yapın ve bunları kaydedin: `git commit -am 'Yeni bir özellik eklendi'`
4. Dalınızı forked repository'e gönderin: `git push origin feature/YeniOzellik`
5. Bir pull isteği oluşturun.



