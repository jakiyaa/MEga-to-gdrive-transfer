# MEga-to-gdrive-transfer
FILE transfer between MEGA &amp; GOOGLEDRIVE   transfer speed=1.5-3 MB/s


# NEw MEga tranfer after colab update!

1.Download rclone to your local pc
https://rclone.org/downloads/

2.Rclone Authenticate MEGA in your pc (NOT In colab)

![Screenshot 2021-07-27 193219](https://user-images.githubusercontent.com/67457538/127168563-727f4e9b-b3ef-4137-a3bf-c63fe551f384.png)


3.GO to rclone.config in your pc

path= C:\Users\username\.config\rclone

4.upload file to colab

![Screenshot 2021-07-27 194100](https://user-images.githubusercontent.com/67457538/127169048-d49739e5-746a-499c-975c-d868171e5e39.png)


5.copy .config file to  root/rclone

``` !cp /content/rclone.conf /root/.config/rclone/rclone.conf
```

6.NOw you can Mount MEGA
