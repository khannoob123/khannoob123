- 👋 Hi, I’m @khannoob123
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
khannoob123/khannoob123 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
import time
password = "pass"
passw = ""
while passw != password:
    passw = input("enter your password: ")
    if passw != password:
        print("mật khẩu sai!!\n")
    else:
        print("****--------------------------------------------------***")

for i in range(0,109,10):
	print("just a moment...loading..." + str(i) + "%" )
	time.sleep(0.4)
print("\nbạn đã đăng nhập thành công\n")

with open("data.txt", "r") as file:
		line = file.read()

for x in line:
	print(x, end = "")
	time.sleep(0.001)
