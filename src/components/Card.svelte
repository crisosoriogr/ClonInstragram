
<script>
    import Comments from "./Comments.svelte";
</script>

<div class="Card">

 <div class="Card-container">
    <div class="Card-header">
        <div class="Card-user">
            <img src="https://www.lapatria.com/sites/default/files/styles/ampliar_945/public/noticia/2022-12/UMANIZALES.jpg?itok=mGqlvLaa" alt="">
            <h2>
                Elmo.pug
                <span>Manizales,Colombia</span>
            </h2>
        </div>
       <div class="Card-settings">
            <i class="fas fa-ellipsis-h"/>
       </div>

    </div>
      <div class="Card-photo">
         <figure>
            <img src="https://www.lapatria.com/sites/default/files/styles/ampliar_945/public/noticia/2022-12/UMANIZALES.jpg?itok=mGqlvLaa" alt="">
         </figure>
      </div>

      <div class="Card-icons">
        <div class="Card-icons-firts">
            <i class="fas fa-heart"/>
            <i class="fas fa-paper-plane"/>
        </div>
       <div class="Card-icons-second">
        <i class="fas fa-bookmark"/>
       </div>

      </div>

      <div class="Card-description">
        <h3>elmo.pug</h3>
        <span>Hola !</span>
      </div>
      

      <Comments/>
 </div>

</div>