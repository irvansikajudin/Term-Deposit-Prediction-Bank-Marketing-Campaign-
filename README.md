
##<h2>Title</h2>
Bank Marketing Campaign - Predict Term Deposit (deposito).</br>

selamat datang di project saya, saya Irvan Sikajudin, seorang Data Science enthusiast, project ini berisikan beberapa proses, mulai dari Data Understanding, EDA, Deep dive EDA, Data Prepocessing, Split Data to Train data and Test Data kemudian melatih beberapa model yang dianggap cocok dgn data yang ada, menggunakan base model K-NN classification, Random Forest, dan Decession Tree., dan mentuning Random Forest.
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


![image](https://user-images.githubusercontent.com/41347634/176096942-23eaf3cc-cb8e-4d22-9507-addb1ba441b7.png)

solusi ketika ketika tidak melakukan pemisahan data menjadi Train-Validation-Test Dataset adalah dengan melakukan Cross Validation, dimana melakukan validation tanpa perlu memerlukan validation set terpisah. dataset tetap dibagi menjadi train dan test set, cross validation dilakukan pada train set, GridSearchCV & RandomSearchCV, saya menggunakan 5 sebagai K-Fold cros validation, terlebih lagi dataset yg saya gunakan tergolong tidak besar(tidak sampai jutaan), maka dari itu penggunaan cross validation masih dapat digunakan karena dataset saya kecil ukurannya, jika digunakan pada dataset yg jutaan akan memakan waktu yg sangat lama dan tidak bijak digunakan pada dataset besar. jika dataset besar hingga jutaan disarankan untuk menggunakan skema hyperparametertuning yg biasa (Train-validation-Test)
Hyperparametertuning untuk menghindari overfit

sumber grid Search CV link text

NOTE : GridSearchCV tidak memerlukan pembagian dataset menjadi train-validasi set, sumber :</br> <a href="https://www.researchgate.net/post/Should_I_first_split_the_data_into_train_and_validation_sets_and_then_use_GridSearchCV_on_the_training_set_followed_by_K_Fold_CV_on_my_training_set">Sumber 1</a></br>
<a href="https://www.quora.com/In-scikit-learn-in-GridSearchCV-can-I-manually-set-validation-set-examples-for-cross-validation">Sumber 2 : lebih detail lihat gambar dibawah.</a></br></br>
![image](https://user-images.githubusercontent.com/41347634/176102262-867208f8-0adf-479e-aad3-c0ab9c93a128.png)



