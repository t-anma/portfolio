# portfolio
## Assignments for UW's Introduction to Git & HTML online class:
### Lesson 3:
#### Added in CSS style sheet complete with 50 lines of code that was then referenced in the two portfolio pages from Assignment 2 (home page and about me page).
### Lesson 2:
#### In the index.html file, you will find my completed landing page for the portfolio complete with 2 links in the nav, a list of projects with images and links, and use of the header, article, and footer elements.
#### In the about_me.html file, you will find my second page for the portfolio website complete with information about me.
##### by Angela Martin, angelalmartin98@gmail.com

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Angela's Portfolio</title>
</head>
<body>
  <header>
    <h1> Angela's Portfolio</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="about_me.html">About Me</a>
    </nav>
  </header>

  <section>
    <h2> Projects</h2>
    <article>
      <h3>Select a project to view</h3>
      <ol>
        <li>Project #1: <img src="https://media.defense.gov/2018/Feb/14/2001877850/780/780/0/180213-F-OC707-0934.JPG" width="150" height="100" alt="a very cute dog that has nothing to do with semantic elements laying down">
          <a href="file:///Users/angelamartin/Desktop/html100/semantic-elements/index.html">Semantic Elements</a></li>
        <li>Project #2: <img src="https://www.guideposts.org/sites/guideposts.org/files/styles/hero_box_left_lg/public/blog_post/k9_veterans.jpg?timestamp=1520443629" width="150" height="100" alt="a military service dog laying down that has nothing to do with project #2 and everything to do with showing I know how to do this">
          <a href="file:///Users/angelamartin/Desktop/html100/html-basics/sectioning-elements.html">Cats, Cats, Cats</a></li>
        <li>Project #3: <img src="https://www.dogingtonpost.com/wp-content/uploads/2016/11/MilitaryDog.jpg" width=150 height="100" alt="another dog that has nothing to do with the project">
          <a href="file:///Users/angelamartin/Desktop/html100/html-basics/index.html">Welcome, Everything is Fine!</a></li>
      </ol>
    </article>
  </section>

  <footer>
    <p>This page built by Angela in 2019 </p>
  </footer>

</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Angela's Portfolio: About Me</title>
</head>
<body>
  <header>
    <h1> Angela's Portfolio: About Me</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="about_me.html">About Me</a>
    </nav>
  </header>

  <section>
    <h2> About Me</h2>
    <article>
      <h3>Hello! Happy to meet you.</h3>
      <p> My name is Angela and I am a User Experience Design major at the Savannah College of Art and Design. I am graduating in May 2020. <a href="https://angelamartin.myportfolio.com/">Here's a link to my artistic portfolio</a></p>
    </article>
  </section>

  <footer>
    <p>This page built by Angela in 2019 </p>
  </footer>

</body>
</html>
