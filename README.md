# Google-Playstore-Dataset -(Backup repo to store off Kaggle)
Google PlayStore App analytics. (2.3 Million App Data) and 24 attributes.

<img src="banner.jpg" width="700" height="180" />

I've collected the data with the help of Python and Scrapy running on a cloud vm.The data was collected on June 2021.

For latest dataset updates. Download from Kaggle: https://www.kaggle.com/gauthamp10/google-playstore-apps/

<br/>

## Instructions to combine the datasets
```
git clone https://github.com/gauthamp10/Google-Playstore-Dataset.git

cd Google-Playstore-Dataset/dataset/

for f in *.tar.gz; do tar -xvf "$f"; done

cat Part?.csv > Googple-Playstore-Dataset.csv

```

Also checkout the Android App Permission dataset: [https://github.com/gauthamp10/android-permissions-dataset](https://github.com/gauthamp10/android-permissions-dataset) 

<br/>

## __Author__

 **Gautham Prakash**
 
  My other projects: [github.com/gauthamp10](https://github.com/gauthamp10)

  Website: [gauthamp10.github.io](https://gauthamp10.github.io)

  Blog: [gauthamp10/blog](https://gauthamp10.github.io/#blog)

## __License__  

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
