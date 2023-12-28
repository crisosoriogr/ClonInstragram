<style>
    .Comments h3 {
      font-size: 14px;
      color: black;
      font-weight: bold;
      margin: 0;
      padding: 0;
    }
    .Comments span {
      font-size: 14px;
      margin: 0 0 0 0.5em;
      font-weight: normal;
      color: rgba(black, 0.9);
    }
    .Comments-add {
      padding: 1em 1em 1em 1em;
      border-top: 1px solid rgba(219, 219, 219, 0.8);
    }
    .Comments-add form {
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    .Comments-content {
      padding: 0 1em 0.5em 1em;
    }
    .Comments-users {
      margin: 0 0 0.5em 0;
      display: flex;
    }
  
    input {
      border: solid 1px #e9e9e9;
      border-radius: 5px;
      color: #696969;
      border: 1px solid transparent;
      font-size: 12px;
      outline: none;
      width: 100%;
      display: flex;
    }
    button {
      border: none;
      color: #3897f0;
      font-size: 12px;
      outline: none;
      cursor: pointer;
    }
    
  </style>
<div class="Comments">

    <div class="Comments-content">
        <div class="Comments-users">
            <h3>Cris Osorio</h3>
            <span>Holla Elmo</span>

        </div>
     

        <div class="Comments-add">
            <form>

                <input type="text"
                class="Comments-input"
                placeholder="agregar Comentario..."
                id="Text"/>
                <button type="submit">Post</button>
            </form>
        </div>

    </div>


</div>
