<template>
    <main>
        <div class="text-top">
             Vídeos novos toda <b>quinta</b> às <b>20h</b>
        </div>

        <a href="https:/youtube.com" target="blank">
        <img alt="Inscreva-se" id="subscribe" src="https://raw.githubusercontent.com/william-costa/wdev-mock-site-resources/master/assets/images/subscribe.svg">
        </a>

        <div class="text-bottom">
            youtube.com/
        </div>

    </main>
</template>
<script>
    export default{
        name: 'Home'
        }
</script>

<style scoped>

main{
    background-color: var(--color-background-home);    
    justify-content: center;
    align-items: center;   
    }

.text-top{
    color: var(--color-text-light);
    font-size: 22px;
    margin-bottom: 20px;
    }

.text-bottom{
    color: var(--color-text-light);
    font-size: 18px;
    margin-top: 20px;
    }

#subscribe{
    width: 340px;
    }

@media (min-width:700px){
    #subscribe{
        width: 370px;
    }
}
</style>