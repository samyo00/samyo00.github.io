---
layout: archive
permalink: /bucketlist/
title: "My bucket list"
author_profile: true
---

[ ] Mercury
[x] Venus
[x] Earth (Orbit/Moon)
[x] Mars
[ ] Jupiter
[ ] Saturn
[ ] Uranus
[ ] Neptune
[ ] Comet Haley

<style>
    /* Custom CSS to style the checkboxes */
    .item-checkbox {
      margin-right: 10px;
    }

    .item-checkbox:checked {
      background-color: lightgray;
      border-color: lightgray;
    }

    .item-checkbox:checked::before {
      content: '\2713';
      display: block;
      color: #000;
      text-align: center;
      font-size: 14px;
      line-height: 16px;
    }

    .item-checkbox:disabled {
      opacity: 0.6;
      cursor: not-allowed;
    }

    .item-checkbox:disabled:checked {
      background-color: lightgray;
      border-color: lightgray;
    }
  </style>
</head>

<body>
  <!-- Top Navigation Bar -->
  <header>
    <!-- Navigation Bar -->
    <div class="topnav">
      <nav>
        <ul>
          <li><a href="/index.html">Home</a></li>
          <li><a href="projects.html">Projects</a></li>
          <li><a href="Achievements.html">Achievements</a></li>
          <li><a href="/bucket_list.html" class="active">Bucket List</a></li>
          <li><a href="/favorites.html" >Favorites</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <!-- Main Content -->
  <div class="main">
    <h2>Bucket List</h2>
    <!-- <p>Progress as of July 1, 2023: 39.75/91.</p> -->
    <p>Progress as of July 1, 2023</p>

    <ul class="bucket-list">
      <li>
        <label>
          <input type="checkbox" class="item-checkbox" checked disabled />
          Provide financial support and mentorship to enable someone to gain admission into an undergraduate program that would otherwise be financially or academically out of reach for them
        </label>
      </li>
      <li>
        <label>
          <input type="checkbox" class="item-checkbox" disabled />
          Conduct research in computational neuroscience and contribute to the development of technologies aimed at restoring vision for the visually impaired. <a href="https://www.facebook.com/watch/?v=486813910180566">Motivation</a>
        </label>
      </li>
      <li>
        <label>
          <input type="checkbox" class="item-checkbox" disabled />
          Attend a Coldplay concert in person
        </label>
      </li>
      <li>
        <label>
          <input type="checkbox" class="item-checkbox" disabled />
          Visit 50 countries (~4% done)
        </label>
      </li>
      <li>
        <label>
          <input type="checkbox" class="item-checkbox" disabled />
          Paragliding
        </label>
      </li>
      <li>
        <label>
          <input type="checkbox" class="item-checkbox" checked disabled />
          Live in another country
        </label>
      </li>
      <li>
        <label>
          <input type="checkbox" class="item-checkbox" disabled />
          Become the first author of a paper at a top-tier conference
        </label>
      </li>
      <li>
        <label>
          <input type="checkbox" class="item-checkbox" disabled />
          Read 1000 books (~2% done)
        </label>
      </li>
      <!-- <li>
        <label>
          <input type="checkbox" class="item-checkbox" disabled />
          Make one million dollars
        </label>
      </li> -->
      <!-- <li>
        <label>
          <input type="checkbox" class="item-checkbox" disabled />
          Teach a graduate-level course
        </label>
      </li> -->
      <li>
        <label>
          <input type="checkbox" class="item-checkbox" disabled />
          Start a company
        </label>
      </li>
      <!-- <li>
        <label>
          <input type="checkbox" class="item-checkbox" disabled />
          Author a patent
        </label>
      </li> -->
      <!-- Rest of the list items... -->
    </ul>
  </div>