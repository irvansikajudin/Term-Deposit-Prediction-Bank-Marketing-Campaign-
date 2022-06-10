
##<h2>Title</h2>
Bank Marketing Campaign - Predict Term Deposit (deposito).

selamat datang di project saya, saya Irvan Sikajudin, seorang Data Science enthusiast, project ini berisikan beberapa proses, mulai dari Data Understanding, EDA, Deep dive EDA, Data Prepocessing, Split Data to Train data and Test Data kemudian melatih beberapa model yang dianggap cocok dgn data yang ada,  yakni model K-NN classification, Random Forest, dan Decession Tree.

##<h2>Context and Source</h2>

<h2>Context</h2>
Find the best strategies to improve for the next marketing campaign. How can the financial institution have a greater effectiveness for future marketing campaigns? In order to answer this, we have to analyze the last marketing campaign the bank performed and identify the patterns that will help us find conclusions in order to develop future strategies.<br>

Temukan strategi terbaik untuk ditingkatkan untuk kampanye pemasaran berikutnya. Bagaimana lembaga keuangan memiliki efektivitas yang lebih besar untuk kampanye pemasaran di masa depan? Untuk menjawab ini, kami harus menganalisis kampanye pemasaran terakhir yang dilakukan bank dan mengidentifikasi pola yang akan membantu kami menemukan kesimpulan untuk mengembangkan strategi masa depan.<br>

<h2>Source</h2>
[Moro et al., 2014] S. Moro, P. Cortez and P. Rita. A Data-Driven Approach to Predict the Success of Bank Telemarketing. Decision Support Systems, Elsevier, 62:22-31, June 2014

Dataset is about Bank campaign dataset obtained from Kaggle and licensed under CC0: Public Domain.

## Idea of The Project
The idea of ​​this project is to find out the characteristics of a campaign that can be relied on to make customers subscribe to term deposit and predict deposit

The dataset contains order-related columns, look at below for more information about columns

<table>
<thead><tr>
<th>Header</th>
<th>Definition</th>
</tr>
</thead>
<tbody>
<tr>
<td><code>Age</code></td>
<td>Age of customer</td>
</tr>
<tr>
<td><code>Job</code></td>
<td>Job of customer</td>
</tr>
<tr>
<td><code>Martial</code></td>
<td>Martial status of customer  </td>
</tr>
<tr>
<td><code>Education</code></td>
<td>Customer education level</td>
</tr>
<tr>
<td><code>Default</code></td>
<td>Has credit in default?</td>
</tr>
<tr>
<td><code>Housing</code></td>
<td>If costumer has housing loan</td>
</tr>
<tr>
<td><code>Loan</code></td>
<td>Has Personal Loan</td>
</tr>
<tr>
<td><code>Balance</code></td>
<td>Customer's individual balance</td>
</tr>
<tr>
<td><code>Contact</code></td>
<td>Communication type</td>
</tr>
<tr>
<td><code>Month</code></td>
<td>Last contact month of year </td>
</tr>
<tr>
<td><code>Day</code></td>
<td>Last contact day of the week</td>
</tr>
<tr>
<td><code>Duration</code></td>
<td>Last contact duration, in seconds</td>
</tr>
<tr>
<td><code>Campaign</code></td>
<td>Number of contacts performed during this campaign and for this client</td>
</tr>
<tr>
<td><code>Pdays</code></td>
<td>Number of days that passed by after the client was last contacted from a previous campaign</td>
</tr>
<tr>
<td><code>Previous</code></td>
<td>Number of contacts performed before this campaign and for this client</td>
</tr>
<tr>
<td><code>Poutcome</code></td>
<td>outcome of the previous marketing campaign </td>
</tr>
<tr>
<td><code>Deposit</code></td>
<td>has the client subscribed a term deposit</td>
</tr>
</tbody>
</table>


## <h2>Creative Marketing Ideas for Banks:</h2>


*   Location-Based Advertising
*   Gamification in FinTech
*   Make Customer Service Fun!
*   Highlight Success Stories
*   Social Media Personality
*   Partnerships
*   Reward Users for Engagement



#Kesimpulan</br>
*   model terbaik K-NN dan Random Forest, karena dua model ini berhasil memprediksi yang benar-benar akan term deposit paling tinggi serta menghindari model Decision Tree yang biasanya cendrung overfit</br>

*   sehingga dengan model yang lebih peka terhadap orang yang akan melakukan term deposit maka kampanye marketing dapat lebih maksimal dilakukan  dengan mendekati orang-orang yang memiliki kriteria atau cendrung melakukan term deposit dgn berbagai metode marketing yang sesuai.</br> 

*   namun untuk perhitungan yang lebih cepat sebaiknya saya melakukan data scaling dan agar beban perhitungan lebih murah.</br>

*   Pada beberapa literatur dijelaskan bahwa outliers akan berpengaruh pada klasifikasi, dengan mengolah outlier(dihapus/metode lainnya) akan meningkatkan akurasi dari model klasifikasi algoritme kNN, namun syangnya penulis belum mampu untuk menerapkan metode tersbut, untuk metode penghapusan outlier penulis rasa kurang tepat dilakukan karena dataset yg digunakan akan berkurang sangat bnyak nantinya.



# Rekomendasi untuk Marketing Dept

demi tercapatinya peningkatan pelanggan yg melakukan term deposit, maka pertimbangkan beberapa hal sebagai berikut :</br>
*   Pertimbangkan untuk malakukan kampanye pada usia 30 an.
*   Pertimbangkan untuk malakukan kampanye pada pasangan yang tidak bercerai.
*   Pertimbangkan untuk melakukan kampanye pada pelanggan yang tidak memiliki Loans(Pinjaman) serta menghindari pelanggan yg memiliki pinjaman.</br>
*   Pertimbangkan untuk melihat tingkat saldo pada setiap profesi, usahakan untuk lebih banyak mendekati pelanggan yg bekerja di rana management.</br>
*   Tidak disarankan untuk campaign (menghubungi) pelanggan terlalu sering, karena semakin banyak menghubungi(melakukan kampanye/iklan) kepada pelanggan maka kesempatan utk pelanggan tersebut melakukan term deposit semakin mengecil.


