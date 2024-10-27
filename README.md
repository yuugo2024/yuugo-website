/* 样式重置 */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    color: #333;
    line-height: 1.6;
}

/* Header 样式 */
.header {
    background-color: #333;
    color: #fff;
    padding: 1rem;
}

.header-container {
    max-width: 1200px;
    margin: auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo {
    font-size: 1.5rem;
}

.navigation a {
    color: #fff;
    margin-left: 1rem;
    text-decoration: none;
}

.navigation a:hover {
    text-decoration: underline;
}

/* Hero 样式 */
.hero {
    background-image: url('images/hero.jpg');
    background-size: cover;
    background-position: center;
    color: #fff;
    padding: 5rem 1rem;
    text-align: center;
}

.hero h2 {
    font-size: 2.5rem;
    margin-bottom: 1rem;
}

.hero p {
    margin-bottom: 2rem;
}

.button {
    padding: 0.5rem 1.5rem;
    color: #333;
    background-color: #fff;
    text-decoration: none;
    border-radius: 5px;
}

.button:hover {
    background-color: #f4f4f4;
}

/* About 样式 */
.about {
    padding: 3rem 1rem;
    text-align: center;
}

/* Collection 样式 */
.collection {
    padding: 3rem 1rem;
    text-align: center;
}

.collection-gallery {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
}

.collection-item {
    width: 200px;
    margin: 1rem;
    text-align: center;
}

.collection-item img {
    width: 100%;
    border-radius: 5px;
}

/* Contact 样式 */
.contact {
    padding: 3rem 1rem;
    text-align: center;
}

.contact form {
    max-width: 600px;
    margin: auto;
    display: flex;
    flex-direction: column;
}

.contact input, .contact textarea, .contact button {
    margin-bottom: 1rem;
    padding: 0.5rem;
    border: 1px solid #ddd;
    border-radius: 5px;
}

.contact button {
    background-color: #333;
    color: #fff;
    cursor: pointer;
}

.contact button:hover {
    background-color: #555;
}

/* Footer 样式 */
footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 1rem;
}
