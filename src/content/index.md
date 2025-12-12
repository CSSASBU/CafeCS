---
title: Home
socialImage: "images/og-image.png"
image: "images/og-image.png"
cover: "images/og-image.png"

socialDescription: "A corner café where we talk about the very foundation beans of CS - from machine learning and artificial intelligence to software & hardware engineering, mathematics, graph theory, and anything roasted, brewed, or filtered through the world of computer science."

tags:
  - webinar
  - computer-science
  - community
  - shahid-beheshti-university
---

# ☕ Café CS

## 🎙 Upcoming & Past Talks

<style>
	.table-container {
	  width: 100%;
	  overflow-x: hidden;
	  box-sizing: border-box;
	}
	
	table {
	  width: 90%;
	  table-layout: auto; 
	  border-collapse: collapse;
	  margin: auto;
	}
	
	td, th {
	  word-wrap: break-word;
	  overflow-wrap: break-word;
	  white-space: normal;
	  border: 1px solid #ccc;
	  padding: 1em;
	}
	td:first-child {
	  vertical-align: middle;
	}
	th {
	  background-color: #222;
	  color: #eee;
	  text-align: left;
	  
	}
	
	td img {
	  width: 100%;
	  max-height: 2000px; 
	  object-fit:scale-down;
	  border-radius: 8px;
	  display: block;
	}
	
	tr {
	  height: auto;         
	  object-fit: contain;
	
	}
	
	.title {
	  font-weight: bold;
	  font-size: 1.1em;
	}
	
	.tags {
	  margin-top: 0.5em;
	  display: flex;
	  flex-wrap: wrap;
	  gap: 0.3em;
	}
	
	.tag {
	  background: #445;
	  color: #ccd;
	  padding: 0.2em 0.5em;
	  border-radius: 5px;
	  font-size: 0.85em;
	}
	
	.description {
	  margin-top: 0.5em;
	  font-size: 0.9em;
	  color: #AAA;
	}
	
	.resources {
	  margin-top: 0.8em;
	}
	
	.resources strong {
	  display: block;
	  margin-bottom: 0.3em;
	  
	}
	
	.resources a {
	  display: inline-block;
	  margin-right: 0.8em;
	  color: #66aaff;
	  text-decoration: none;
	}
	
	.resources a:hover {
	  text-decoration: underline;
	}
	
	/* Responsive stacking */
	@media (max-width: 700px) {

  /* Make each row a card */
  tr {
    display: flex;
    flex-direction: column;
    border: 1px solid #333;
    border-radius: 10px;
    margin-bottom: 1.5em;
    overflow: hidden;
  }

  thead {
    display: none;
  }

  td {
    display: block;
    width: 100%;
    border: none;
    padding: 1em;
    box-sizing: border-box;
  }

  /* Image becomes full-width */
  td img {
    width: 100%;
    height: auto;
    max-height: none;   /* important */
    object-fit: contain;
    display: block;
  }

  .table-container {
    padding: 0 .5em;
  }
}

</style>

<div class="table-container">
  <table>
    <thead>
      <tr>
        <th>Poster</th>
        <th>Talk Info</th>
      </tr>
    </thead>
    <tbody>
    <tr>
	    <td>
          <img src="talks/1404-09-19-When-Models-Become-Actors/poster.png" alt="Intro to Game Theory Poster">
        </td>
        <td>
          <div class="title">
            <a href="talks/1404-09-19-When-Models-Become-Actors/notes.md" >#005: When Models Become Actors !</a>
            <span> | The Shift from LLMs to Intelligent Agents</span>
          </div>
          <a href="https://github.com/sinaapolo969">
	          Sina Tayebi
          </a>
          <div class="tags">
            <span class="tag">Dec 10, 2025</span>
            <span class="tag">ai</span>
			<span class="tag">llms</span>
			<span class="tag">agents</span>
			<span class="tag">agentic-systems</span>
			<span class="tag">memory</span>
			<span class="tag">tool-use</span>
			<span class="tag">autonomous-agents</span>
			<span class="tag">agi</span>
			<span class="tag">emergent-behavior</span>
			<span class="tag">ai-philosophy</span>
			<span class="tag">future-of-ai</span>
          </div>
          <div class="description">
            We built machines that could speak, but not yet machines that could decide. LLMs dazzled us with language, yet remained confined to their own predictions, unable to take a step beyond the next token. Now, quietly, a shift is underway. Models are being wrapped in memory, tools, goals, and loops, beginning to behave less like static oracles and more like emerging agents. This talk explores that threshold: why language alone was never enough, what happens when models begin to act, and whether these new agentic systems mark the first glimmer of something closer to general intelligence, or merely another step in a much longer journey.
          </div>
          <div class="resources">
            Resources:  
            <a href="talks/1404-09-19-When-Models-Become-Actors/slides.pdf">Slides</a>
          </div>
        </td>
      </tr>
    <tr>
	    <td>
          <img src="talks/1404-09-05-The-Evolution-of-Data-Architecture/poster.png" alt="The-Evolution-of-Data-Architecture">
        </td>
        <td>
          <div class="title">
            <a href="talks/1404-09-05-The-Evolution-of-Data-Architecture/notes.md" >#004: The Evolution of Data Architecture!</a>
            <span> | From Warehouses to Lakehouses and the Rise of Real-Time Processing</span>
          </div>
          <a href="https://github.com/Navid-Ebadi-2003">
	          Navid Ebadi
          </a>
          <div class="tags">
            <span class="tag">Nov 26, 2025</span>
            <span class="tag">big-data</span>
            <span class="tag">data-warehousing</span>
            <span class="tag">data-lakes</span>
            <span class="tag">data-lakehouses</span>
            <span class="tag">real-time-stream-processing</span>
            <span class="tag">data-storage</span>
            <span class="tag">data-processing</span>
            <span class="tag">data-management</span>
            <span class="tag">data-evolution</span>
          </div>
          <div class="description">
            We live in an era where data is generated at unprecedented speed, volume, and variety—a phenomenon widely known as Big Data . This explosion of information has fundamentally changed how organizations store, process, and analyze their digital assets.
            In this lecture we'll explore the evolution from traditional Data Warehouses (structured storage for analytics) to flexible Data Lakes (raw data repositories), and innovative Data Lakehouses (combining the best of both). Finally, we'll discuss real-time stream processing.
          </div>
          <div class="resources">
            Resources:  
            <a href="talks/1404-09-05-The-Evolution-of-Data-Architecture/slides1.pdf">Slides 1</a>
            <a href="talks/1404-09-05-The-Evolution-of-Data-Architecture/slides2.pdf">Slides 2</a>
            <a href="https://www.youtube.com/watch?v=D5sedVmHbqk">Video</a>
          </div>
        </td>
      </tr>
      <tr>
	    <td>
          <img src="talks/1404-08-28-Fun-Meets-Function/poster.jpg" alt="Intro to Game Theory Poster">
        </td>
        <td>
          <div class="title">
            <a href="talks/1404-08-28-Fun-Meets-Function/notes.md" >#003: Fun Meets Function</a>
            <span> | When Games Get Serious !</span>
          </div>
          <a href="https://github.com/MehrdadShirvani">
	          Mehrdad Shirvani
          </a>
          <div class="tags">
            <span class="tag">Nov 19, 2025</span>
            <span class="tag">games</span>
            <span class="tag">serious-games</span>
            <span class="tag">gamification</span>
            <span class="tag">learning</span>
            <span class="tag">creativity</span>
            <span class="tag">innovation</span>
            <span class="tag">problem-solving</span>
            <span class="tag">motivation</span>
            <span class="tag">human-intuition</span>
            <span class="tag">behavioral-science</span>
          </div>
          <div class="description">
            Games are shaping the way we learn, solve problems, and innovate. They tackle real-world challenges, from scientific discovery to improving health behaviors. In this session, we’ll explore how play can become a tool for learning, creativity, and positive change. By harnessing human intuition and motivation, we’ll see how the mechanics that make games engaging can also turn them into powerful engines for real-world impact.
          </div>
          <div class="resources">
            Resources:  
            <a href="talks/1404-08-28-Fun-Meets-Function/slides.pdf">Slides</a>
            <a href="https://www.youtube.com/watch?v=ngArnhT1szM">Video</a>
          </div>
        </td>
      </tr>
      <tr>
        <td>
          <img src="talks/1404-08-21-Beyond-The-Bank/poster.png" alt="Intro to Game Theory Poster">
        </td>
        <td>
          <div class="title">
            <a href="talks/1404-08-21-Beyond-The-Bank/notes.md">#002: Beyond the Bank</a>
            <span> |  What is Bitcoin & Why?!</span>
          </div>
          <a href="https://github.com/seyed0123">
	          Seyed Ali Hosseini Nasab
          </a>
          <div class="tags">
            <span class="tag">Nov 12, 2025</span>
            <span class="tag">bitcoin</span>
            <span class="tag">blockchain</span>
            <span class="tag">decentralized-systems</span>
            <span class="tag">cryptography</span>
            <span class="tag">digital-money</span>
            <span class="tag">peer-to-peer</span>
            <span class="tag">finance</span>
            <span class="tag">technology</span>
          </div>
          <div class="description">
            From obscurity to global headlines, Bitcoin has sparked a financial revolution that challenges our deepest assumptions about money. But what truly lies beneath the digital surface? This presentation goes beyond the price tag to uncover the core innovation: a decentralized system that allows us to trust each other without needing to trust a middleman. We will unravel how Bitcoin creates digital scarcity and enables peer-to-peer value transfer across the globe, exploring its emergence as "digital gold" and its potential to redefine the future of finance.
          </div>
          <div class="resources">
            Resources:  
            <a href="talks/1404-08-21-Beyond-The-Bank//slides.pdf">Slides</a>
            <a href="https://youtu.be/p1QJ-IL952U?si=5ce-O2Mb8VnvISQ1">Video</a>
          </div>
        </td>
      </tr>
      <tr>
        <td>
          <img src="talks/1404-08-14-Who-Is-Guarding-the-Louvre/poster.jpg" alt="Intro to Game Theory Poster">
        </td>
        <td>
          <div class="title">
            <a href="talks/1404-08-14-Who-Is-Guarding-the-Louvre/notes.md">001: Who is Guarding the Louvre?!</a>
            | The Art Gallery Problem Explained
          </div>
          <a href="https://github.com/ShayanShahrabi">
	          Shayan Shahrabi Farahani
          </a>
          <div class="tags">
	        <span class="tag">Nov 5, 2025</span>
            <span class="tag">computational-geometry</span>
            <span class="tag">optimization</span>
            <span class="tag">visibility</span>
            <span class="tag">algorithms</span>
            <span class="tag">geometry</span>
            <span class="tag">problem-solving</span>
            <span class="tag">theory</span>
            <span class="tag">math</span>
          </div>
          <div class="description">
            Imagine securing an art gallery with the fewest guards possible. This is the essence of the Art Gallery Problem, a classic puzzle in computational geometry that challenges us to find the optimal way to cover a space. It's all about achieving maximum visibility with minimum resources. Our goal for this session is to unravel this problem together, from its initial setup to its surprising and intuitive solution.
          </div>
          <div class="resources">
            Resources:
            <a href="talks/1404-08-14-Who-Is-Guarding-the-Louvre/slides.pdf">Slides</a>
            <a href="https://www.youtube.com/watch?v=hRg6qiIglMA&list=PLuHvv8pyNyW96X5cs0kZTM5AB1SQaytZg&index=4">Video</a>
          </div>
        </td>
      </tr>
    </tbody>
  </table>
</div>

---

## About Café CS

Many events inspired us to ignite the engines of Café CS - from the legendary series of Combinatorics Circle Seminars organized by the minds behind Iran’s Combinatorics Olympiad, to the Tabaghe16 Podcast of Soheil Alavi, which - by his own words - brews a magnetism that gathers people who think alike… and see the world through the same lens.

We even took a sip from past experiences - like the Math Circle Book - a place where people gathered around a shared table and solved problems together… much like a group of heroes plotting strategy over steaming mugs of logic.

All these sparks combined - and forged the idea that we, too, should ignite our own gathering - a place where computer scientists, tech lovers, mathematicians, and curious spirits unite. A corner café where we talk about the very foundation beans of CS - from machine learning and artificial intelligence to software & hardware engineering, mathematics, graph theory, and anything roasted, brewed, or filtered through the world of computer science.

Here, once a week, we gather - tea in hand, curiosity online, engines engaged - to discuss what we love.

These sessions aren’t meant to be a class - nor a conference. No towering lecture halls. No rigid protocols. Just a warm, friendly café chat for inquisitive minds - to learn from one another, spark ideas, and build a cozy fellowship of computer enthusiasts.

Till we meet again, fellow travelers of logic… 🙌❤️☕

> [!tip] [Café CS](AboutUs) - More Than a Gathering. A Brewed Alliance.
