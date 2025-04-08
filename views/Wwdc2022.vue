<template>
    <div>
      <!-- Title -->
      <div class="inner-content">
        <h2 class="heading"><b>Brain Tumor Segmentation using 3D U-Net on MRI Scans</b></h2>
      </div>
  
      <!-- Overview -->
      <div class="inner-content">
        <h3 class="subheading"><b>Overview</b></h3>
        <p class="paragraph">
          This <a href="./Project%20Report.pdf" class="text-blue-600 underline">project</a> focuses on the accurate segmentation of brain tumors from MRI scans, 
          a critical step for advancing diagnostic and therapeutic approaches in neuro-oncology. Utilizing the powerful 3D U-Net architecture, this study 
          aims to enhance segmentation accuracy and provide reliable quantification of brain tumors. The model leverages the BRATS dataset, incorporates 
          data augmentation strategies to address class imbalance, and employs advanced filters and feature extraction techniques.
        </p>
      </div>
  
      <!-- Objective -->
      <div class="inner-content">
        <h3 class="subheading"><b>Objective</b></h3>
        <p class="paragraph">
          To develop a robust 3D U-Net model that improves brain tumor segmentation accuracy, comparing its performance against 2D U-Net and 
          investigating the efficacy of model ensembling and potential integrations with cutting-edge models like UnetFormer and MedSegDiff.
        </p>
      </div>
  
      <!-- Dataset -->
      <div class="inner-content">
        <h3 class="subheading"><b>Dataset</b></h3>
        <p class="paragraph">
          This project uses the BRATS 2021 dataset, which includes a diverse array of MRI images, facilitating a comprehensive training regime that 
          underscores the significance of extensive and varied training data.
        </p>
      </div>
  
      <!-- Features -->
      <div class="inner-content">
        <h3 class="subheading"><b>Features</b></h3>
        <ul class="paragraph list-disc pl-6">
          <li>Extensive Preprocessing: Streamlining data for optimal neural network performance.</li>
          <li>Data Augmentation: Mitigating the issue of class imbalance to enhance model generalizability.</li>
          <li>Advanced Filtering and Feature Extraction: Refining inputs to improve model outcomes.</li>
          <li>Comparative Analysis: Evaluating 2D and 3D U-Net models and exploring the benefits of model ensembling.</li>
          <li>Performance Metrics: Rigorous accuracy assessments to gauge model effectiveness.</li>
        </ul>
      </div>
  
      <!-- Installation and Usage -->
      <div class="inner-content">
        <h3 class="subheading"><b>Installation and Usage</b></h3>
        <p class="paragraph">
          Detailed instructions on setting up the environment, installing dependencies, and running the project are included in the Jupyter notebooks 
          in this GitHub repo or alternatively can be downloaded through the linked Google Drive folder:
        </p>
        <p class="paragraph">
          <a href="https://drive.google.com/drive/folders/1VyDjyxmIOIqtz3fJIiDmQX-El107EVYy" class="text-blue-600 underline">Code files</a>
        </p>
      </div>
  
      <!-- Results -->
      <div class="inner-content">
        <h3 class="subheading"><b>Results</b></h3>
        <p class="paragraph">
          Initial findings indicate superior performance of the 3D U-Net models trained on the BRATS 2021 dataset, highlighting the project's 
          potential as a significant contribution to the field of medical imaging and artificial intelligence.
        </p>
      </div>
  
      <!-- Credits -->
      <div class="inner-content">
        <h3 class="subheading"><b>Credits</b></h3>
        <p class="paragraph">
          Team Members:
        </p>
        <ul class="paragraph list-disc pl-6">
          <li>Jovan Yap</li>
          <li>Xu Boyu</li>
          <li>Duan Lingbo</li>
          <li>Kai Chan</li>
          <li>Shu Bohan</li>
        </ul>
      </div>
  
      <!-- References -->
      <div class="inner-content">
        <h3 class="subheading"><b>References</b></h3>
        <ul class="paragraph list-disc pl-6">
          <li><a href="https://paperswithcode.com/paper/unetformer-a-unified-vision-transformer-model" class="text-blue-600 underline">UNetFormer: A Unified Vision Transformer Model</a></li>
          <li><a href="https://www.frontiersin.org/articles/10.3389/fncom.2020.00025/full" class="text-blue-600 underline">Brain Tumor Segmentation Using an Ensemble of 3D U-Nets</a></li>
          <li><a href="https://www.med.upenn.edu/cbica/brats2020/data.html" class="text-blue-600 underline">BRATS Dataset 2020</a></li>
          <li><a href="http://braintumorsegmentation.org/" class="text-blue-600 underline">BRATS Dataset 2021</a></li>
        </ul>
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
