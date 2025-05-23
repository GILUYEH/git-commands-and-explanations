<h2 align="center">
  دستورات <a href="https://git-scm.com/doc">GIT</a> به همراه توضیحات مختصر آنها در اینجا قرار خواهند گرفت
<h2>

<div align="center">
  <img src="https://github.com/ahmad-mirzaei/git-commands-and-explanations/blob/2100aca18de101af32ed35f314d8c462dfd8dd29/git-logo-gif.gif">
</div>

---

<div align="center">
  <img src="https://github.com/ahmad-mirzaei/git-commands-and-explanations/blob/ae35ec9426f4bb320eefac7d94961e33acc729ff/red-line.gif">
</div>

### `git` : 
<p align="right">مشاهده ی دستورات گیت</p>
<hr>

### `git init`:  
<p align="right">معرفی کردن پروژه به گیت یا اینیشیالایز کردن آن</p>
<hr>

### `git status`:   
<p align="right">برای فهمیدن موقعیت فعلی فایل های پروژه که مثلا در کدام مرحله هستند</p>
<p align="right">(working directory | staging area | head)</p>

### `git status --short` or `git status -s`: 
<p align="right">برای فهمیدن موقعیت فعلی فایل های پروژه به صورت <b>خلاصه شده</b> که مثلا در کدام مرحله هستند</p>
<hr>

### `git add <file name>` : 
<p align="right"><b>فایل</b> مورد نظر را به مرحله ی <b>استیجینگ</b> می برد</p>
<p align="right">staging area</p>

### `git add .` : 
<p align="right"><b>تمامی</b> فایل ها و تغییرات پروژه را به مرحله ی استیجینگ می برد</p>
<hr>


### `git rm --cached <file name>` : 
<p align="right"><b>فایلی</b> که به مرحله ی استیجینگ اضافه شده را به مرحله ی <b>ورکینگ دایرکتوری</b> بر می گرداند </p>
<p align="right">(From staging area to working directory)</p>
<hr>

### `git commit -m <message>` :
<p align="right">فایل های پروژه که در مرحله ی استیجینگ قرار دارند را به یک پیغام مرتبط به مرحله ی نهایی یا هد، مخزن یا ریپوزیتوری می برد</p>
<p align="right">from staging area to HEAD or repositories</p>


<hr>
<!-- <p align="right"></p> -->
