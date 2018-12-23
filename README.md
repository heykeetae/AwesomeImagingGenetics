# Awesome Imaging Genetics
Recent advances in artificial intelligence (AI) has been largely reflected in radiomics, an academic area connecting the high-throughput information of images (or imaging phenotype) with clinical outcomes, such as tumor detection, secmentation or disease stages. A conventional research pipelines in radionomics were 1) data and label processing, 2) (hand-crafted)feature selection, and 3) correlation analysis between the selected features and disease biomarkers. The 2) feature selection and the 3) correlation analysis have been integrated via AI techniques, most of them employing the convolutional neural networks as the training backbone. 

Imaging genomics can be regarded as an extension to radiomics, where we attempt to predict and trace genotypic information from medical imaging phenotype, rather than tumors and diseases. While tumors and disease patterns might be quite obvious in the human eyes, genotypic information or protein expression is harder to trace from images, where the AI techniques come into play. This is an interesting research area, which is inherently interdisciplinary at the intersection of biology, biophysics, medical imaging, computer science and engineering, and perhaps more areas.      
## Imaging Genetics
Imaging Genetics, i.e., Imaging Genomics or Radiogenomics, is a rapidly evolving field connecting the cellular genomics and medical image analysis. In this document, the exact name of the research area is interchangeably referred to any one of in the three different names, until it has a standardized name agreed by scholars. It primarily concerns tracking genetic variations from the imaging phenotype. Driven by recent advances in machine learning and active application of the algorithm, a host of novel research ideas have been brought into fruition. To highlight those efforts, the long-term goal of this repository is to list relevant research papers and summarize available public datasets, with a focus on machine learning approaches.  
<p align="center"><img width="60%" src="images/conceptual_drawing.png" /></p>
The figure above illustrates the intuition of Imaging Genetics. We would like to trace genetic information underlying the patterns (or phenotype) found on medical images! (Don't be misguided, I do not claim that we can trace all the genetic mutations in a colorectal tissue as in the feagure, the figure is for illustrative purpose only.) 

## Current update status
* [ ] Paper list
* [ ] More datasets
* [ ] Major datasets

## Paper list
- This paper list is partially attributable to the following papers.
  * Lee et al., [Radiomics and imaging genomics in precision medicine](https://www.pfmjournal.org/journal/view.php?number=9), *Precision and Future Medicine*, 2017
  * Bai et al., [Imaging genomics in cancer research: limitations
and promises](https://www.ncbi.nlm.nih.gov/pubmed/26864054), *The British Journal of Radiology*, 2016

* Imaging Genomics (Radiogenomics, Imaging Genetics)
  * Halpenny et al., [Radiogenomic evaluation of lung cancer: are there imaging characteristics associated with lung adenocarcinomas harboring BRAF mutations?](https://www.ncbi.nlm.nih.gov/pubmed/28012356), *Clinical Imaging*, 2017
  * Demerath et al., [Mesoscopic imaging of glioblastomas: Are diffusion, perfusion and spectroscopic measures influenced by the radiogenetic phenotype?](https://www.ncbi.nlm.nih.gov/pubmed/27864578), *The Neuroradiology Journal*, 2016
  * Wiestler et al., [Multiparametric MRI-based differentiation of WHO grade II/III glioma and WHO grade IV glioblastoma](https://www.ncbi.nlm.nih.gov/pubmed/27739434), *Scientific Reports*, 2016
  * Kickingereder et al., [Radiogenomics of glioblastoma: machine learning-based classification of molecular characteristics by using multiparametric and multiregional MR imaging features](https://pubs.rsna.org/doi/10.1148/radiol.2016161382), *Radiology*, 2016
  * Heiland et al., [Molecular differences between cerebral blood volume and vessel size in glioblastoma multiforme](https://www.ncbi.nlm.nih.gov/pubmed/27613830), *Oncotarget*, 2016
  * Hu et al., [Radiogenomics to characterize regional genetic heterogeneity in glioblastoma](https://www.ncbi.nlm.nih.gov/pubmed/27502248), *Neuro-Oncology*, 201
  * Saha et al., [Interobserver variability in identification of breast tumors in MRI and its implications for prognostic biomarkers and radiogenomics](https://www.ncbi.nlm.nih.gov/pubmed/27487872), *Medical Physics*, 2016
  * Mehta et al., [Radiogenomics monitoring in breast cancer identifies metabolism and immune checkpoints as early actionable mechanisms of resistance to anti-angiogenic treatment](https://www.ncbi.nlm.nih.gov/pubmed/27474395), *EBioMedicine*, 2016
  * Stoyanova et al., [Association of multiparametric MRI quantitative imaging features with prostate cancer gene expression in MRI-targeted prostate biopsies](https://www.ncbi.nlm.nih.gov/pubmed/27438142), *Oncotarget*, 2016
  * Zhao et al., [Reproducibility of radiomics for deciphering tumor phenotype with imaging](https://www.ncbi.nlm.nih.gov/pubmed/27009765), *Scientific Reports*, 2016
  * McCann et al., [Quantitative multiparametric MRI features and PTEN expression of peripheral zone prostate cancer: a pilot study](https://www.ncbi.nlm.nih.gov/pubmed/27009765), *American Journal of Roentgenology*, 2016
  * Guo et al., [Prediction of clinical phenotypes in invasive breast carcinomas from the integration of radiomics and genomics data](https://www.ncbi.nlm.nih.gov/pubmed/26835491), *Journal of Medical Imaging*, 2016
  * Zhu et al., [Deciphering genomic underpinnings of quantitative MRI-based radiomic phenotypes of invasive breast carcinoma](https://www.nature.com/articles/srep17787), *Scientific Reports*, 2015
  * Kickingereder et al., [IDH mutation status is associated with a distinct hypoxia/angiogenesis transcriptome signature which is non-invasively predictable with rCBV imaging in human glioma](https://www.ncbi.nlm.nih.gov/pubmed/26538165), *Scientific Reports*, 2015
  * Rao et al., [A combinatorial radiographic phenotype may stratify patient survival and be associated with invasion and proliferation characteristics in glioblastoma](https://www.ncbi.nlm.nih.gov/pubmed/26473782), *Journal of Neurosurgery*, 2016
  * Gutman et al., [Somatic mutations associated with MRI-derived volumetric features in glioblastoma](https://www.ncbi.nlm.nih.gov/pubmed/26337765), *Neuroradiology*, 2015
  * Renard-Penna et al., [Multiparametric magnetic resonance imaging predicts postoperative pathology but misses aggressive prostate cancers as assessed by cell cycle progression score](https://www.ncbi.nlm.nih.gov/pubmed/26272031), *Journal of Urology*, 2015
  * Shinagare et al., [Radiogenomics of clear cell renal cell carcinoma: preliminary findings of The Cancer Genome Atlas-Renal Cell Carcinoma (TCGA-RCC) Imaging Research Group](https://www.ncbi.nlm.nih.gov/pubmed/25753955), *Abdominal Radiology*, 2015
  * Wang et al., [Anatomical localization of isocitrate dehydrogenase 1 mutation: a voxel-based radiographic study of 146 low-grade gliomas](https://www.ncbi.nlm.nih.gov/pubmed/25318355), *European Journal of Neurology*, 2015
  * Halpenny et al., [Are there imaging characteristics associated with lung adenocarcinomas harboring ALK rearrangements?](https://www.ncbi.nlm.nih.gov/pubmed/25312988), *Lung Cancer*, 2014
  * Gevaert et al., [Glioblastoma multiforme: exploratory radiogenomic analysis by using quantitative image features](https://www.ncbi.nlm.nih.gov/pubmed/24827998), *Radiology*, 2014
  * Nair et al., [NF- kappaB protein expression associates with (18)F-FDG PET tumor uptake in non-small cell lung cancer: a radiogenomics validation study to understand tumor metabolism](https://www.ncbi.nlm.nih.gov/pubmed/24355259), *Lung Cancer*, 2014
  * Jamshidi et al., [Illuminating radiogenomic characteristics of glioblastoma multiforme through integration of MR imaging, messenger RNA expression, and DNA copy number variation](https://www.ncbi.nlm.nih.gov/pubmed/24056404), *Radiology*, 2014
  * Karlo et al., [Radiogenomics of clear cell renal cell carcinoma: associations between CT imaging features and mutations](https://www.ncbi.nlm.nih.gov/pubmed/24029645), *Radiology*, 2014
  * De Ruysscher et al., [Quantification of radiation-induced lung damage with CT scans: the possible benefit for radiogenomics](https://www.ncbi.nlm.nih.gov/pubmed/23957564), *Acta Oncologica*, 2013
  * Zinn et al., [Radiogenomic mapping of edema/cellular invasion MRI-phenotypes in glioblastoma multiforme](https://www.ncbi.nlm.nih.gov/pubmed/21998659), *PLoS One*, 2011
  * Gevaert et al., [Non-small cell lung cancer: identifying prognostic imaging biomarkers by leveraging public gene expression microarray data: methods and preliminary results](https://www.ncbi.nlm.nih.gov/pubmed/22723499), *Radiology*, 2012
  * Aerts et al., [Decoding tumour phenotype by noninvasive imaging using a quantitative radiomics approach](https://www.nature.com/articles/ncomms5006), *Nature Communications*, 2014
  * Kuo et al., [Radiogenomic analysis to identify imaging phenotypes associated with drug response gene expression programs in hepatocellular carcinoma](https://www.ncbi.nlm.nih.gov/pubmed/17609439), *Journal of Vascular and Interventional Radiology*, 2007
  * Nair et al., [Prognostic PET 18F-FDG uptake imaging features are associated with major oncogenomic alterations in patients with resected non-small cell lung cancer](https://www.ncbi.nlm.nih.gov/pubmed/22710433), *Cancer Research*, 2012
  * Segal et al., [Decoding global gene expression programs in liver cancer by noninvasive imaging](https://www.nature.com/articles/nbt1306), *Nature Biotechnology*, 2007
  * Yamamoto et al., [Radiogenomic analysis of breast cancer using MRI: a preliminary study to define the landscape](https://www.ncbi.nlm.nih.gov/pubmed/22915408), *American Journal of Roentgenology*, 2012
  * Yamamoto et al., [Breast cancer: radiogenomic biomarker reveals associations among dynamic contrast-enhanced MR imaging, long noncoding RNA, and metastasis](https://www.ncbi.nlm.nih.gov/pubmed/25734557), *Radiology*, 2015
  * Barajas et al., [Glioblastoma multiforme regional genetic and cellular expression patterns: influence on anatomic and physiologic MR imaging](https://www.ncbi.nlm.nih.gov/pubmed/20093527), *Radiology*, 2010
  * Diehn et al., [Identification of noninvasive imaging surrogates for brain tumor gene-expression modules](https://www.ncbi.nlm.nih.gov/pubmed/18362333), *PNAS*, 2008
  * Pope et al., [Relationship between gene expression and enhancement in glioblastoma multiforme: exploratory DNA microarray analysis](https://www.ncbi.nlm.nih.gov/pubmed/18796682), *Radiology*, 2008
  * Zinn et al., [A novel volume-age-KPS (VAK) glioblastoma classification identifies a prognostic cognate microRNA-gene signature](https://www.ncbi.nlm.nih.gov/pubmed/22870228), *PLoS One*, 2012
  * Jamshidi et al., [The radiogenomic risk score: construction of a prognostic quantitative, noninvasive imagebased molecular assay for renal cell carcinoma](https://www.ncbi.nlm.nih.gov/pubmed/26402495), *Radiology*, 2015
  * Colen et al., [NCI Workshop Report: clinical and computational requirements for correlating imaging phenotypes with genomics signatures](https://www.ncbi.nlm.nih.gov/pubmed/25389451), *Translational Oncology*, 2014
  * Carlson et al., [Relationship between survival and edema in malignant gliomas: role of vascular endothelial growth factor and neuronal pentraxin 2](https://www.ncbi.nlm.nih.gov/pubmed/17473188), *Clinical Cancer Research*, 2007
  * Colen et al., [TCGA Glioma Phenotype Research Group. Imaging genomic mapping of an invasive MRI phenotype predicts patient outcome and metabolic dysfunction: a TCGA glioma phenotype research group project](https://www.ncbi.nlm.nih.gov/pubmed/24889866), *BMC Medical Genomics*, 2014
  * Jain et al., [Correlation of perfusion parameters with genes related to angiogenesis regulation in glioblastoma: a feasibility study](https://www.ncbi.nlm.nih.gov/pubmed/22422183), *American Journal of Neuroradiology*, 2012
  * Naeini et al., [Identifying the mesenchymal molecular subtype of glioblastoma using quantitative volumetric analysis of anatomic magnetic resonance images](https://www.ncbi.nlm.nih.gov/pubmed/23444259), *Neuro-Oncology*, 2013
  * Nicolasjilwan et al., [TCGA Glioma Phenotype Research Group. Addition of MR imaging features and genetic biomarkers strengthens glioblastoma survival prediction in TCGA patients](https://www.ncbi.nlm.nih.gov/pubmed/24997477), *Journal of Neuroradiology*, 2015
  * Pope et al., [Non-invasive detection of 2-hydroxyglutarate and other metabolites in IDH1 mutant glioma patients using magnetic resonance spectroscopy](https://www.ncbi.nlm.nih.gov/pubmed/22015945), *Journal of Neuro-Oncology*, 2012
  * Osborne et al., [18F-FDG PET of locally invasive breast cancer and association of estrogen receptor status with standardized uptake value: microarray and immunohistochemical analysis](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4141648/), *Journal of Nuclear Medicine*, 2010
  * Palaskas et al., [18F-fluorodeoxy-glucose positron emission tomography marks MYC-overexpressing human basal-like breast cancers](), *Cancer Research*, 2011
  * Zhu et al., [Brain metastasis in children with stage 4 neuroblastoma after multidisciplinary treatment](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4593360/), *Chinese Journal of Cancer*, 2015
  * Miura et al., [Distinct clinicopathological phenotype of hepatocellular carcinoma with ethoxybenzylmagnetic resonance imaging hyperintensity: association with gene expression signature](https://www.ncbi.nlm.nih.gov/pubmed/26105803), *The American Journal of Surgery*, 2015
  * Halle et al., [Hypoxiainduced gene expression in chemoradioresistant cervical cancer revealed by dynamic contrast-enhanced MRI](https://www.ncbi.nlm.nih.gov/pubmed/22890239), *Cancer Research*, 2012
  *  et al., [](), **, 20
  *  et al., [](), **, 20
  *  et al., [](), **, 20
  *  et al., [](), **, 20
  *  et al., [](), **, 20
  *  et al., [](), **, 20
  *  et al., [](), **, 20
  

## Datasets
Datasets are perhaps the pre-requisites for any research studies in this area, where we need 1)large-scale imaging data, 2) paired with genotypic information. Here we review some rich publicly available datasets.

### \[1\] The Cancer Genomic Atlas ([TCGA](https://cancergenome.nih.gov/abouttcga/overview)) - lung adenocarcinoma (LUAD)
### \[2\] The Cancer Genomic Atlas ([TCGA](https://cancergenome.nih.gov/abouttcga/overview)) - lung adenocarcinoma (LUAD)
### \[3\] The Cancer Genomic Atlas ([TCGA](https://cancergenome.nih.gov/abouttcga/overview)) - lung adenocarcinoma (LUAD)
### \[4\] The Cancer Genomic Atlas ([TCGA](https://cancergenome.nih.gov/abouttcga/overview)) - lung adenocarcinoma (LUAD)

