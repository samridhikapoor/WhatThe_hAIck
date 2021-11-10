
# Plant Disease Detection


## Introduction


It is very important to get an accurate diagnosis of plant diseases for global health and well being.
In this ever changing environment, identifying the disease including early prevention is important
to avoid problems that we might face otherwise. Some of these problems could have devastating
impacts on humanity including global shortage of food. It is crucial to prevent unnecessary waste of
financial resources achieving a healthier lifestyle, by addressing climate change from an ecological
perspective. It is difficult for the naked eye of a human being to catch all sorts of problems with plant
diseases. Also doing this time and time again is also laborious and unproductive work. In order to
achieve accurate plant disease detection, a plant pathologist should possess good observation skills
so that one can identify characteristic symptoms. An automated system designed to help identify
plant diseases by the plant’s appearance and visual symptoms could be of great help. This can be
deployed in agricultural fields so that the whole pipeline can be automated. This would not only lead
to better efficiency as machines could perform better than humans in these redundant tasks but also
improve the productivity of the farm. Our work solves the above mentioned problem of automating
plant disease classification using deep learning and computer vision techniques.

## Plant Disease Detection


Disease detection in plants plays an important role in agriculture as farmers have often to decide
whether the crop they are harvesting is good enough. It is of utmost importance to take these seriously
as it can lead to serious problems in plants due to which respective product quality, quantity or
productivity is affected. Plant diseases cause a periodic outbreak of diseases leading to large-scale
death which severely affects the economy. These problems need to be solved at the initial stage,
to save the lives and money of people. Automatic classification of plant diseases is an important research topic as it is important in monitoring large fields of crops and at a very early stage, if we can
detect the symptoms of diseases when they appear on plant leaves. This enables computer vision
algorithms to provide image-based automatic inspection. Comparatively, manual identification is
labor intensive, less accurate and can be done only in small areas at a time. By this method, the plant
diseases can be identified at the initial stage itself and the pest and infection control tools can be used
to solve pest problems while minimizing risks to people and the environment.



## About Dataset 

[link](https://www.kaggle.com/vipoooool/new-plant-diseases-dataset)

This dataset is recreated using offline augmentation from the original dataset. The original dataset can be found on [this](https://github.com/spMohanty/PlantVillage-Dataset) github repo. This dataset consists of about 87K rgb images of healthy and diseased crop leaves which is categorized into 38 different classes. The total dataset is divided into 80/20 ratio of training and validation set preserving the directory structure. A new directory containing 33 test images is created later for prediction purpose.

![App Screenshot](https://previews.dropbox.com/p/thumb/ABUiEu76wx9iCP6vVEY8yI3BkSttkT9BckhUqL0JR9fhtDI7pF5GzRfFx7bsfBcfUMFnqTWUhCetLIyLeYCORtngM8Ha3rFddRh01Dboz_ZrdgB5JdzObPNL97XthRGmuWrD4rPhxdYL7KOHmyg7P6xzrj657F0QyuGoElnSxpGC4o9o7h7ERIqxh9Ec20H_Gls1fFslVIOAQDkMB2jpy3Q1OwGxcc5A8oEhHFFR_zgIhok7PjtyXJtD0x08Y4Qq1xu_8DOGFE-4B_ziOo5ODRWc7_fysorlbxEB1EbGnSk0aZU0IHoUaM9VhSeKX25xim3hp664u_0mTlkIgR6P4-hYWtea7T1JNSiWb5_-Jok-aALbLd7iEV77bTFtDT1qj2Q/p.png?fv_content=true&size_mode=5)
![App Screenshot](https://previews.dropbox.com/p/thumb/ABXxMROj6qkt7Z20Y62tTtoW14NOxFzd5GiQk4yR0AlDOmEADXvQnQPBOvlOpN_j8RQOW2sj-DOcU7IFI2i1AR6nUUjM5r2FFqgiIXDQJIYIECjviIONwTNDrKWz6WD2k_U5OKeIGm87Kbale_cJ_y_ZYDzJRdto-VBh_E4v0SkaDRD6Hne5dpcoihVLAlN0V8xKq9_STb4aPtV7OYLMnZbWf60enLfUFTJk9PC8NDtfKUJf1SxKJp4maWESAFToakJHm3UQSJzyWkuVVUsTI61xs8C3nmI2CIfOTeVctkQcoAErtSmhO1_XyLCgraIvBs04nedELw3YLBAsGyG2i7sxdla2EVaR7icNlupnaDHRosbALJsxamdG7uVq-EFPt4U/p.png?fv_content=true&size_mode=5)







## Model architecture 

We used VGG19 for enhancing the accuracy of our model.

![App Screenshot](https://previews.dropbox.com/p/thumb/ABX2GpKQD32keQ6YdhnJ-rQfgz1Fh2UhvC9WlFBeLFfiVGGT87oOGEhejwgjauR6Fba3Gf-E28T0Ug51jwu-vkkjusBWLUvSPI8NHeta1N_jEIq7BuL3ZQV5RKk-JSFAZAncaild9W3yJSG0yJYG9ptp3cpHYUXkBNvH7vzLASD2s0Peb3Qsjyr9Yiz9rG_Dvgkoj67BxU67ZBz0xPGtLY16C2c2PvVg2-30subbdtHlV4kKoI64RkqgnhC9wnlkfcsg-pXdsA3DeTuBh0kKuPAcobCl6IS43WVktTotlt_1DRxa81v0CUuxefqLE-q7KEC9tL7pHLrftk_OFVpHfxIDeoXFNxgwf1vrAfR4Vkw9JvRLutDBVZjua5eUHFrZ6QA/p.jpeg?fv_content=true&size_mode=5)
## Loss and accuracy plot
![image](https://user-images.githubusercontent.com/81116984/141133320-518cb220-1ddd-492e-9eed-eefbc7993ffe.png)

## Results
Now the best models with best accuracy detects the brain tumor with accuracy

Accuracy 85%

![App Screenshot](https://previews.dropbox.com/p/thumb/ABVWkUzUXRCcmVLlk5SYu2rl-M8p0Be-89tRZJXNVFzzLTM2S27qj58qfpC8BjkzbLjyFAQ1Fjk-qN8S0LvQRHo0MTPF1043pKV5lRP6Fe2TVADgEmrBhj3l8DZcMWLbBLq-ohscZTxfZuPLe5TrUfouyxSnJk0S4rxg5EzU193ysP6Xdx0urg50QVXJuzcZDfWlIjNrShQE2oORM7g_jqxJzGW0rzll1S2T8AK4iGPtj4En6UB0fg3aO3EaK3x7JtOVZygqSdLzw_8Z_y-WMmN-SFznBH3Q1-hHlLgKTwVe-fg7HVEt_tkq8pbx9JJEXlzR_ptrbkht8K5PHXTbF7wzSrUm1q_3gI2OSwlyEUyCaqUF_ShA02OvpJRM_9S1nLQ/p.png?fv_content=true&size_mode=5)




DONUT CHART OF ACCURACY TABLE ->

![App Screenshot](https://previews.dropbox.com/p/thumb/ABUsvuLE4lOxOqIKuU168qU21G7bOEB_LbjKCmukFMpH5YV3NEaWm3PGNlIOr56wKBU-RrQ2nagcxzKPYGzndRJmI5VZpsBF0Kn7x6wqNkB4YbfMGqBTtQC_qzwqtgpscrjrreQzY8E944uGEUOGo7nfZJfDhS1m8h400ES8Ja4wV0y9MD9TcJ_DDbsHSH6YVrCr05Qylre6j1noTEcgN4389Ezk0aEoWTGkPwLCxdSaYeRP4zBwj_uysAxcfT9qxY8hYWj44QFTDRJeVRX0LcIypzfoC8n2SPwkow2icmUP3kIkRJIymE5VK6q46-aXaPtU_iaTr21EnbEQhokz1TwQm5rJyoEm88lV5Famu0d2L05b1rV2XQCQpr0a96lG3b0/p.png?fv_content=true&size_mode=5)
## Conclusion 

The model was successfully able to determine whether the plant whose image is provided has the disease or not and if yes,which disease the plant is suffering from.

Knowing if the plant is suffering with a disease we can conclude which pesticide should be selected for its further prevention.

## Challenges we ran into
1. Faced Diffilculty in finding a appropriate Data-set with large number of images
2. As a newbie to Machine learning domain it is very difficult to work with huge number of funtions and libraries.3)As we have used VGG 19 architure so most of the common inbuilt functions are not working , we have encounterd with number of errors , So finding new functions and there respective libraries is quite a troublesome.
3. As we have used VGG 19 architure so most of the common inbuilt functions are not working , we have encounterd with number of errors , So finding new functions and there respective libraries is quite a troublesome.
4. Faced Pixel Related issue for showing false result for Feed images
5. Had Trouble in deployment of our model on website , and linking backend with  the frontend
## Challenges we ran into
1. Faced Diffilculty in finding a appropriate Data-set with large number of images
2. As a newbie to Machine learning domain it is very difficult to work with huge number of funtions and libraries.3)As we have used VGG 19 architure so most of the common inbuilt functions are not working , we have encounterd with number of errors , So finding new functions and there respective libraries is quite a troublesome.
3. As we have used VGG 19 architure so most of the common inbuilt functions are not working , we have encounterd with number of errors , So finding new functions and there respective libraries is quite a troublesome.
4. Faced Pixel Related issue for showing false result for Feed images
5. Had Trouble in deployment of our model on website , and linking backend with  the frontend
## Contributors
[Nischay](https://github.com/NischayGoyal1)

[Samridhi](https://github.com/samridhikapoor)

[Niranjan](https://github.com/NiranjanHebli)

[Rohan](https://github.com/Rohan5202)
## Challenges we ran into
1. Faced Diffilculty in finding a appropriate Data-set with large number of images
2. As a newbie to Machine learning domain it is very difficult to work with huge number of funtions and libraries.3)As we have used VGG 19 architure so most of the common inbuilt functions are not working , we have encounterd with number of errors , So finding new functions and there respective libraries is quite a troublesome.
3. As we have used VGG 19 architure so most of the common inbuilt functions are not working , we have encounterd with number of errors , So finding new functions and there respective libraries is quite a troublesome.
4. Faced Pixel Related issue for showing false result for Feed images
5. Had Trouble in deployment of our model on website , and linking backend with  the frontend
## Conclusion 

The model was successfully able to determine whether the plant whose image is provided has the disease or not and if yes,which disease the plant is suffering from.

Knowing if the plant is suffering with a disease we can conclude which pesticide should be selected for its further prevention.
