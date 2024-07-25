<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Kritka bansal</title>
<style>
    header{
text-align: center;
text-size-adjust: 90px;
    }
    header{
text-align: center;
text-size-adjust: 90px;
    }
    .grid-container {
        display: grid;
        grid-template-columns: repeat(3, 1fr);
        grid-gap: 20px;
      }
      
.flex-container {
  display: flex;
  flex-wrap: wrap;
  background-color: rgb(226, 230, 230);
}

.flex-container > div {
  background-color: #b1eac4;
  width:250px;
  margin: 10px;
  text-align: center;

}
      .card {
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: space-between;
      }
      
      .emoji {
        order: 1;
        font-size: 40px;
      }
      
      .title {
        order: 2;
        margin: 10px 0;
      }
      
      .description {
        order: 3;
        margin-bottom: 10px;
      }
      
      .buttons {
        order: 4;
        align-self: flex-end;
      }

    
</style>
</head>
<header><b>Kritika Bansal</b></header>
<body>
    <img src="c:\Users\kriti\OneDrive\Pictures\my image\me.jpg" height="200px" width="120px">
    <ol>
        <li>041130242</li>
        <li>Interactive media design</li>
        <li>MTM6201</li>
        <li>i love to spend my time on coding</li>
    </ol>
    <div class="flex-container">
      <div class="card">
        <div class="emoji">😊</div>
        <h2 class="title">Happy</h2>
        <p class="description">Feeling joyful and content</p>
        <div class="buttons">
          <button>Like</button>
          <button>Comment</button>
        </div>
      </div>
      <div class="card">
        <div class="emoji">😍</div>
        <h2 class="title">Love</h2>
        <p class="description">Feeling deep affection and admiration</p>
        <div class="buttons">
          <button>Like</button>
          <button>Comment</button>
        </div>
      </div>
      <div class="card">
        <div class="emoji">😂</div>
        <h2 class="title">Laugh</h2>
        <p class="description">Finding something humorous</p>
        <div class="buttons">
          <button>Like</button>
          <button>Comment</button>
        </div>
      </div>
      <div class="card">
          <div class="emoji"></div>
          <span style='font-size:100px;'>&#127793;</span>
          <h2 class="title">Seeding</h2>
          <p class="description">Find info regarding plants</p>
          <div class="buttons">
            <button>Like</button>
            <button>Comment</button>
          </div>
    </div>
</body>
</html>
