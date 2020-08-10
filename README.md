@charset "UTF-8";

/*
------------------------------------*/
html {
  font-size: 100%;
}

body{
  font-family: "Yu Gothic Medium", sans-serif;
  line-height: 1.7;
  color: #432;
}

a{
  text-decoration: none;
}

img{
  max-width: 100%;
}

/*Header
------------------------------------*/
.header-logo {
  height: 80px;
  width: 15%;
  margin: auto;
}

.main-nav {
  display: flex;
  font-size: 1.25rem;
  margin-top: 34px;
  list-style: none;
}

.main-nav li {
  margin-left: 36px;
}

.main-nav a {
  color: #432;
}

.main-nav a:hover {
  color: #0bd;
}

.page-header {
  display: flex;
  justify-content: space-between;
  background-color: rgba(255, 255, 255, 0.8);
  height: 120px;
}

.wrapper {
  max-width: 1800px;
  margin: 0 auto;
  padding: 0 4%;
}

/* HOME
--------------------------------------------------------*/
.home-content {
  text-align: center;
  margin-top: 10%;
  color: #fff;
}

.home-content p {
  font-size: 1.125rem;
  margin: 10px 0 42px;
}

/* Title */
.page-title {
  font-size: 5.5rem;
  font-family: 'Philosopher', serif;
  text-transform: uppercase;
  text-shadow: -5px 0 #432;
  font-weight: normal;
}

.page-title span {
  color: red;
}

/* Button */
.button {
  font-size: 1.375rem;
  background: #0bd;
  color: #fff;
  border-radius: 5px;
  padding: 18px 32px;
}

.button:hover {
  background: #0090aa;
}

/* Background */
.big-bg {
  background-size: cover;
  background-position: center top;
  background-repeat: no-repeat ;
}

#home {
  background-image: url(gymnas3.jpg);
  min-height: 100vh;
}

#home .page-title {
  text-transform: none;
}
