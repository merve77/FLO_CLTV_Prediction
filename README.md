# FLO CUSTOMER LIFETIME VALUE PREDICTION
FLO_CLTV_Prediction
# BG-NBD ve Gamma-Gamma ile CLTV Prediction
## İş Problemi 
FLO satış ve pazarlama faaliyetleri için roadmap belirlemek istemektedir. 
Şirketin orta uzun vadeli plan yapabilmesi için var olan müşterilerin gelecekte şirkete sağlayacakları potansiyel değerin tahmin edilmesi gerekmektedir.
## Veri Seti Hikayesi
Veri seti son alışverişlerini 2020 - 2021 yıllarında OmniChannel(hem online hem offline alışveriş yapan) 
olarak yapan müşterilerin geçmiş alışveriş davranışlarından elde edilen bilgilerden oluşmaktadır.
## Değişkenler
master_id: Eşsiz müşteri numarası <br/>
order_channel : Alışveriş yapılan platforma ait hangi kanalın kullanıldığı (Android, ios, Desktop, Mobile, Offline)  <br/>
last_order_channel : En son alışverişin yapıldığı kanal <br/>
first_order_date : Müşterinin yaptığı ilk alışveriş tarihi <br/>
last_order_date : Müşterinin yaptığı son alışveriş tarihi <br/>
last_order_date_online : Muşterinin online platformda yaptığı son alışveriş tarihi <br/>
last_order_date_offline : Muşterinin offline platformda yaptığı son alışveriş tarihi <br/>
order_num_total_ever_online : Müşterinin online platformda yaptığı toplam alışveriş sayısı <br/>
order_num_total_ever_offline : Müşterinin offline'da yaptığı toplam alışveriş sayısı <br/>
customer_value_total_ever_offline : Müşterinin offline alışverişlerinde ödediği toplam ücret <br/>
customer_value_total_ever_online : Müşterinin online alışverişlerinde ödediği toplam ücret <br/>
interested_in_categories_12 : Müşterinin son 12 ayda alışveriş yaptığı kategorilerin listesi <br/>
