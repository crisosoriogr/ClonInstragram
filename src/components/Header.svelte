<style>
  .Header {
    background-color: white;
    position: fixed;
    width: 100%;
  }
  .Header-container {
    grid-template-columns: minmax(auto, 936px);
    display: grid;
    justify-content: center;
    background-color: white;
    border-bottom: 1px solid rgba(38, 38, 38, 0.4);
  }
  .Header-content {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 0.5em;
  }
  .Header ul {
    list-style: none;
  }
  .Header li {
    display: inline-block;
    margin: 0 0 0 1em;
  }
  .Header i {
    font-size: 16px;
    color: rgba(38, 38, 38, 0.7);
    cursor: pointer;
  }

  h1 {
    padding: 0;
    margin: 0;
    font-size: 28px;
    color: black;
    font-family: "Pacifico", cursive;
    cursor: pointer;
    position: relative;
    background: #fff;
    mix-blend-mode: multiply;
    display: inline-block;
  }

  h1:before {
    content: "";
    display: block;
    width: 100%;
    height: 100%;
    background: radial-gradient(circle at top left, #f09433, #bc1888);
    mix-blend-mode: screen;
    position: absolute;
    top: 0;
    left: 0;
  }
</style>




<div class="Header">
  <div class="Header-container">
    <div class="Header-content">
       <div class="Header-logo">
        <h1>Instagram</h1>
       </div>
       <div class="Header-nav">
        <ul>
            <li>
                <i class="fa-duotone fa-heart"/>

            </li>
            <li>
              <i class="fa-solid fa-user"></i>
            </li>
        </ul>
       </div>

    </div>
  </div>
</div>