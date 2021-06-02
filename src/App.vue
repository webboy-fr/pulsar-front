<template>
  <div class="container bg-dark text-light">
    <div class="row">
      <div class="col-12 col-md-6 text-center text-md-start">
        
        <FOHeader />
      </div>
      <div class="col-12 col-md-2 text-start d-flex align-items-center justify-content-center">
        <i class="fab fa-facebook me-3"></i>
        <a class="text-light text-decoration-none" href="https://www.facebook.com/Pulsar-103501757979651">Facebook</a>
      </div>
      <div class="col-12 col-md-2 text-center d-flex align-items-center justify-content-center">
        <i class="fab fa-soundcloud me-3"></i>
        <a class="text-light text-decoration-none" href="https://soundcloud.com/user-456769386">Soundcloud</a>
      </div>
      <div class="col-12 col-md-2 text-end d-flex align-items-center justify-content-center">
        <i class="fab fa-youtube me-3"></i>
        <a class="text-light text-decoration-none"
          href="https://www.youtube.com/channel/UCiPgwaY55JdTYpDFqKX1eyA">Youtube</a>
      </div>
    </div>

    <img class="img-fluid w-100 mb-5" src="pulsar.jpg" alt="">


    <div class="row">
      <div class="col-12 col-md-8">
        <p>
          Bonjour ! Nous sommes Pulsar, et nous sommes un groupe de musique rock. Nous faisons principalement
          des reprises, des Pixies à The Black Keys, en passant par Portishead ou The Hives.
          <br>
          Nous sommes 5 (1 chanteuse, 2 guitariste, un bassiste et un batteur), et le groupe existe depuis
          2018.
          <br>
          Vous pouvez nous découvrir un peu plus en écoutant nos derniers enregistrements de répet. Nous
          projettons d'enregistrer une démo plus propre, mais nous recherchons aussi des concerts pour vous
          partager notre énergie
          galactique.
          <br>
          <div class="text-center">
            <img src="pulsar.webp" class="img-fluid" />
          </div>
          <br>
          Pourquoi galactique ? Et bien un pulsar est un type d'étoile qui brille.... très très fort. Bon on
          aurait pu s'appeler
          "boule à facettes", mais Pulsar c'est vachement plus cool... :)
          <br>
          Bref, on est dispo pour foutre le feu sur scène !!!
          <br>
          Vous pouvez nous contacter par les différents réseaux sociaux, mais si c'est pas votre truc appelez nous au 06
          73 85 48 39 (julien).
          <br>
          @++
        </p>
        <Members />
      </div>
      <div class="col-12 col-md-4">
        <h2>Démo</h2>
        <iframe width="100%" height="450" scrolling="no" frameborder="no" allow="autoplay"
                    src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/playlists/1259803744&color=%231813f7&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true"></iframe>
        <div
          style="font-size: 10px; color: #cccccc;line-break: anywhere;word-break: normal;overflow: hidden;white-space: nowrap;text-overflow: ellipsis; font-family: Interstate,Lucida Grande,Lucida Sans Unicode,Lucida Sans,Garuda,Verdana,Tahoma,sans-serif;font-weight: 100;">
          <a href="https://soundcloud.com/user-456769386" title="pulsar" target="_blank"
            style="color: #cccccc; text-decoration: none;">pulsar</a> · <a
            href="https://soundcloud.com/user-456769386/sets/pulsar-repet-mai-2021" title="PULSAR - Répet mai 2021"
            target="_blank" style="color: #cccccc; text-decoration: none;">PULSAR - Répet mai 2021</a>
        </div>



        <h2 class="mt-5">Playlist</h2>
        <div class="ratio ratio-4x3">
          <iframe src="https://www.youtube.com/embed/videoseries?list=PLN8djy52q8G9C9opwbZTGk1NLcDrMAuqK"
            title="Playlist pulsar"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
            allowfullscreen></iframe>
        </div>

        <h2 class="mt-5">Suivez nous !</h2>
        <iframe
          src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2FPulsar-103501757979651%2F&tabs=timeline&width=340&height=500&small_header=false&adapt_container_width=true&hide_cover=false&show_facepile=true&appId=101103616653623"
          width="" height="500" style="border:none;overflow:hidden; width:100%;" scrolling="no" frameborder="0"
          allowfullscreen="true"></iframe>

      </div>
    </div>
    <footer>
      Site réalisé par <a href="https://webboy.fr" title="développeur et formateur en développement web"
        target="_blank">webboy</a>.
    </footer>
  </div>  
</template>

<script setup>
  import FOHeader from './components/FOHeader.vue'
  import Members from './components/Members.vue'

  // This starter template is using Vue 3 experimental <script setup> SFCs
  // Check out https://github.com/vuejs/rfcs/blob/script-setup-2/active-rfcs/0000-script-setup.md
</script>

<style>
  #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
  }
</style>