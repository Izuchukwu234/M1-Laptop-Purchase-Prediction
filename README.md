<div class="sc-emEvRq gZqHzs sc-hGFITe jXToHY"><h1>M1 Laptop Purchase Prediction</h1>
<h2>Context</h2>
<p>The Apple M1 MacBook is a popular laptop that has gained a lot of attention in recent years due to its impressive performance and energy efficiency. If you are considering purchasing an M1 MacBook, there are several factors that you may want to consider before making your decision.</p>
<ul>
<li><p>One factor to consider is your budget. The M1 MacBook is available in a range of prices, depending on the specific model and configuration you choose. It's important to carefully consider your budget and choose a model that fits your needs and your financial situation.</p></li>
<li><p>Another factor to consider is your computing needs. The M1 MacBook is a powerful machine that is well-suited for a wide range of tasks, including running demanding software, playing games, and handling heavy workloads. However, if you only need a laptop for basic tasks like web browsing and word processing, you may be able to get by with a less powerful and less expensive model.</p></li>
<li><p>You may also want to consider the design and form factor of the M1 MacBook. The M1 MacBook is available in both 13-inch and 16-inch sizes, and you'll need to decide which size is right for you. Additionally, the M1 MacBook is available in both a standard laptop form factor and a more portable "MacBook Air" form factor.</p></li>
<li><p>Finally, you'll want to consider the availability and support options for the M1 MacBook. Apple is known for its strong support network, and the M1 MacBook is no exception. You can find support through Apple's online resources, as well as through authorized Apple service providers.</p></li>
</ul>
<h2>Content</h2>
<p>A quantitative methodology was used to conducted a survey for a period of 2 weeks across all social media channels for primary data collection. Therefore, the objective of this project is to determine which features are you going to use to understand purchasing behaviors. Think about the input dataset and output dataset that your model will have to give. </p>
<p>You might want to have a look at this study for some ideas: <a rel="noreferrer nofollow" target="_blank" href="https://www.kaggle.com/datasets/hunter0007/m1-data">M1 Purchase Prediction</a></p>
<h3>General features</h3>
<ul>
<li><p>trust_apple - Brand trust : (Yes, No)</p></li>
<li><p>Interest_computers - Level of interest in computers : (1 Not interested - 5 Very interested) </p></li>
<li><p>age_computer - Age of your current computer : (0 means less than one year -  6 years or more )</p></li>
<li><p>user_pc or mac - Type of computer : ( 0 PC , 1 Apple, 2 Hp or Other )</p></li>
<li><p>appleproducts_count - Count of apple products your own : (0 - 10 or more)</p></li>
<li><p>familiarity_m1 - Brand familiarity (Yes, No)</p></li>
</ul>
<h3>Apple M1 Macs features</h3>
<ul>
<li><p>f_batterylife - Importance of  (1 Not important - 5 is very import )</p></li>
<li><p>f_price - Cheaper price  (1 Not important - 5 is very import )</p></li>
<li><p>f_size - Thinner of computer (1 Not important - 5 is very import )</p></li>
<li><p>f_multitasking - Improved multitasking power (1 Not important - 5 is very import )</p></li>
<li><p>f_noise  - Less noisy (1 Not important - 5 is very import )</p></li>
<li><p>f_performance - Improved performance (1 Not important - 5 is very import )</p></li>
<li><p>f_neural - Neural engine  (1 Not important - 5 is very import )</p></li>
<li><p>f_synergy - How important is a seamless experience (1 Not important - 5 is very import )</p></li>
<li><p>f_performanceloss     - A small loss in performance (1 Not important - 5 is very import )</p></li>
<li><p>m1_consideration - M1 Chip into account in the selection process of buying a new Apple computer (1 Not important - 5 is very import )</p></li>
<li><p>m1_purchase - Would you buy one of the new Apple M1 Macs ( Yes,  No)</p></li>
</ul>
<h3>Demographic Features</h3>
<ul>
<li><p>gender </p></li>
<li><p>age_group </p></li>
<li><p>income_group</p></li>
<li><p>status</p></li>
<li><p>domain </p></li>
</ul></div>
<h2>Main Objective</h2>
<p>In this section, I am demonstrating the connection between various characteristics to identify the features that have the most significant impact on our target variable, 'm1_purchase.' Following that, I am constructing various classification models utilizing advanced methods like GridSearch, ML pipelines, and fine- tuning hyperparameters to attain the optimal predictive model in terms of accuracy. Furthermore, I will address the weaknesses of each model.</p>
<h2>Machine Learning Analysis</h2>
<p>In terms of simplicity, the Decision Tree model stands out because it provides strong predictive results while being the easiest and quickest to train due to its fewer parameters. On the contrary, models like K Nearest Neighbors (KNN) achieve optimal results with a K value of 3, but they are slower in the prediction phase because they need to calculate distances between all data points to classify each one. The Random Forest model also performs well, but its training process takes longer, mainly due to the grid search technique used to find the best parameters. This tradeoff implies that with larger datasets, these models may offer improved performance, but the training time will be longer. Ultimately, the model choice depends on your project's specific requirements, taking into account factors like dataset size, training time, and the desired level of predictive accuracy.</p>

<p>For more information on the Analysis, please see this here <a href=''>Analysis.pdf</a>.</p>
