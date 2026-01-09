# Bank Marketing Deposit Analysis

This project analyzes a bank marketing dataset to understand
which factors influence whether a customer opens a term deposit account.

## Dataset
The dataset includes customer demographics, financial attributes,
and marketing campaign information.

Target variable:
- deposit (yes / no)

## Exploratory Data Analysis
Key insights from the analysis:
- Age has a weak influence on deposit subscription.
- Customers with higher balances are more likely to open a deposit.
- Call duration is the strongest differentiating feature.
- Some categorical variables such as job and education show meaningful patterns.

## Modeling
A baseline Logistic Regression model was built using numerical features:
- age
- balance
- duration
- campaign

The model achieved approximately 71% accuracy on the test set.

Note: The duration feature may introduce data leakage and should be used
with caution in real-world prediction scenarios.

## Tools
- Python
- Pandas
- Matplotlib
- Scikit-learn


## Türkçe Açıklama

Bu proje, banka pazarlama verisi üzerinde keşifsel veri analizi
ve temel bir makine öğrenmesi modeli kurmayı amaçlamaktadır.

Çalışmada, müşterilerin vadeli mevduat hesabı açma kararını etkileyen
faktörler incelenmiştir.

Başlıca bulgular:
- Yaş değişkeninin etkisi zayıftır.
- Yüksek bakiyeye sahip müşterilerin mevduat açma olasılığı daha yüksektir.
- Görüşme süresi en ayırt edici değişkendir.

Modelleme aşamasında basit bir Lojistik Regresyon modeli kurulmuştur.

