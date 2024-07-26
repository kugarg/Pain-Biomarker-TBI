<h1>Biomarker-Based Analysis of Pain in Patients with Tick-Borne Infections before and after Antibiotic Treatment</h1>

<h2>Abstract</h2>
<p>This study investigates the correlation between pain and biomarkers in tick-borne infection (TBI) patients from an Irish hospital. We found that age and gender do not influence pain ratings at baseline (T0) or follow-up (T2), but pain ratings significantly decreased post-treatment. Notable changes in transferrin, transferrin saturation %, platelets, neutrophils, and CD4% were observed. Temporal analysis showed correlations between pain ratings and said biomarkers, but also suggested external influences on pain perception. However, biomarkers did not directly predict pain changes when accounting for overall trends, indicating that while certain biomarkers fluctuate with pain, they are unreliable indicators of pain levels or treatment efficacy in this context.</p>

<h2>Repository running name: Pain-Biomarker-TBI</h2>

<h3>Repository Description</h3>
<p>This repository contains the data and analysis code for the study "Biomarker-Based Analysis of Pain in Patients with Tick-Borne Infections before and after Antibiotic Treatment." The study investigates the relationship between pain and biomarkers in patients with tick-borne infections (TBIs) before and after antibiotic treatment.</p>

<h3>Table of Content</h3>
<ol>
    <li><a href="#introduction">Introduction</a></li>
    <li><a href="#data">Data</a></li>
    <li><a href="#folder-structure-and-content">Folder Structure and Content</a></li>
    <li><a href="#steps-to-download-and-reproduce">Steps to Download and Reproduce</a></li>
    <li><a href="#licenses">Licenses</a></li>
    <li><a href="#results">Results</a></li>
    <li><a href="#feedback">Feedback</a></li>
    <li><a href="#references">References</a></li>
    <li><a href="#cite-this-repo-as">Cite Pain-Biomarker-TBI Repository</a></li>
</ol>

<h3 id="introduction">Introduction</h3>
<p>Tick-borne illnesses, especially those caused by Borrelia, are increasing globally, with late-stage symptoms often leading to Post-treatment Lyme disease syndrome (PTLDS) or Chronic Lyme Disease (CLD). This study explores the relationship between pain and biomarkers in TBI patients from an Irish hospital, assessing changes from baseline (T0) to follow-up (T2) post-antibiotic treatment.</p>

<h3 id="data">Data</h3>
<p>The data folder contains a CSV file with the following columns:</p>
<ul>
    <li><strong>Number</strong>: Deidentified patient number</li>
    <li><strong>Timepoint</strong>: Data at baseline before antibiotic treatment (T0) or follow-up after antibiotic treatment (T2)</li>
    <li><strong>Age</strong>: Ranging between 17 and 81 years</li>
    <li><strong>Gender</strong>: F for Female, M for Male</li>
    <li><strong>Pain rating</strong>: Reported by patients through a questionnaire and ranges from 1 to 10</li>
    <li><strong>CD3%</strong>: Reference range 61% to 84%</li>
    <li><strong>CD3Total</strong>: Reference range 960 to 2600 cells/ul</li>
    <li><strong>CD8%</strong>: Reference range 13% to 40%</li>
    <li><strong>CD8-Suppr</strong>: CD8-suppressor reference range 270 to 930 cells/ul</li>
    <li><strong>CD4%</strong>: Reference range 32% to 60%</li>
    <li><strong>CD4-Helper</strong>: CD4+ Helper T cell count reference range 540 to 1600 cells/ul</li>
    <li><strong>H/S-ratio</strong>: Helper/suppressor (H/S) ratio reference range 0.9 to 4.5</li>
    <li><strong>HgB</strong>: Hemoglobin reference range 11.5 to 16.5 g/dL</li>
    <li><strong>Platelets</strong>: Reference range 150 to 400 ×10^9/L</li>
    <li><strong>Neutrophils</strong>: Reference range 2 to 8 ×10^9/L</li>
    <li><strong>Lymphocytes</strong>: Reference range 1 to 4 ×10^9/L</li>
    <li><strong>WCC</strong>: White cell count reference range 3.5 to 11 ×10^9 /L</li>
    <li><strong>CRP</strong>: C-reactive protein reference range &lt;7 mg/L</li>
    <li><strong>Iron</strong>: Reference range 6 to 33 umol/L</li>
    <li><strong>Transf</strong>: Transferrin reference range 1.88 to 3.02 g/dL</li>
    <li><strong>%Trans sat</strong>: Transferrin saturation (%) reference range 19% to 55%</li>
</ul>

<h3 id="folder-structure-and-content">Folder Structure and Content</h3>
<ul>
    <li><strong>data</strong>: Contains the dataset in CSV format.</li>
    <li><strong>figures</strong>: Contains figures and visualizations used in the analysis.</li>
    <li><strong>notebook</strong>: Contains Jupyter notebooks with the analysis code.</li>
    <li><strong>venv</strong>: Contains the virtual environment setup.</li>
    <li><strong>MIT license</strong>: The MIT license file.</li>
    <li><strong>CC-BY-SA-4.0 license</strong>: The Creative Commons BY-SA 4.0 license file.</li>
    <li><strong>requirements.txt</strong>: List of required Python packages.</li>
</ul>

<h3 id="steps-to-download-and-reproduce">Steps to Download and Reproduce</h3>
<ol>
    <li><strong>Download or Clone the Repository</strong>:
        <ul>
            <li>Click on the green "<> Code" button at the top of the repository page.</li>
            <li>Choose either "Download ZIP" to download the repository as a ZIP file or copy its URL to clone it using Git:</li>
            <ul>
                <li>To clone the repository using Git, open your terminal or command prompt and run:
                    <pre><code>git clone https://github.com/yourusername/Pain-Biomarker-TBI.git</code></pre>
                </li>
            </ul>
        </ul>
    </li>
    <li><strong>Extract the ZIP File (if applicable)</strong>:
        <ul>
            <li>If you downloaded the repository as a ZIP file, extract it to a directory of your choice.</li>
        </ul>
    </li>
    <li><strong>Navigate to the Downloaded Folder</strong>:
        <ul>
            <li>Open your terminal or command prompt and navigate to the extracted or cloned repository folder:
                <pre><code>cd Pain-Biomarker-TBI</code></pre>
            </li>
        </ul>
    </li>
    <li><strong>Activate the Virtual Environment</strong>:
        <ul>
            <li>Activate the virtual environment included in the repository:
                <ul>
                    <li>On macOS and Linux, run:
                        <pre><code>source venv/bin/activate</code></pre>
                    </li>
                    <li>On Windows, run:
                        <pre><code>venv\Scripts\activate</code></pre>
                    </li>
                </ul>
            </li>
        </ul>
    </li>
    <li><strong>Run Jupyter Notebook</strong>:
        <pre><code>jupyter notebook</code></pre>
    </li>
    <li><strong>Open the Notebook File</strong>:
        <ul>
            <li>In the Jupyter Notebook interface, navigate to the <code>notebook</code> folder and open the file <code>Pain-Biomarker-TBI.ipynb</code>.</li>
        </ul>
    </li>
    <li><strong>Execute the Code Cells</strong>:
        <ul>
            <li>Run the code cells sequentially to reproduce the analysis and model.</li>
        </ul>
    </li>
</ol>

<h3 id="licenses">Licenses</h3>
<ul>
    <li><strong>MIT License</strong>: See <code>MIT license</code> file for details.</li>
    <li><strong>Creative Commons BY-SA 4.0 License</strong>: See <code>CC-BY-SA-4.0 license</code> file for details.</li>
</ul>

<h3 id="results">Results</h3>
<p>The study found no significant influence of age or gender on pain ratings. Pain ratings significantly decreased from T0 to T2, indicating the effectiveness of antibiotic treatment. Significant changes were observed in transferrin, transferrin saturation (%), platelets, neutrophils, and CD4% between T0 and T2. While these biomarkers fluctuated with pain, they did not directly predict pain changes, suggesting the involvement of external influences and allostatic load in symptom variability among long-term TBI patients.</p>

<h3 id="feedback">Feedback</h3>
<p>We welcome feedback and suggestions! Please open an issue on GitHub if you have any questions, suggestions, or issues with the repository.</p>

<h3 id="references">References</h3>
<ol>
    <li>Garg, K.; Thoma, A.; Avramovic, G.; Gilbert, L.; Shawky, M.; Ray, M.R.; Lambert, J.S. Biomarker-Based Analysis of Pain in Patients with Tick-Borne Infections before and after Antibiotic Treatment. Antibiotics 2024, 13, 693. https://doi.org/10.3390/antibiotics13080693</li>
    <li>Xi, D.; Garg, K.; Lambert, J.S.; Rajput-Ray, M.; Madigan, A.; Avramovic, G.; Gilbert, L. Scrutinizing Clinical Biomarkers in a Large Cohort of Patients with Lyme Disease and Other Tick-Borne Infections. Microorganisms 2024, 12, 380. https://doi.org/10.3390/microorganisms12020380</li>
    <li>Xi, D.; Thoma, A.; Rajput-Ray, M.; Madigan, A.; Avramovic, G.; Garg, K.; Gilbert, L.; Lambert, J.S. A Longitudinal Study of a Large Clinical Cohort of Patients with Lyme Disease and Tick-Borne Co-Infections Treated with Combination Antibiotics. Microorganisms 2023, 11, 2152. https://doi.org/10.3390/microorganisms11092152</li>
</ol>

<h3 id="cite-this-repo-as">Cite this Repository as follows</h3>
<pre><code>@misc{Pain-Biomarker-TBI,
  author = {Kunal Garg, Abbie Thoma, Minha Rajput Ray, Gordana Avramovic, Leona Gilbert, John Shearer Lambert},
  title = {Biomarker-Based Analysis of Pain in Patients with Tick-Borne Infections before and after Antibiotic Treatment},
  year = {2024},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/yourusername/Pain-Biomarker-TBI}},
}</code></pre>

</body>
</html>
