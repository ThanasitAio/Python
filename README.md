# Python

## ดีงรูป instagram
```python
# ติดตั้ง cmd
## pip install instaloader

#แบบที่ 1 
import instaloader
ig = instaloader.Instaloader()
insta_page = input('ENTER USERNAME : ')
ig.download_profile(insta_page, profile_pic_only=False)

#แบบที่ 2
import instaloader
username = input("enter insta username : ")
instaloader.Instaloader().download_profile(username,profile_pic_only=False)
```
