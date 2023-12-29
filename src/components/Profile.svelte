<script>
  export let nickname;
  export let name;

</script>



<style>
    .Profile-content {
      display: flex;
      align-items: center;
    }
    .Profile-avatar img {
      width: 42px;
      height: 42px;
      border-radius: 50%;
    }
    .Profile-info {
      margin: 0 0 0 0.5em;
    }
    .Profile-info h2 {
      font-size: 14px;
      color: black;
      margin: 0;
      padding: 0;
    }
    .Profile-info span {
      font-size: 12px;
      font-weight: normal;
    }
  </style>
  
<div class="Profile">
    <div class="Profile-content">
        <div class="Profile-avatar">
            <img src="https://scontent.cdninstagram.com/v/t51.2885-19/399311455_299949926263438_4702544293095347959_n.jpg?stp=dst-jpg_s100x100&_nc_cat=103&ccb=1-7&_nc_sid=c4dd86&_nc_ohc=ZrZLL7TEsKIAX8NWb4A&_nc_ad=z-m&_nc_cid=0&_nc_ht=scontent.cdninstagram.com&oh=00_AfAQfryy-If7HZZxWSsQH4-n1v6eWH--g9bQC44MbpaSFA&oe=65929E83" alt="">
        </div>
        <div class="Profile-info">
            <h2> {nickname}</h2>
            <span> {name}</span>
        </div>
    </div>
</div>