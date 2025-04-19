<template>
  <div>
    <!-- Introduction Section -->
    <!-- <img src="@/assets/Nossaflex/hero_light.webp" alt="Introduction" class="hero" /> -->
    <div class="inner-content">
      <h3 class="heading"><b>Introduction</b></h3>
      <p class="paragraph">
        I spearheaded the development of an Instagram-like web application that featured both client-side and server-side rendering, integrated with a MapReduce distributed system and a custom search engine. 
        In compliance with the University of Michigan's honor code, I am not allowed to publicly disclose the source code. 
        However, detailed descriptions of the project's key functionalities and technological implementations are provided below to showcase my technical experiences.
      </p>
    </div>

    <!-- Project 2 Section -->
    <img src="@/assets/fullstack_distributed_systems/p2-insta485.webp" alt="Insta485 Serverside" class="images" />
    <h6 class="subtitle">insta485-serverside</h6>
    <div class="inner-content">
      <h3 class="heading"><b>Server-side Rendering</b></h3>
      <p class="paragraph">
        This project represents the second installment of a three-part series in EECS 485, focused on developing a dynamic, interactive website modeled after Instagram. 
        Leveraging server-side rendering, the application supports real-time interactions such as creating, updating, deleting, and liking posts, comments, and user profiles.
      </p>
      <p class="paragraph">
        Key Features:
        <ul>
          <li>Dynamic Content Management with CRUD operations.</li>
          <li>Session Management for secure user interactions.</li>
          <li>Advanced SQL Database Interactions.</li>
          <li>Interactive User Interface with integrated server-rendered pages.</li>
          <li>Authentication and Authorization mechanisms.</li>
        </ul>
      </p>
    </div>

    <!-- Project 3 Section -->
    <img src="@/assets/fullstack_distributed_systems/p3-insta485.webp" alt="Insta485 Serverside" class="images" />
    <h6 class="subtitle">insta485-clientside</h6>
    <div class="inner-content">
      <h3 class="heading"><b>Client-side Rendering</b></h3>
      <p class="paragraph">
        The final project in EECS 485, focusing on developing an interactive web application using client-side dynamic pages powered by a REST API. 
        This Instagram clone transitions from server-side rendering to client-side rendering with AJAX and ReactJS.
      </p>
      <p class="paragraph">
        Key Features:
        <ul>
          <li>Client-Side Rendering for dynamic user interactions.</li>
          <li>AJAX-driven Interactions for asynchronous data fetching and updates.</li>
          <li>REST API Integration for backend functionalities.</li>
          <li>Reusable Code with enhanced functionality.</li>
          <li>Asynchronous Programming with improved responsiveness.</li>
        </ul>
      </p>
    </div>

    <!-- Project 4 Section -->
    <img src="@/assets/fullstack_distributed_systems/p4-mapreduce.webp" alt="Insta485 Serverside" class="images" />
    <h6 class="subtitle">MapReduce Distributed System</h6>
    <div class="inner-content">
      <h3 class="heading"><b>Distributed System Implementation</b></h3>
      <p class="paragraph">
        This project implements a MapReduce framework in Python, inspired by Google's original MapReduce paper. 
        Designed to execute MapReduce programs across distributed systems, the framework is capable of running on clusters managed by AWS EMR, Google Dataproc, or Microsoft MapReduce.
      </p>
      <p class="paragraph">
        Key Features:
        <ul>
          <li>Distributed Execution with multiple nodes.</li>
          <li>Fault Tolerance with efficient error handling.</li>
          <li>Concurrency through OS-provided threads and processes.</li>
          <li>Networking with Sockets for inter-node communication.</li>
          <li>Scalable Worker Instances with parallel processing capabilities.</li>
        </ul>
      </p>
    </div>

    <!-- Project 5 Section -->
    <img src="@/assets/fullstack_distributed_systems/p5-search-engine.webp" alt="Insta485 Serverside" class="images" />
    <h6 class="subtitle">Search Engine</h6>
    <div class="inner-content">
      <h3 class="heading"><b>Search Engine Development</b></h3>
      <p class="paragraph">
        This project is designed to build a scalable search engine, utilizing advanced information retrieval techniques and parallel data processing. 
        The system integrates text analysis, link analysis, and a service-oriented architecture to efficiently scale dynamic web pages and search functionalities.
      </p>
      <p class="paragraph">
        Key Features:
        <ul>
          <li>Segmented Inverted Index for efficient querying.</li>
          <li>Text Analysis (TF-IDF) for importance evaluation of words.</li>
          <li>Link Analysis (PageRank) for ranking web pages.</li>
          <li>REST API for providing search results in JSON format.</li>
          <li>Dynamic Search Interface mimicking functionalities of Google or Bing.</li>
        </ul>
      </p>
    </div>

    <!-- Acknowledgments Section -->
    <div class="inner-content">
      <h3 class="heading"><b>Acknowledgments</b></h3>
      <p class="paragraph">
        Special thanks to the University of Michigan, my teammates Liang Erdao and Gao Tianhong, and the EECS485 staff for providing the resources and environment to develop these applications.
      </p>
    </div>
  </div>
  </template>
  
  <style scoped>
  .hero {
    width: 100%;
    background-position: center center;
    background-size: 100%;
    background-repeat: no-repeat;
    border: 1px solid rgb(0, 0, 0, 0.1);
  }
  
  .images {
    width: 100%;
    height: auto;
    /* object-fit: cover; */
  }
  
  .images-full {
    width: 100%;
    height: auto;
    object-fit: cover;
  }

  .video {
    width: 100%;
    height: 350px;
  }
  
  .subtitle {
    font-size: 12px;
    color: gray;
    text-align: center;
  }
  
  .heading {
    padding-bottom: 5px;
  }
  
  .inner-content {
    padding-top: 30px;
    padding-bottom: 30px;
  }
  
  h6,
  h3 {
    margin: 0;
    padding: 0;
  }
  </style>
  