<template>
        <section class="about-main">
            <h1 class="h1-title">
                About Me
            </h1>

            <div class="about-all">
               <div class="about-image">
                    <div class="icon-background">
                    <img src="/src/assets/Profile.jpeg" alt="">
                </div>
                    <img src="/src/assets/Profile.jpeg" alt="">
                <div class="about-text-icon">
                    <h1 cla>
                       Hi! Im Woodude 
                    </h1>
                </div>
                  
                </div>
                <div class="about-text">
                    
                  
                    <h2> Find me at</h2>
                    <p><ul>
                        <li>
                            <a class="action-text" href="">Github</a>
                        </li>
                    </ul>
                </p>
                </div>
            </div>
        </section>
</template>


<script lang="ts" setup name="about">

</script>

<style scoped>
    .about-main {
        margin: 25px;
    }
    .about-image {
        display: flex;
        text-align: center;
        justify-content: center;
        
    }
    
    .about-text {
        margin-top: 5rem;
        text-align: center;
    }


    .icon-background {

    z-index: -1;
    height: 100%;
    position: absolute;
    border-radius: 320px;
    filter: blur(68px);
    }
    img {
        border: solid 10px;
        height: 50%;
        border-radius: 300px;
    }

    .about-text-icon {
        width: 4rem;
        font-family: 'Courier New', Courier, monospace;
        font-size: 1.5rem;
        padding-left: 3rem;
    }


    h2 {
        padding-left: 5rem;
        margin: auto;
        font-size: 2.5rem;
        font-weight: 600;
    }

    p {
        padding-left: 5rem;
        margin: auto;
        font-size: 1.2rem;
    }
    li {
        list-style: none;
    }

</style>