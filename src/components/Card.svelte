<script>
  import bgPattern from "../assets/img/bg-pattern-card.svg";
  import victor from "../assets/img/image-victor.jpg";
</script>

<div class="card">
  <div>
    <img src={bgPattern} alt="" />
  </div>
  <div class="ppic-container">
    <img src={victor} alt="victor" class="ppic" />
  </div>
  <div class="bio">
    <p class="fullname">Victor Crest <span class="age">26</span></p>
    <p class="city">London</p>
  </div>
  <div class="line" />
  <div class="stats">
    <div>
      <p>80k</p>
      <span>Followers</span>
    </div>
    <div>
      <p>803k</p>
      <span>Likes</span>
    </div>
    <div>
      <p>1.4k</p>
      <span>Photos</span>
    </div>
  </div>
</div>

<style>
  .card {
    width: 300px;
    background-color: #fff;
    border-radius: 15px;
    overflow: hidden;
  }

  .ppic-container {
    width: 100%;
    position: relative;
    height: 40px;
  }

  .ppic {
    border-radius: 50%;
    outline: 5px solid #fff;
    position: absolute;
    top: -50px;
    right: 32%;
  }

  .bio {
    padding: 20px;
  }

  .fullname {
    font-weight: 700;
    padding: 5px;
  }

  .age {
    display: inline-block;
    margin-left: 6px;
    color: var(--dark-gray);
    font-weight: 400;
  }

  .city {
    color: var(--dark-gray);
    font-size: 14px;
  }

  .line {
    border: 0;
    border-top: 0.5px solid var(--dark-gray);
    opacity: 0.2;
  }

  .stats {
    display: flex;
    justify-content: space-around;
    align-items: center;
    padding: 20px;
  }

  .stats span {
    display: block;
    font-size: 12px;
    color: var(--dark-gray);
  }

  .stats p {
    font-weight: 700;
  }
</style>
