To make the Interactive Navbar using HTML, CSS, JAVASCRIPT.

So we are Navbar Elements on the files.

HTML Navbar:

        <nav>
            <a href="#home" class="active">HOME</a>
            <a href="#about">ABOUT</a>
            <a href="#services">SERVICES</a>
            <a href="#portfolio">PORTFOLIO</a>
            <a href="#contact">CONTACT</a>
        </nav>


CSS Styling :

nav a {
    font-size: 18px;
    color: #fff;
    text-decoration: none;
    font-weight: 500;
    margin-left: 35px;
    transition: .3s;
}
nav a:hover,
nav a.active {
    color: rgb(13, 192, 216);


Javascript File :


if(top >= offset && top < offset + height) {
            navLinks.forEach(links => {
                links.classList.remove('active');
                document.querySelector('header nav a[href*=' + id + ']').classList.add('active');
            });
        };



