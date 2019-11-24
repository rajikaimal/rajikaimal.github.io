<style>
  .container {
    margin: 0;
  }

  .hi {
    margin-top: 100px;
    font-size: 60px;
    width: 100%;
    text-align: center;
  }

  .profile-pic-container {
    margin: 0;
  }

  .profile-pic {
    display: block;
    margin: auto;
    width: 15%;
    border-radius: 50%;
    transition: transform 0.2s;
  }

  /* .profile-pic: hover {
	transform: scale(1.2);
	transform: rotate(25deg);
} */

  .description {
    font-size: 20px;
    margin-top: 30px;
    margin-left: auto;
    margin-right: auto;
    width: 100%;
    text-align: center;
  }

  .primaryHighlight {
    background-color: orange;
    border-radius: 6px;
    padding: 4px;
    color: #ffffff;
  }

  .dx {
    background-color: deeppink;
    border-radius: 6px;
    padding: 10px;
  }

  .dx a {
    color: #ffffff;
  }

  .devtools {
    background-color: mediumslateblue;
    border-radius: 6px;
    padding: 10px;
    color: #ffffff;
  }

  .talks-section {
    margin-top: 60px;
  }
  .talks {
    font-size: 30px;
    text-align: center;
    margin-bottom: 15px;
  }

  .talks-list {
    text-align: center;
    list-style: none;
    margin: 0px;
    font-size: 20px;
  }
</style>

<div class="container">
  <div class="hi">Hi! 👨‍💻</div>
  <div class="profile-pic-container">
    <img
      src="https://avatars2.githubusercontent.com/u/8940086?s=460&v=4"
      class="profile-pic" />
  </div>
  <div class="description">
    <p>Howdy! 🤠 I'm a Senior Software Engineer at <span class="primaryHighlight">99X Technology</span>, tech speaker 💻 <br/> Open Sourcerer 🛸</p>
    <p>
      <span class="devtools">DevTools</span>
      for better
      <span class="dx">
        <a
          href="https://dev.to/stereobooster/developer-experience-how-i-missed-it-before-47go">
          DX
        </a>
      </span>
    </p>
  </div>
  <div class="talks-section">
    <p class="talks">My talks</p>
    <ul class="talks-list">
      <li>
        <a href="https://www.youtube.com/watch?v=Cbf2HvadZqA">
          FOSSASIA 2019 - Node.js - The Node.js API for open cloud
        </a>
      </li>
    </ul>
  </div>
</div>
