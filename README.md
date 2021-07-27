# New MEGA transfer after colab update!

## New notebook  

 [![Open In Colab](https://colab.research.google.com/github/jakiyaa/MEga-to-gdrive-transfer/blob/main/New_MEGA_%3C%3E_GDRIVE_.ipynb)


## 1.Download rclone to your local pc

 https://rclone.org/downloads/ 


## 2.Rclone Authenticate MEGA in your pc (NOT In colab)

![Screenshot 2021-07-27 193219](https://user-images.githubusercontent.com/67457538/127168563-727f4e9b-b3ef-4137-a3bf-c63fe551f384.png)

https://rclone.org/mega/  

## 3.GO to rclone.config in your pc

``` C:\Users\username\.config\rclone ```


![Screenshot 2021-07-27 195107](https://user-images.githubusercontent.com/67457538/127170840-fda3098c-3325-44ea-a379-772f571820de.png)


## 4.upload _rclone.config_ file to colab

![Screenshot 2021-07-27 194100](https://user-images.githubusercontent.com/67457538/127169048-d49739e5-746a-499c-975c-d868171e5e39.png)


## 5.copy _.config file_ to  root/rclone

``` !cp /content/rclone.conf /root/.config/rclone/rclone.conf  ```

![Screenshot 2021-07-27 185009](https://user-images.githubusercontent.com/67457538/127169647-59fbc723-c7ef-4955-b665-664e29fd3aa1.png)


## THEn you  can see your MEGA remote

![Screenshot 2021-07-27 193325](https://user-images.githubusercontent.com/67457538/127169714-aa14b177-595b-4b6e-92db-7012e4467d38.png)

## 6.NOw you can Mount MEGA

## 7.MEGA Mounted sucessfully

![Screenshot 2021-07-27 193458](https://user-images.githubusercontent.com/67457538/127169882-e4f074a7-2fa5-4278-a85d-b9d99a570dbf.png)
