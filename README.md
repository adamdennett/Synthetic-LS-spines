# Synthetic-LS-spines
Created by <a href="http://calls.ac.uk" target="_blank">CALLS Hub</a> - Source for downloading synthetic LS spines and related documentation

The England and Wales Longitudinal Study (ONS LS), Scottish Longitudinal Study (SLS) and Northern Ireland Longitudinal Study (NILS) are incredibly rich micro-datasets linking census and other health and administrative data (births, deaths, marriages, cancer registrations) for individuals and their immediate families across several decades. Whilst unique and valuable resources, the sensitive nature of the information they contain means that access to the microdata is restricted to approved researchers and LS support staff, who can only view and work with the data in safe settings controlled by the national statistical agencies. Consequently, compared to other census data products such as the aggregate statistics or interaction data, the three longitudinal studies are used by a small number of researchers - a situation which limits their potential impact.

Given that confidentiality constraints mean that open access is not possible with the real microdata, alternative options are needed to allow academics and other users to carry out their research more freely. To address this the SYLLS project (Synthetic Data Estimation for UK Longitudinal Studies) has been set up.  SYLLS is developing techniques to produce synthetic data which mimics the real data and preserves the relationships between variables and transitions of individuals over time, but is more freely accessible. This project is a collaboration between the three UK Longitudinal Study Research Support Units - CeLSIUS, SLS-DSU and the NILS-RSU - makes use of two complementary methods for generating synthetic data products (see http://calls.ac.uk/guides-resources/synthetic-ls-data/). 

The repository hosted here allows you to download files and documentation relating to one of the strands of the SYLLS project, which created downloadable synthetic teaching datasets. A simple proportional fitting algorithm has been used to extend the national 2011 Census Microdata Teaching files (derived from the Samples of Anonymised Records) to include longitudinal transitions (currently a ten year transition back to 2001), derived from the real LS data. The Synthetic Spine state transitions are for some of the most commonly used variables in social science research, including health, marital status, social grade and religion, as well as estimates for the numbers of births and deaths. These data are for general use and will allow users who are unfamiliar with longitudinal data to get a feel for the kinds of questions that can be answered by following individuals through time and observing changes in their characteristics.

You can read more about the technique for creating synthetic spine datasets in this <a href="http://calls.ac.uk/output-entry/a-synthetic-longitudinal-study-dataset-for-england-and-wales/" target="_blank">journal paper</a>. More information can be found in this <a href="http://calls.ac.uk/2014/01/10/synthetic-data-for-the-uk-longitudinal-studies-sylls/" target="_blank">blog post</a> by Dr Adam Dennett.

The following files are currently available:

<ul>
 <li><a href="https://github.com/Fiona-C/Synthetic-LS-spines/raw/386188d3d2c5e9b06e2bb9c2eb6b9bc804538a6a/ONS%20Microdatateachingvariables.pdf" target="_blank">ONS Microdatateachingvariables.pdf</a> - Description of the ONS Census Microdata variables used to create the ONS LS synthetic spine (PDF 420KB)</li>
 <li><a href="https://github.com/Fiona-C/Synthetic-LS-spines/raw/c64bde7fff8eeb72ebe49590a3747a3481431680/SYLLS_Synthetic_ONSLS_Spine_Final_a.xlsx" target="_blank">SYLLS_Synthetic_ONSLS_Spine_Final_a.xlsx</a> - The synthetic ONS LS spine dataset (XLSX 64MB)</li>
 <li><a href="https://github.com/Fiona-C/Synthetic-LS-spines/raw/d65d6e3e749874e35927280ec7bf4a087ad66534/SYLLS_Synthetic_SLS_Spine_updated.xlsx" target="_blank">SYLLS_Synthetic_SLS_Spine_updated.xlsx</a> - The synthetic SLS spine dataset (XLSX 8.9MB)</li>
 <li><a href="https://github.com/Fiona-C/Synthetic-LS-spines/raw/18a37dbe6988104534629976a1457a32762d01af/NILS%20Synthetic%20Data%20Spine.xlsx" target="_blank">NILS_Synthetic_Data_Spine.xlsx</a> - The synthetic NILS spine dataset (XLSX 2.08MB)</li>
 </ul>

Some useful links:

<ul>
 	<li><a href="http://rpubs.com/adam_dennett/80649" target="_blank" rel="noopener">Practical exercise using the ONS LS spine data</a> (link to Adam Dennett's blog)</li>
 	<li><a href="http://calls.ac.uk/wp-content/uploads/ScriptForLSSpineData.R.zip" target="_blank" rel="noopener">R script used for creating the synthetic spine</a> (ZIP 8KB)</li>
 	<li><a href="http://calls.ac.uk/output-entry/a-synthetic-longitudinal-study-dataset-for-england-and-wales/" target="_blank" rel="noopener">Journal paper about the methodology</a> (open access)</li>
  <li><a href="http://calls.ac.uk/guides-resources/synthetic-ls-data/" target="_blank">More information about the SYLLS project and the LSs</a> (link to page on CALLS Hub website)</li>
</ul>

# NOTE: 
The datasets contain synthetic data based on the ONS Longitudinal Study for England and Wales (ONS LS), the Scottish Longitudinal Study (SLS) and the Northern Ireland Longitudinal Study (NILS) and do not contain real ONS LS, SLS or NILS data. The synthetic datasets have been developed for teaching purposes and for researchers to familiarise themselves with longitudinal data. Real ONS LS microdata are available in safe settings in London, Newport, South Wales and Titchfield in Hampshire. Real SLS microdata are available in the safe setting in Edinburgh. Real NILS microdata are available in the safe setting in Belfast. The microdata are never released outside these safe settings. Researchers may apply to use ONS LS data by contacting <a href="mailto:celsius@ucl.ac.uk">CeLSIUS</a>, based at University College London, to use SLS data by contacting <a href="mailto:sls@lscs.ac.uk">SLS-DSU</a>, based at Ladywell House, Edinburgh or to use NILS data by contacting <a href="mailto:rsu@nisra.gov.uk">NILS-RSU</a>, based at Queen's University Belfast. The ONS LS, SLS and NILS synthetic spines are released under an Open Government Licence agreement.


CeLSIUS, SLS-DSU, NILS-RSU, CALLS Hub and SYLLS are funded by the Economic and Social Research Council (ESRC). For more information please visit the <a href="http://calls.ac.uk" target="_blank">CALLS Hub website</a>.
