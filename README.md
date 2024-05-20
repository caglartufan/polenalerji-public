# Ankara University Pollen Allergy Bulletin Website

## Link to the project

[Ankara Üniversitesi Polen Alerji Bülteni (https://polenalerji.ankara.edu.tr/)](https://polenalerji.ankara.edu.tr/)

## :pencil: About the project

I have developed this project while I was working as a part-time student at Ankara University IT Department. This website provides a 3-day pollen forecast of Ankara, capital of Türkiye. It also has nice features to provide useful information such as about the project team, pollens, a yearly pollen calender which shows what pollen is usualy at rise in what month of the year, technical details of the pollen measurement devices and tools, video archive to the visitors of the website. Website also has a minimal CMS integrated to create and share content related to types of pollens etc.

I have completed this project alone since it didn't have large amount of features to be integrated. To keep it simple and light-weight I preferred to depend on as little 3rd party library or tools as possible. Only 3rd party library or tool used in this project is CKEditor which is a WYSIWYG, rich text editor. Other than that everthing else is built with vanilla HTML, CSS & SCSS, JS, PHP & PDO, SQL, MsSQL Server. I used OOP and, applied clean coding practices and SOLID principles to increase maintainability and readibility of the codebase for future developers. I built an administration dashboard to manage and modify content of the website such as page contents (both generally-static pages such as "Hakkımızda (About Us)", "Polenler (Pollens)", "Basında Biz (Us in the Press)" and other dynamic pages) etc., navigation menu, general website settings such as social media links and page URLs, slider content, showcased photo & video. Data related weather forecast such as temperature, humidity, wind speed are pulled from the service provided by the MGM (Meteoroloji Genel Müdürlüğü or General Directorate of Meteorology) upon each request to website. Data related to pollen forecast is similarly pulled from the service provided by the MGM daily, using a cron job which updates and adds new entries to database to show on website.

**IMPORTANT NOTE:** This repository only contains a `README.md` file to describe the project in my Github profile. I can not share or add the codes to this repository due to privacy of the project.

## :microscope: Technologies used

HTML, CSS, SCSS, JS, CKEditor, PHP & PDO, OOP, SQL, MsSQL Server

## :art: Images from project

Homepage (Top part)

![polenalerji-homepage](https://github.com/caglartufan/polenalerji-public/assets/37420200/d31f317b-ad93-4408-a91a-ddaefcd9ebcb)

Homepage (Middle part)

![polenalerji-homepage-2](https://github.com/caglartufan/polenalerji-public/assets/37420200/a809fc82-0370-4e7d-9a8f-100429a32d17)

Homepage (Bottom part)

![polenalerji-homepage-3](https://github.com/caglartufan/polenalerji-public/assets/37420200/2a61e84f-4ea8-4f38-b84f-529c305eadf7)

Pollen Calendar Page

![polenalerji-pollen-calendar](https://github.com/caglartufan/polenalerji-public/assets/37420200/6ca6c86d-ce19-4d84-b806-ecb2fc82cab2)

A page created with CMS and enabled access through navbar menu

![polenalerji-a-page-created-with-CMS](https://github.com/caglartufan/polenalerji-public/assets/37420200/598cb0e1-582d-4bd7-bd9e-9ef89abf284e)

Us in the Press Page

![polenalerji-us-in-the-press-page](https://github.com/caglartufan/polenalerji-public/assets/37420200/c6f23e96-1ce5-40d1-a026-0d34124d85a0)

Video Archive Page

![polenalerji-video-archive-page](https://github.com/caglartufan/polenalerji-public/assets/37420200/42fbcfe9-f80f-4229-b28d-a8e998482deb)

Administration Login Page (I can't access the adminitrator dashboard, due to that reason I can't show how it looks)

![polenalerji-administration-login-page](https://github.com/caglartufan/polenalerji-public/assets/37420200/30f72718-9444-47c4-a10e-87d690bb43bc)

Hompeage (Mobile Responsive)

![polenalerji-mobile-homepage](https://github.com/caglartufan/polenalerji-public/assets/37420200/41c8466b-3ae1-4610-b74f-7fd1d6297467)

Homepage with Active Navbar Menu (Mobile Responsive)

![polenalerji-mobile-homepage-with-active-menu](https://github.com/caglartufan/polenalerji-public/assets/37420200/272d20db-9a9c-45f1-ad4a-af70a1e453c9)

## :dart: Gains

- :white_check_mark: Created a light-weight, optimised full-stack project from scratch.
- :white_check_mark: Practiced PHP, PDO, SQL and OOP.
- :white_check_mark: Implemented CKEditor which is a WYSIWYG, rich text editor to create a minimal CMS.
- :white_check_mark: Created a custom grid system and mixins in SCSS for responsiveness
- :white_check_mark: Modified `.htaccess` file to rewrite pages that are not available in file system to check if requested page is created with CMS, if not show 404 page.
