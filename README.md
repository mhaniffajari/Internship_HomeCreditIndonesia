# Business Understanding
## Problem Statement

HomeCreditIndonesia memiliki 9,01% default kreditur. Permasalahan tersebut dapat menyebabkan kerugian Rp2.171.363.980,50. Perusahaan ingin Tim Data Scientist berkolaborasi dengan Tim Credit Analyst untuk menyelsaikan masalah tersebut.
## Goals and Objective

Tim sepakat untuk membuat model credit risk untuk mengurangi jumlah default kreditur dan kerugian. Model ini juga bisa menghasilkan credit scoring untuk tambahan pertimbangan menentukan kredit limit, interest rate ataupun term pada loan applicant.

# Feature Engineering and Data Preprocessing

Feature engineering bertujuan untuk melengkapi fitur yang sudah ada di application test. Tim Data Science mendapatkan data historical applicant dari pemerintah, financial lending lain ataupun sumber internal. Data-data tersebut akan melengkapi fitur yang ada.

Banyak data yang tidak lengkap atau tidak terisi sehingga dianggap sebagai null values. Oleh karena itu untuk Handling Missing Value tim data scientist melakukan imputasi. Kemudian dilakukan transformasi dengan metode WeightofEvidence (WOE). Lalu, data yang memiliki korelasi kuat dengan banyak variabel akan didrop karena akan menyebabkan multicollineriaty.

# Modelling
