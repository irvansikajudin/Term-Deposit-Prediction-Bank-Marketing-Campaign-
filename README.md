
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

[embed]https://doc-0g-bs-docs.googleusercontent.com/docs/securesc/893uroi8p2854gb54kce4j6mfdig05jb/buc02162l72kcecj6gae435413klmito/1656392925000/02466805747010670495/02466805747010670495/1VdLJsxH7IhMrJEoS9gcSahGhAlFvKaTM?e=download&ax=ACxEAsbWTuLp9xp47KA6YI8tNSr_N9yaj8DgW13vNzVdb9sNLaZNMu-BByvx7RKCYj5aFzREMtKtwQQ6SVJdNJuZhsFMixPJOXxyFwJT9iEdsG7A1tmCj8ntRoiNUtgLIGIOr_tfKeMH3yFr2RiWJpRvIy6ADskfpVTeG2-rppSd8cxvhxejslHrI6k87rc3abbS6ZlRO7c0A6Bwi4vTDx_GrRt2n5kQaZtE4D4s6iMNNbmLKnurxe0wak_LNi1_viFosVt2CMG8Jf1v_hQ531uHR9XhtE1E2HmUIdUKRY3sCux99HOYlZpSgj8FvaK039IHYR9upPXmRuj5DiDMzfPqEstQzI8_cLN2Jb_d7Oa_KlR4DC5KHTtT8-B1SmqcAPqHYG4JrZCKouuQ0jEMk6fI6ursn4VhE6BWc0ghEV70RVE1WrowqYRudxtOzZk0iRpPLBJQ5f6vI2L6eMuGSQ6iceu82WsJf2oIOL5com_hyC9H41Lo5-lRAqpca6CGXM9InI1lGsI6_bZ2FZ99TLuC8EWyunchZXlg43huU9FOzxrafggGfZs8kqaAUSl8L0qvhquepJPeBsmY4NLkvjXpwZFfllLQQsL7M6as7Q8FMb8VJGXaYwl9D98urGUNZvveJ3_IgMzpnxbDSgEnJwaOTxNWIkIMuU3PHvxJx9X-3i38ZolfsYXUcQS2EaNfzt6fKoPOTymkl9CX8kQVU4MJ5OwWo6G-wvYymFtJBWxQGGXbgKyahNz8-ffVjl_ZuVK7qz-wu6rGdTqRwzvKWR6Tm1vJ&authuser=0&nonce=kmk9dh7iljlue&user=02466805747010670495&hash=e83ko13b3kmuuvuvfvaf52tm96ig6p11[/embed]



