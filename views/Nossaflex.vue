<template>
<div>
    <img src="@/assets/Govtech/background.webp" alt="GovTech Logo" class="hero" />
    <div class="inner-content">
      <h3 class="heading"><b>Introduction</b></h3>
      <p class="paragraph">
        I joined the Govtech Video Analytics and AI Practice team back in May 2024. During my four-month internship at GovTech, I contributed to various content authentication and management initiatives as part of the AI Practice in the Government Technology Office (GTO). I worked on two main projects: the Out-of-Context Image-Caption Pair Detection and Curator, an Automated Media Indexing Management System. 
      </p>
      <p class="paragraph">
        As an intellectually curious learner and innovative problem solver, I am excited to contribute to the AI Practice’s mission. This article reflects my journey from learning how to apply AI to solve real-world problems to deploying scalable AI systems for the public.
      </p>
    </div>
    
    <!-- Project 1 Section -->
    <img src="@/assets/Govtech/rag_pipeline.webp" class="images-full" />
    <h6 class="subtitle">Out-of-Context Image-Caption Pair Detection</h6>
    <div class="inner-content">
      <h3 class="heading"><b>Project 1: Out-of-Context Image-Caption Pair Detection</b></h3>
      <p class="paragraph">
        My first project involved developing a proof-of-concept (POC) for a multimodal cheap fake detector using Retrieval Augmented Generation (RAG) with zero-shot captioning fallback mechanism. The tool aims to identify mismatched image-caption pairs, helping the public distinguish between authentic and misleading content, particularly in the Singapore context.
      </p>
      <p class="paragraph">
        Initially, I built a single-chain zero-shot captioning Vision Language Model (VLM) pipeline. However, the single-chain pipeline struggled with seemingly in-context but factually incorrect captions. Implementing a RAG pipeline with zero-shot captioning fallback increased accuracy by 27%.
      </p>
      <p class="paragraph">
        Data played a crucial role in this project. I curated thousands of images with corresponding captions, generating both authentic and mismatched pairs. I created a vector database using LanceDB with hybrid search capabilities for improved accuracy.
      </p>
    </div>

    <!-- Project 2 Section -->
    <img src="@/assets/Govtech/aws.webp" class="images-full" />
    <h6 class="subtitle">Automated Media Indexing Management</h6>
    <div class="inner-content">
      <h3 class="heading"><b>Curator: Automated Media Indexing Management System</b></h3>
      <p class="paragraph">
        My second project involved collaborating with the Government Digital Products team to develop a Whole-of-Government (WOG) media indexing management system. This initiative explored advanced multimodal AI capabilities, including multimodal search and automated tagging and captioning for both images and videos.
      </p>
      <p class="paragraph">
        A key component of this project was building a proof-of-concept (POC) for an entity search feature. I developed backend services that allowed users to search for related images based on an uploaded entity image with AWS Rekognition. This task required careful consideration of various design factors, with a particular focus on maximizing efficiency and minimizing latency.
      </p>
      <p class="paragraph">
        Following backend development, I designed the frontend interface for this feature, ensuring a user-friendly and intuitive experience. I integrated the frontend with the backend using NextJS. Comprehensive evaluation of the media indexing feature through prompt engineering further improved system performance.
      </p>
    </div>

    <!-- Reflections Section -->
    <img src="@/assets/Govtech/intern_day.webp" class="images-full" />
    <h6 class="subtitle">Govtech Intern Day</h6>
    <div class="inner-content">
      <h3 class="heading"><b>Reflections</b></h3>
      <p class="paragraph">
        Throughout this journey, I gained valuable insights into scalability, data importance, and the significance of a supportive work environment. Scalability required designing architecture with future needs in mind, such as choosing between client-side and server-side rendering for different tasks.
      </p>
      <p class="paragraph">
        Data is fundamental to AI engineering, enhancing model performance through preprocessing and optimization. Additionally, the welcoming and innovative culture at GovTech enabled me to thrive and contribute effectively.
      </p>
    </div>

    <!-- Conclusion Section -->
    <img src="@/assets/Govtech/intern_day2.webp" class="images-full" />
    <h6 class="subtitle">Conclusion</h6>
    <div class="inner-content">
      <h3 class="heading"><b>Conclusion</b></h3>
      <p class="paragraph">
        Looking back, joining GovTech was one of the best decisions I have made. Working on real-world AI projects has significantly enhanced my skills as an AI engineer, from testing and deployment, to understanding key design principles in large AI systems.
      </p>
      <p class="paragraph">
        I want to extend my heartfelt gratitude to my mentor, Kyaw, and the entire AI Practice team for their unwavering support and for making my internship such a fulfilling experience. Their encouragement and the enjoyable moments we shared made me look forward to going to work every day. Lastly, I am deeply grateful for all the unforgettable memories and friendships made while planning the Intern bonding day!
      </p>
    </div>
    <br />
    <a href="https://www.curator.gov.sg/" style="color: #ff5733">Govtech Curator Project</a>
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
    height: 350px;
    object-fit: cover;
}

.images-full {
    width: 100%;
    height: auto;
    object-fit: cover;
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
