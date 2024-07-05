"# Day-3-css" 
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dribbble Clone</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>
    <header>
        <div class="header-left">
            <div class="logo">DRIBBLE</div>
            <nav>
                <ul>
                    <li><a href="#">Shots</a></li>
                    <li><a href="#">Designers</a></li>
                    <li><a href="#">Teams</a></li>
                    <li><a href="#">Community</a></li>
                    <li><a href="#">Jobs</a></li>
                </ul>
            </nav>
        </div>
        <div class="header-right">
            <div class="auth">
                <a href="#">Sign up</a>
                <a href="#">Sign in</a>
            </div>
            <input type="text" placeholder="Search">
        </div>
    </header>
    <main>
        <div class="filter-bar">
            <div class="filter-elements">
                <h4 style="color: white">What are you working on?</h4>
                <h4 style="color: rgb(120, 117, 114);">&nbsp;Dribbble is show and tell for designers.</h4>
            </div>
            <div class="filter-options">
                <a href="#">Learn more</a>
                <a href="#" class="btn-signup">Sign up</a>
            </div>
        </div>

        <section class="shots-gallery">
            <!-- Repeat this block for each shot -->
            <div class="shot-item">
                <img src="https://cdn.dribbble.com/userupload/15400880/file/original-071b01bd1030c99498d9bcbb9d1dbb26.jpg?resize=1024x768" alt="Design 1">
                <div class="shot-info">
                    <p class="shot-title">Brad Hansen</p>
                    <div class="shot-meta">
                        <p><i class="fas fa-eye"></i> 1k</p>
                    <div class="shot-meta-1">
                        <p><i class="fas fa-heart"></i> 290</p>
                    </div>
                    </div>
                </div>
            </div>
            
            <!-- Add more shot items as needed -->
            <div class="shot-item">
                <img src="https://cdn.dribbble.com/userupload/15390293/file/original-d4dc8b0b025b571ffb3bd076523f7a36.jpg?resize=1024x772" alt="Design 1">
                <div class="shot-info">
                    <p class="shot-title">Coric Design</p>
                    <div class="shot-meta">
                        <p><i class="fas fa-eye"></i> 875</p>
                    <div class="shot-meta-1">
                        <p><i class="fas fa-heart"></i> 31</p>
                    </div>
                    </div>
                </div>
            </div>

            <div class="shot-item">
                <img src="https://cdn.dribbble.com/userupload/15403100/file/original-de59b96b67116df5eeb6f4d8a7dc64b9.jpg?resize=1024x768" alt="Design 1">
                <div class="shot-info">
                    <p class="shot-title">Orenji Studio</p>
                    <div class="shot-meta">
                        <p><i class="fas fa-eye"></i> 2k</p>
                    <div class="shot-meta-1">
                        <p><i class="fas fa-heart"></i> 51</p>
                    </div>
                    </div>
                </div>
            </div>

            <div class="shot-item">
                <img src="https://cdn.dribbble.com/userupload/15380095/file/original-c8479f373d5b721a3c6d829e2fc898ca.jpg?resize=1024x768" alt="Design 1">
                <div class="shot-info">
                    <p class="shot-title">Emote</p>
                    <div class="shot-meta">
                        <p><i class="fas fa-eye"></i> 6.2k</p>
                    <div class="shot-meta-1">
                        <p><i class="fas fa-heart"></i> 53</p>
                    </div>
                </div>
            </div>
        </div>

            <div class="shot-item">
                <img src="https://cdn.dribbble.com/userupload/15403399/file/original-b7361210bdb63945fae4f2b40a3a0270.png?resize=1024x754&vertical=center" alt="Design 1">
                <div class="shot-info">
                    <p class="shot-title">Vedant Hegde</p>
                    <div class="shot-meta">
                        <p><i class="fas fa-eye"></i> 6.7k</p>
                    <div class="shot-meta-1">
                        <p><i class="fas fa-heart"></i> 86</p>
                    </div>
                </div>
            </div>
        </div>

            <div class="shot-item">
                <img src="https://cdn.dribbble.com/userupload/15408506/file/original-03a0e69935f426c65f8a965a2ee9a872.png?resize=1024x768" alt="Design 1">
                <div class="shot-info">
                    <p class="shot-title">Rw Studio</p>
                    <div class="shot-meta">
                        <p><i class="fas fa-eye"></i> 1.7k</p>
                    <div class="shot-meta-1">
                        <p><i class="fas fa-heart"></i> 46</p>
                    </div>
                    </div>
                </div>
            </div>

            <div class="shot-item">
                <img src="https://cdn.dribbble.com/userupload/4048273/file/original-e103b524c3cc72ddbdcaf6bbf00c958d.gif" alt="Design 1">
                <div class="shot-info">
                    <p class="shot-title">ILLO</p>
                    <div class="shot-meta">
                        <p><i class="fas fa-eye"></i> 158k</p>
                    <div class="shot-meta-1">
                        <p><i class="fas fa-heart"></i> 524</p>
                    </div>
                </div>
            </div>
        </div>

            <div class="shot-item">
                <img src="https://cdn.dribbble.com/userupload/10828451/file/original-93b5e1248fc87bff9f9ffb77f3f4f0c8.gif" alt="Design 1">
                <div class="shot-info">
                    <p class="shot-title">PSYCHROME</p>
                    <div class="shot-meta">
                        <p><i class="fas fa-eye"></i> 21.7k</p>
                    <div class="shot-meta-1">
                        <p><i class="fas fa-heart"></i> 379</p>
                    </div>
                    </div>
                </div>
            </div>

            <div class="shot-item">
                <img src="https://cdn.dribbble.com/userupload/10350637/file/original-1a8ba78f4ae2c201536efeb4424492a6.gif" alt="Design 1">
                <div class="shot-info">
                    <p class="shot-title">Fireart Studio</p>
                    <div class="shot-meta">
                        <p><i class="fas fa-eye"></i> 35.1k</p>
                    <div class="shot-meta-1">
                        <p><i class="fas fa-heart"></i> 199</p>
                    </div>
                    </div>
                </div>
            </div>

            <div class="shot-item">
                <img src="https://cdn.dribbble.com/userupload/14521988/file/original-ec97466039b0833e7eee59716637f270.gif" alt="Design 1">
                <div class="shot-info">
                    <p class="shot-title">Jan Kallwejt</p>
                    <div class="shot-meta">
                        <p><i class="fas fa-eye"></i> 9.8k</p>
                    <div class="shot-meta-1">
                        <p><i class="fas fa-heart"></i> 84</p>
                    </div>
                    </div>
                </div>
            </div>

            <div class="shot-item">
                <img src="https://cdn.dribbble.com/userupload/9641401/file/original-3bf412c3dedf552aed5787c546f5d64a.gif" alt="Design 1">
                <div class="shot-info">
                    <p class="shot-title">MUTI</p>
                    <div class="shot-meta">
                        <p><i class="fas fa-eye"></i> 48.9k</p>
                    <div class="shot-meta-1">
                        <p><i class="fas fa-heart"></i> 218</p>
                    </div>
                </div>
                </div>
            </div>

            <div class="shot-item">
                <img src="https://cdn.dribbble.com/userupload/3963577/file/original-93ddbb771e951512ba9fbc5bfe473a2c.gif" alt="Design 1">
                <div class="shot-info">
                    <p class="shot-title">Cub Studio</p>
                    <div class="shot-meta">
                        <p><i class="fas fa-eye"></i> 81.8k</p>
                    <div class="shot-meta-1">
                        <p><i class="fas fa-heart"></i> 269</p>
                    </div>
                    </div>
                </div>
            </div>

            <div class="shot-item">
                <img src="https://cdn.dribbble.com/userupload/15404369/file/original-d8e017abacae058af40bb4b8d8011193.png?resize=1024x768" alt="Design 1">
                <div class="shot-info">
                    <p class="shot-title">Lucian Radu</p>
                    <div class="shot-meta">
                        <p><i class="fas fa-eye"></i> 4.2k</p>
                    <div class="shot-meta-1">
                        <p><i class="fas fa-heart"></i> 63</p>
                    </div>
                </div>
                </div>
            </div>

            <div class="shot-item">
                <img src="https://cdn.dribbble.com/userupload/15411411/file/original-d7fe69db80dd8e26c56adf5c848683e4.jpg?resize=1024x768" alt="Design 1">
                <div class="shot-info">
                    <p class="shot-title">MUTI</p>
                    <div class="shot-meta">
                        <p><i class="fas fa-eye"></i> 755</p>
                    <div class="shot-meta-1">
                        <p><i class="fas fa-heart"></i> 23</p>
                    </div>
                    </div>
                </div>
            </div>

            <div class="shot-item">
                <img src="https://cdn.dribbble.com/userupload/15400445/file/original-1f62c42db10d08d9a34f33e9d0d19b68.jpg?resize=1024x768" alt="Design 1">
                <div class="shot-info">
                    <p class="shot-title">Tommy Chandra</p>
                    <div class="shot-meta">
                        <p><i class="fas fa-eye"></i> 1.1k</p>
                    <div class="shot-meta-1">
                        <p><i class="fas fa-heart"></i> 28</p>
                    </div>
                    </div>
                </div>
            </div>

            <div class="shot-item">
                <img src="https://cdn.dribbble.com/userupload/15410841/file/original-d08b15d18b02ecc649aa3fd53211d094.png?resize=1024x768" alt="Design 1">
                <div class="shot-info">
                    <p class="shot-title">tubik</p>
                    <div class="shot-meta">
                        <p><i class="fas fa-eye"></i> 908</p>
                    <div class="shot-meta-1">
                        <p><i class="fas fa-heart"></i> 35</p>
                    </div>
                </div>
                </div>
            </div>

            <div class="shot-item">
                <img src="https://cdn.dribbble.com/userupload/15397531/file/original-f03a68b2242a8d049735ec6a75c4399d.jpg?resize=1024x768" alt="Design 1">
                <div class="shot-info">
                    <p class="shot-title">Scott Biersack</p>
                    <div class="shot-meta">
                        <p><i class="fas fa-eye"></i> 2.4k</p>
                    <div class="shot-meta-1">
                        <p><i class="fas fa-heart"></i> 26</p>
                    </div>
                </div>
                </div>
            </div>

            <div class="shot-item">
                <img src="https://cdn.dribbble.com/userupload/15390351/file/original-c71b777463b741e02fe3ebd23faeba68.jpeg?resize=1024x768" alt="Design 1">
                <div class="shot-info">
                    <p class="shot-title">Jessie Maisonneuve</p>
                    <div class="shot-meta">
                        <p><i class="fas fa-eye"></i> 4.3k</p>
                    <div class="shot-meta-1">
                        <p><i class="fas fa-heart"></i> 42</p>
                    </div>
                </div>
                </div>
            </div>

        </section>
    </main>
</body>
</html>
```
## CSS Example

```css
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f8f8f8;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: #333;
    color: white;
    padding: 10px 20px;
}

header .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
}

header .logo h1 {
    margin: 0;
}

header nav ul {
    list-style: none;
    display: flex;
    margin: 0;
    padding: 0;
}

header nav ul li {
    margin-right: 20px;
}

header nav ul li a {
    color: #fff;
    text-decoration: none;
}

.auth-buttons a {
    color: #fff;
    text-decoration: none;
    margin-left: 10px;
}

.auth-buttons .sign-up {
    background-color: #ff4081;
    padding: 5px 10px;
    border-radius: 3px;
}

.nav-links {
    list-style-type: none;
    display: flex;
    gap: 15px;
    margin: 0;
}

.nav-links li {
    display: inline;
}

.nav-links a {
    color: white;
    text-decoration: none;
}

.auth-links a {
    margin-left: 15px;
    color: #ff4081;
    text-decoration: none;
}

.search-bar input {
    padding: 5px;
    border-radius: 3px;
    border: none;
}

.gallery-header {
    padding: 20px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.filter-options {
    display: flex;
    gap: 10px;
}

.shots-gallery {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
    gap: 15px;
    padding: 20px;
}

.shot-item {
    background-color: white;
    border-radius: 5px;
    overflow: hidden;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    position: relative;
    transition: transform 0.3s ease;
}

.shot-item:hover {
    transform: translateY(-35px);
}

.shot-item img {
    width: 100%;
    display: block;
}

.shot-info {
    padding: 10px;
    text-align: center;
}

.shot-title {
    font-weight: bold;
    margin: 0;
}

.shot-meta {
    display: flex;
    justify-content: space-around;
    padding-top: 5px;
}

.shot-meta p {
    display: flex;
    align-items: center;
    margin: 0;
    font-size: 14px;
}

.shot-meta p i {
    margin-right: 5px;
}

.shot-meta i {
    color: aqua;
}

.shot-meta-1 i {
    color: #ff4081;
}

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f5f5f5;
}

header {
    background-color: #333;
    padding: 10px 20px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    color: white;
}

.header-left {
    display: flex;
    align-items: center;
}

.header-left .logo {
    font-size: 24px;
    font-weight: bold;
    color: #ffffff;
    margin-right: 20px;
}

header nav ul {
    list-style: none;
    display: flex;
    gap: 20px;
    margin: 0;
    padding: 0;
}

header nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: 500;
    transition: color 0.3s ease;
}

header nav ul li a:hover {
    color: #ff4081;
}

.header-right {
    display: flex;
    align-items: center;
}

.header-right .auth a {
    color: white;
    text-decoration: none;
    margin-left: 15px;
    padding: 5px 10px;
    border-radius: 3px;
    transition: background-color 0.3s ease;
}

.header-right .auth a:hover {
    background-color: rgba(255, 64, 129, 0.2);
}

.header-right input {
    padding: 5px 10px;
    border-radius: 3px;
    border: 1px solid #ccc;
    margin-left: 20px;
}

.filter-bar {
    display: flex;
    justify-content: center; 
    align-items: center;
    background-color: #090909ba;
    padding: 20px;
    flex-direction: column; 
    text-align: center; 
}

.filter-elements {
    display: flex;
    align-items: center;
    flex-direction: column; 
}

.filter-elements h4 {
    margin: 0;
    padding-inline-end: 10px;
    color: white;
}

.filter-options {
    display: flex;
    gap: 10px;
    margin-top: 10px; 
}

.filter-options a {
    text-decoration: none;
    padding: 10px 20px;
    border-radius: 5px;
    color: white;
    transition: background-color 0.3s ease;
}

.filter-options a:hover {
    background-color: grey;
}

.btn-signup {
    background-color: #ff4081;
    font-weight: bold;
}

.header-left .logo {
    font-style: italic;
}
```
### Output:

![Screenshot (116)](https://github.com/subhan4t/Day-3-css/blob/c19c31eabcd77db2b2917611874d209671440ce7/Screenshot%20(116).png)
![Screenshot (116)](https://github.com/subhan4t/Day-3-css/assets/170702606/ebac5e6f-fcd9-46fe-b389-4307748b24e5)
