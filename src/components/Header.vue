<template>
<header class="site-header">
    <nav class="site-nav">
      <a class="site-brand" href=" " title="home">
        Woodude./Blog
      </a>
        <div class="site-links">
        <a class="link">Home</a>
        <a class="link">Blog</a>
        <a class="link">Notes</a>
        <a class="link">Rss</a>

      </div>
    </nav>

  </header>

</template>

<script lang="ts" setup name="header" >
    
</script>

<style scoped>
.site-header {
    padding-left: 25px;
    padding-right: 25px;
    font-size: 20px; 
    margin:  25px auto; 
  }

  .site-brand {
    font-weight: bold;
    
  }
  .site-nav {
    display: flex;
  }
  .site-links {
    display: flex;
    margin:  auto 0 0 auto;
  }
  .link {
    margin-left: 20px;
    padding: 5px;
  }
  .link:hover {
    
    background-color: hsl(0, 0%, 0%);
    color: rgb(255, 255, 255);
    transition: 0.4s;
    border-radius: 0.25rem;
    cursor: pointer;
  }


  .site-nav > a {
    text-decoration: none;
    color: rgb(0, 0, 0);
    transition: 0.4s;
    padding-left: 10px;
}
@media (prefers-color-scheme: dark) {
  .site-nav > a {
    text-decoration: none;
    color: rgb(255, 255, 255);
    transition: 0.4s;
    padding-left: 10px;
  }
  .link:hover {
    background-color: hsl(0, 0%, 100%);
    color: rgb(0, 0, 0);
    transition: 0.4s;
    border-radius: 0.25rem;
    cursor: pointer;
    }
}




</style>