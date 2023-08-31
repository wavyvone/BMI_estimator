# Introduction
League of Legends is a video game that has been played as an e-sport extremely
competitively for the past 11 years. We believe that players who prioritize their
physical health would display the best performance and consistency in their careers.
Therefore we hypothesized that using BMI as an indicator of health, the player’s
change in BMI vs their change in performance would be inversely related. To
estimate the player’s BMI, we built an AI model that uses pre-trained FaceNet
architecture sequential layers that produced a BMI. We trained the network on the
MORPH-II dataset and a dataset we produced from web-scraping totaling around
3000 total images. After 40 epochs, we achieved a mean absolute error of 2.37
achieving state-of-the-art performance. After running the model through our player
dataset, we could show general trends in career performances and BMI. Ultimately,
however, we were not able to show a correlation or statistical significance between
BMI change and performance.
