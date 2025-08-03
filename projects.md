---
title: Projects
feature_image: "https://picsum.photos/2560/600?image=201"
---
<head>
<title>Table with Buttons and Rules</title>
<style>
  table {
    width: 100%;
    border-collapse: collapse;
  }

  /* Top rule */
  table thead {
    border-top: 2px solid black;
  }

  /* Middle rule (between header and body) */
  table tbody {
    border-top: 1px solid black;
  }

  /* Bottom rule */
  table tfoot {
    border-top: 2px solid black; /* Can also be applied to tbody if no tfoot */
  }

  th, td {
    padding: 8px;
    text-align: left;
  }

  th {
    font-weight: bold;
  }

  .action-button {
    background-color: #4CAF50; /* Green */
    color: white;
    padding: 8px 12px;
    border: none;
    border-radius: 4px;
    cursor: pointer;
    font-size: 14px;
  }

  .action-button:hover {
    background-color: #45a049;
  }
</style>
</head>
<body>
 <table>
      <thead>
        <tr>
          <th><b>Project</b></th>
          <th><b>Tasks</b></th>
          <th><b>Tools</b></th>
          <th><b>Repository</b></th>
        </tr>
      </thead>
      <tbody>
      <tr>
          <td>Resume summarization using GenAI</td>
          <td>GenAI, NLP, Summarization </td>
          <td>Python, Jupyter Notebook, os, requests, dotenv, pypdf, openai, docx</td>
          <td>{% include button.html text="GitHub" icon="github" link="https://github.com/samuel-sousa/LLM-applications/blob/main/resume_summarization.ipynb/" color="#000000" %}</td>
      </tr>
      <tr>
          <td>Semi-Supervised WSD</td>
          <td>NLP, Classification </td>
          <td>Python, numpy, scipy, sklearn, pandas, networkx, abc</td>
          <td>{% include button.html text="GitHub" icon="github" link="https://github.com/samuel-sousa/Master_thesis_experiments/" color="#000000" %}</td>
      </tr>
      <tr>
          <td>Analysis of clustering algorithms</td>
          <td>Geospatial data analysis, Clustering </td>
          <td>R</td>
          <td>{% include button.html text="GitHub" icon="github" link="https://github.com/samuel-sousa/Clei-Laclo-2018/" color="#000000" %}</td>
       </tr>
       <tr>
          <td>Testing Doc2Vec embeddings</td>
          <td>NLP</td>
          <td>Python, gensim, nltk, numpy, pandas, sklearn, matplotlib, time</td>
          <td>{% include button.html text="GitHub" icon="github" link="https://github.com/samuel-sousa/Doc2Vecs/" color="#000000" %}</td>
        </tr>
        <tr>
          <td>Integer programming</td>
          <td>Optimization</td>
          <td>Python, cvxpy, numpy</td>
          <td>{% include button.html text="GitHub" icon="github" link="https://github.com/samuel-sousa/Integer_Programming_CVXPY/" color="#000000" %}</td>
        </tr>
      </tbody>
    <tfoot>
      <tr>
        <td colspan="4">End of projects</td>
      </tr>
    </tfoot>
  </table>
</body>