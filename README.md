# Synthetic-LS-spines
Created by <a href="https://calls.ac.uk" target="_blank">CALLS Hub</a> - Source for downloading synthetic LS spines and related documentation

The England and Wales Longitudinal Study (ONS LS), Scottish Longitudinal Study (SLS) and Northern Ireland Longitudinal Study (NILS) are incredibly rich micro-datasets linking census and other health and administrative data (births, deaths, marriages, cancer registrations) for individuals and their immediate families across several decades. Whilst unique and valuable resources, the sensitive nature of the information they contain means that access to the microdata is restricted to approved researchers and LS support staff, who can only view and work with the data in safe settings controlled by the national statistical agencies. Consequently, compared to other census data products such as the aggregate statistics or interaction data, the three longitudinal studies are used by a small number of researchers - a situation which limits their potential impact.

Given that confidentiality constraints mean that open access is not possible with the real microdata, alternative options are needed to allow academics and other users to carry out their research more freely. To address this the SYLLS project (Synthetic Data Estimation for UK Longitudinal Studies) has been set up.  SYLLS is developing techniques to produce synthetic data which mimics the real data and preserves the relationships between variables and transitions of individuals over time, but is more freely accessible. This project is a collaboration between the three UK Longitudinal Study Research Support Units - CeLSIUS, LSCS and the NILS-RSU - makes use of two complementary methods for generating synthetic data products (see http://calls.ac.uk/guides-resources/synthetic-ls-data/). 

The repository hosted here allows you to download files and documentation relating to one of the strands of the SYLLS project, which created downloadable synthetic teaching datasets. A simple proportional fitting algorithm has been used to extend the national 2011 Census Microdata Teaching files (derived from the Samples of Anonymised Records) to include longitudinal transitions (currently a ten year transition back to 2001), derived from the real LS data. The Synthetic Spine state transitions are for some of the most commonly used variables in social science research, including health, marital status, social grade and religion, as well as estimates for the numbers of births and deaths. These data are for general use and will allow users who are unfamiliar with longitudinal data to get a feel for the kinds of questions that can be answered by following individuals through time and observing changes in their characteristics.

You can read more about the technique for creating synthetic spine datasets in this <a href="http://calls.ac.uk/output-entry/a-synthetic-longitudinal-study-dataset-for-england-and-wales/" target="_blank">journal paper</a>. More information can be found in this <a href="http://calls.ac.uk/2014/01/10/synthetic-data-for-the-uk-longitudinal-studies-sylls/" target="_blank">blog post</a> by Dr Adam Dennett.

The following files are available:

<ul>
 <li><a href="Synthetic-LS-spines/ONS Microdatateachingvariables.pdf" target="_blank"></a> Description of the ONS Census Microdata variables used to create the ONS LS synthetic spine (PDF 420KB)</li>
 </ul>

Some useful links:

<ul>
 	<li><a href="http://rpubs.com/adam_dennett/80649" target="_blank" rel="noopener">Practical exercise using the spine data</a> (link to Adam Dennett's blog)</li>
 	<li><a href="http://calls.ac.uk/wp-content/uploads/ScriptForLSSpineData.R.zip" target="_blank" rel="noopener">R script used for creating the synthetic spine</a> (ZIP 8KB)</li>
 	<li><a href="http://calls.ac.uk/output-entry/a-synthetic-longitudinal-study-dataset-for-england-and-wales/" target="_blank" rel="noopener">Journal paper about the methodology</a> (open access)</li>
  <li><a href="http://calls.ac.uk/guides-resources/synthetic-ls-data/" target="_blank">More information about the SYLLS project and the LSs</a></li>
</ul>

# NOTE: 
The dataset contains synthetic data based on the ONS Longitudinal Study for England and Wales (ONS LS) and does not contain real ONS LS data. The synthetic dataset has been developed for teaching purposes and for researchers to familiarise themselves with longitudinal data. Real ONS LS microdata are available in safe settings in London, Newport, South Wales and Titchfield in Hampshire. The microdata are never released outside these safe settings. Researchers may apply to use these data by contacting CeLSIUS, based at University College London. The ONS LS synthetic spine is released under an Open Government Licence agreement.
