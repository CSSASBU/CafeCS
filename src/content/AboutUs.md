

<style>
.team-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 2em;
  margin-top: 2em;
}

.member {
  flex: 1 1 200px; /* responsive width — fits 2-3 per row */
  max-width: 300px;
  text-align: center;
  padding: 1em;
  border-radius: 10px;
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.member:hover {
  transform: translateY(-5px);
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
}

.member img {
  width: 100%;
  max-width: 180px;
  height: 180px;
  object-fit: cover;
  border-radius: 50%; /* makes images round */
  margin-bottom: 1em;
  box-shadow: 0 2px 8px rgba(0,0,0,0.15);
}

.member .name {
  font-weight: bold;
  font-size: 1.1em;
  margin-bottom: 0.3em;
}

.member .title {
  font-size: 0.9em;
}

/* Responsive adjustments */
@media (max-width: 700px) {
  .member {
    flex: 1 1 100%;
  }
}
</style>

<div class="team-container">
  <div class="member">
    <img src="team/1.jpg" alt="Sadra Seyedtabaei">
    <div class="name">Sadra Seyedtabaei</div>
    <div class="title">Position</div>
  </div>
<div class="member">
    <img src="team/1.jpg" alt="Mohammad Sajjad Zanganeh">
    <div class="name">Mohammad Sajjad Zanganeh</div>
    <div class="title">Position</div>
  </div>
  <div class="member">
    <img src="team/1.jpg" alt="Amin Ghoorchian">
    <div class="name">Amin Ghoorchian</div>
    <div class="title">Position</div>
  </div>
  <div class="member">
    <img src="team/1.jpg" alt="Shayan Shahrabi">
    <div class="name">Shayan Shahrabi</div>
    <div class="title">Position</div>
  </div>
  <div class="member">
    <img src="team/1.jpg" alt="Ali Taherzadeh">
    <div class="name">Ali Taherzadeh</div>
    <div class="title">Position</div>
  </div>
  <div class="member">
    <img src="team/1.jpg" alt="Mehrdad Shirvani">
    <div class="name">Mehrdad Shirvani</div>
    <div class="title">Position</div>
  </div>
  <div class="member">
    <img src="team/1.jpg" alt="Ali Nadi">
    <div class="name">Ali Nadi</div>
    <div class="title">Position</div>
  </div>
  <div class="member">
    <img src="team/1.jpg" alt="AmirAli Araghi">
    <div class="name">AmirAli Araghi</div>
    <div class="title">Position</div>
  </div>
  <div class="member">
    <img src="team/1.jpg" alt="Ehsan Habibagahi">
    <div class="name">Ehsan Habibagahi</div>
    <div class="title">Position</div>
  </div>
  <div class="member">
    <img src="team/1.jpg" alt="Hirad Torabi">
    <div class="name">Hirad Torabi</div>
    <div class="title">Position</div>
  </div>
</div>
