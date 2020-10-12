<style>
  text { background-color: blue; }
  .red-text {
    color: red;
  }
</style>

<h2 class="red-text">CatPhotoApp</h2>
<main>
  <p class="red-text">Click here to learn more <a href="https://www.linkedin.com/in/andrewsterrell/">about me.</a>.</p>

  <a href="#"><img src="https://media-exp1.licdn.com/dms/image/C4E03AQH52I3GGhZ0yA/profile-displayphoto-shrink_400_400/0?e=1608163200&v=beta&t=OA3DyMD0WenuDA_qnwfpihhbIbiWQoKH4GjmX3ceQ98" alt="A picture of Andrew in his suit." width="200" height="200"></a>

  <div>
    <p>Things I love:</p>
    <ul>
      <li>Sci-fi</li>
      <li>Katsu</li>
      <li>Traveling</li>
    </ul>
    <p>Top 3 things I hate:</p>
    <ol>
      <li>Unearned confidence</li>
      <li>Lack of empathy</li>
      <li>Making other people feel small</li>
    </ol>
  </div>

  <form action="https://freecatphotoapp.com/submit-cat-photo">
    <label><input type="radio" name="indoor-outdoor" checked> Indoor</label>
    <label><input type="radio" name="indoor-outdoor"> Outdoor</label><br>
    <label><input type="checkbox" name="personality" checked> Loving</label>
    <label><input type="checkbox" name="personality"> Lazy</label>
    <label><input type="checkbox" name="personality"> Energetic</label><br>
    <input type="text" placeholder="cat photo URL" required>
    <button type="submit">Submit</button>
  </form>
</main>
