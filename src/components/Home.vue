<template>
  <div id="home">
    <!-- Top Header -->
    <header>
      <div id="header" class="container">
        <div id="branding">
          <h1>Wuhu</h1>
        </div>
        <div id="search">
          <img src="../assets/search.svg" alt="Wuhu search">
        </div>
        <div id="login-start" class="grid-2">
          <a id="login" href="#" class="btn-secondary">登录</a>
          <a id="start" href="#" class="btn btn-secondary">开始</a>
        </div>
      </div>
    </header>

    <!-- Nav -->
    <nav id="navigation" class="navition container">
      
    </nav>

    <!-- Tag Section -->
    <section id="tag-section" class="tag-section container boxes">
      <div class="box">

      </div>
            <div class="box">
        
      </div>
            <div class="box">
        
      </div>
    </section>

    <!-- Showcase -->
    <section id="showcase" class="container">

    </section>

    <!-- Tag List & Popular SideBar -->
    <section id="content" class="container">
      <article id="tag-list">

      </article>

      <aside id="popular-sidebar">

      </aside>
    </section>

    <!-- About -->
  </div>
</template>

<script>
export default {
  name: "Home",
  props: {
    msg: String
  }
};
</script>

<style scoped>
/* Header Branding */
#header {
  background-color: aquamarine;
  display: grid;
  grid-template-columns: 1fr 4fr 1fr;
  grid-gap: 20px;
  height: 3rem;
}

#branding {
  background-color: beige;
}

#branding h1 {
  margin: 0;
  padding-top: 0.8rem;
  color: var(--primary-color-hover);
}

/* Header Search */
#search {
  background-color: yellow;
}

#search img {
  float: right;
  height: 1rem;
  padding: 1rem 0;
}

/* Header Login & Get Start */
#login-start {
  background-color: violet;
  text-align: center;
  margin: auto;
  letter-spacing: 3px;
}

#login-start a {
  font-size: 0.8rem;
  margin-right: 20px;
}

#login-start #login {
  margin-top: 0.5rem;
}

/* Navigation */
#navigation {
  margin-top: 5px;
  background-color: blue;
  height: 2rem;
}

/* Tag Section */
#tag-section {
  background-color: brown;
  height: 70vh;
  margin-top: 5px;
}

.boxes {
  display: grid;
  grid-gap: 10px;
  grid-template-columns: repeat(3, 1fr);
}

.box {
  margin: 10px 0;
  padding: 20px;
  background-color: azure;
}

/* Showcase */
#showcase {
  height: 50vh;
  margin-top: 5px;
  background-color: black;
}

/* Content */
#content {
  height: 300vh;
  margin-top: 5px;
  background-color: aqua;
  padding: 10px;
}

#content #tag-list {
  padding: 10px;
  float: left;
  width: 70%;
  height: 100%;
  background-color: brown;
  box-sizing: border-box;
}

#content #popular-sidebar {
  padding: 10px;
  float: right;
  width: 30%;
  height: 100%;
  background-color: blueviolet;
  box-sizing: border-box;
}
</style>
