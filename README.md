# 2022-1-OSSProj-DreamsComeTrue-4
## Team_DreamsComeTrue๐ญ
![Github license](https://img.shields.io/github/license/CSID-DGU/2022-1-OSSProj-DreamsComeTrue-4)
![badges](https://img.shields.io/badge/OS-ubuntu-red)
![badges](https://img.shields.io/badge/IDE-VSCode-informational)
![badges](https://img.shields.io/badge/python-3-blue)
![badges](https://img.shields.io/badge/pygame-2.0.2-yellow)
![Generic badge](https://img.shields.io/badge/pygame_menu-4.2.0-yellow.svg)
![Generic badge](https://img.shields.io/badge/pymysql-1.0.2-orange.svg)  

---
๐คช [์ด์๋](https://github.com/yaena1223) (ํ์ฅ) : ๊ฒฝ์์ ๋ณดํ๊ณผ 18ํ๋ฒ

๐ฅฐ [์ต๋คํฌ](https://github.com/daheeda) (ํ์) : ํต๊ณํ๊ณผ 19ํ๋ฒ

๐ [์ ๋ฏผ๊ฒฝ](https://github.com/kkong1007) (ํ์) : ํ๊ณต์๋ฌผ๊ณตํ๊ณผ 19ํ๋ฒ

---

![๋ก๊ทธ์ธ2](https://user-images.githubusercontent.com/77571090/173226976-b3931216-9b16-4b4a-8633-20877e6a0f3b.png)
<br/></br>์๋ํ์ธ์ ํ ๋๋ฆผ์ฆ์ปด์ธ๋ฅด ์๋๋ค : ) <br/>
pygame๋ฅผ ๊ธฐ๋ฐ์ผ๋ก ํ โ๋๋ฅ์ดโํ๋ง shooting game์๋๋ค.

<br/></br>
### How to run

---

1. python3 ์ค์น

```powershell
sudo apt-get update
sudo apt install python3
```

2. pygame, pygame_menu ์ค์น

```powershell
sudo pip3 install pygame==2.0.2
sudo pip3 install pygame_menu==4.2.0
```

3. pymysql ์ค์น

```powershell
sudo pip3 install pymysql==1.0.2
```

4. tkinter ์ค์น

```powershell
sudo apt-get install python3-tk
```

5. ๊ฒ์ ์คํ

```powershell
python3 Main.py
```

<br/></br>
### How to play

---

[Default]

![Untitled 1](https://user-images.githubusercontent.com/77571090/173226458-42aebf24-adb0-4114-a6f4-3965f8265fa1.png)

[PVP Game]

![Untitled 2](https://user-images.githubusercontent.com/77571090/173226507-7f20b997-f228-4524-a342-0950155b7a54.png)

<br/></br>
### Game preview

---

> ๋ก๊ทธ์ธ/ํ์๊ฐ์
> 

![Untitled 3](https://user-images.githubusercontent.com/77571090/173226588-f944264c-47ef-4dc5-b43e-0299c668f1b8.png)

- RDS ๋ฐ์ดํฐ๋ฒ ์ด์ค๋ฅผ ํตํด user ์ ๋ณด ์ ์ฅ
- ๋ก๊ทธ์ธ ๋ฒํผ ํด๋ฆญ ์ ์์ด๋ & ๋น๋ฐ๋ฒํธ ์๋ ฅ ํ login ๊ฐ๋ฅ

<br/>

> ๊ธฐ๋ณธ ๋ฉ๋ด ํ๋ฉด
> 

![Untitled 4](https://user-images.githubusercontent.com/77571090/173226613-11cc2f44-ff0e-484c-ad65-04d95198ba85.png)

- ๋ค๋ธ๋ฐ๋ฅผ ํตํด ์ํ๋ ํ์ด์ง ์ ๊ทผ ๊ฐ๋ฅ
- ๊ฒ์์ Stage๋ชจ๋์ Infinite๋ชจ๋๋ก ๊ตฌ์ฑ
- ๊ฒ์ ์ธ์ ๊ธฐ๋ฅ์๋ ์บ๋ฆญํฐ์์ , ๋ง์ดํ์ด์ง, ๋ญํน, ๋์๋ง, ์๋ฆฌon/off ๊ฐ ์์

<br/>

> Stage ๋ชจ๋ game
> 

![Untitled 5](https://user-images.githubusercontent.com/77571090/173226634-d00874f5-2f96-4844-b89e-87f1c7d9d42a.png)

- 3๊ฐ์ง map์ด ์์ผ๋ฉฐ ๊ฐ๊ฐ stage1,2,3์ผ๋ก ๊ตฌ์ฑ
- ๊ฒ์ ์์ ์ ๋ชฉํ์ ์ ์๋ด์ฐฝ ํ์ธ ๊ฐ๋ฅ

<br/>

> Infinite ๋ชจ๋ game
> 

![Untitled 6](https://user-images.githubusercontent.com/77571090/173226657-804ed977-00b7-4093-901f-c2cf7cecb3fa.png)

- 3๊ฐ์ง map์ผ๋ก ๊ตฌ์ฑ
- ๋ชฉ์จ์ด 0์ด ๋  ๊ฒฝ์ฐ ๊ฒ์ ์ข๋ฃ
- ๊ฒ์ ์ข๋ฃ ํ ์๋์ผ๋ก ๋ญํน์ด ๋ฑ๋ก๋จ
- ๋ฑ๋ก๋ ๋ญํน์ ๋ญํนํ์ด์ง์์ ํ์ธ ๊ฐ๋ฅ

<br/>

> PVP game
> 

![Untitled 7](https://user-images.githubusercontent.com/77571090/173226689-3ccc27fd-5318-4674-8582-475ce0d12dec.png)

- 2์ธ ํ๋ ์ด ๊ฒ์์ผ๋ก ๋ก๊ทธ์ธ ์์ด ์ด์ฉ ๊ฐ๋ฅ
- 120์ด์ ์ ํ ์๊ฐ ๋ด์ ๋ชฉ์จ์ด 0์ด ๋๊ฑฐ๋ ์ ํ์๊ฐ์ด ๋๋๋ฉด ๊ฒ์ ์ข๋ฃ

<br/>

> Mypage
> 

![Untitled 8](https://user-images.githubusercontent.com/77571090/173226699-8d68ec9c-68ec-447b-bc7f-93dc54df0759.png)

![Untitled 9](https://user-images.githubusercontent.com/77571090/173226704-4fddb9d8-63c5-4fcc-b9c9-64062c2048c7.png)

- ์์ด๋, ์ ์, ๋ณด์  ์ฝ์ธ, ๋ณด์  ์บ๋ฆญํฐ์ ๋ํ ์ ๋ณด ์ ๊ณต
- ์บ๋ฆญํฐ ์ ํ ๊ฐ๋ฅ

<br/>

> Character Store
> 

![Untitled 10](https://user-images.githubusercontent.com/77571090/173226710-060422c1-2444-49e6-91d6-8d7eb053f189.png)

- ์บ๋ฆญํฐ ์์ ์์๋ ๋ณด์ ํ ์ฝ์ธ์ผ๋ก ์บ๋ฆญํฐ ๊ตฌ๋งค ๊ฐ๋ฅ

<br/></br>
### Credits

---

- Sounds: [https://github.com/CSID-DGU/2021-2-OSSProj-PlusAlpha-9](https://github.com/CSID-DGU/2021-2-OSSProj-PlusAlpha-9)
- Character image: Copyright 2022. Jung Mingyeong
- Item image: Copyright 2022. Jung Mingyeong
- Background image: Copyright 2022. Choi Dahee
- Attacker image: Copyright 2022. Choi Dahee

<br/></br>
### References

---

- Origin Source: [https://github.com/CSID-DGU/2021-2-OSSProj-PlusAlpha-9](https://github.com/CSID-DGU/2021-2-OSSProj-PlusAlpha-9)
- Login/Signup Source:  https://github.com/CSID-DGU/2021-1-OSSPC-Tongsan1-2
