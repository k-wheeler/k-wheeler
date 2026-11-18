# Kathryn Wheeler, Ph.D.

Environmental & Geospatial Data Scientist

I combine remote sensing and geospatial analysis with statistical, mechanistic, and machine learning models to understand how human activity affects our planet's ecosystems. I turn that understanding into decisions, from forecasting forest phenology to assessing contaminant impacts at Superfund sites.

[Website / Portfolio](https://k-wheeler.github.io) · [Resume](https://k-wheeler.github.io/resume/) · [Google Scholar](https://scholar.google.com/citations?user=u70ni9sAAAAJ&hl=en) · [LinkedIn](https://www.linkedin.com/in/kathryn-wheeler-ph-d-aa06659a) · kwheelerecology@gmail.com

## Background

- **Ph.D., Earth and Environment**, Boston University: Certificate in Biogeosciences, NSF Graduate Research Fellow. Dissertation: *Cold-deciduous broadleaf phenology: monitoring using a geostationary satellite and predicting using trigger-less dynamic models*
- **NOAA Climate and Global Change Postdoctoral Fellow**, MIT. Project: *The connections between leaf phenology and mycorrhizae in a changing world*
- **B.S., Environmental Science**, University of Delaware, *summa cum laude*: Full four-year merit scholarship, NOAA Hollings Scholar

Currently a Research Scientist at [**CarbonPlan**](https://carbonplan.org), conducting climate science and impacts research. Previously an Environmental Consulting Associate at [**Industrial Economics, Inc.**](https://indecon.com) (2023 to 2026), supporting Natural Resource Damage Assessments at Superfund sites with spatial statistics, ArcGIS Pro, and machine learning.

## Featured projects

| Repository | What it is |
|---|---|
| [AppTrail_Phenology](https://github.com/k-wheeler/AppTrail_Phenology) | End-to-end machine learning pipeline predicting daily fall foliage phenological state for roughly 15,000 forest pixels along the Massachusetts Appalachian Trail, ingesting NASA HLS satellite imagery via Google Earth Engine. Trained, tuned, and compared decision-tree classifiers and a recurrent neural network (LSTM, PyTorch) to classify per-pixel state. Built the full stack and deployed it as a self-updating webpage: a scheduled GitHub Actions pipeline re-fetches imagery, recomputes predictions, and publishes an interactive map automatically every day, turning a research idea into a live, continuously updating product. [Live map](https://k-wheeler.github.io/phenology/) |
| [chlorophyllCycling](https://github.com/k-wheeler/chlorophyllCycling) | Code behind my Ph.D. research showing autumn senescence in deciduous forests may not require a cold-accumulation trigger, via a Bayesian state-space model. [Preprint](https://www.biorxiv.org/content/10.1101/2023.06.07.544057v1.full) |
| [CarbonAndPhenology](https://github.com/k-wheeler/CarbonAndPhenology) | Modeling the link between autumn senescence and photosynthesis at Harvard Forest, at leaf and canopy scale |
| [NEFI_pheno](https://github.com/k-wheeler/NEFI_pheno) | GOES-16/17 geostationary satellite phenology monitoring and daily NDVI estimation |
| [PNW_LULC](https://github.com/k-wheeler/PNW_LULC) | End-to-end geospatial machine learning pipeline classifying land cover and change across Oregon from Google Earth Engine satellite embeddings. Compared and tuned tree-ensemble, multilayer perceptron, and convolutional neural network models, including a two-head network that predicts land-cover change directly from paired before/after embeddings. Ran CCDC and COLD algorithms to identify timing of land cover change, containerized the trained model with Docker, and deployed it for wall-to-wall inference on Google Cloud Platform. Applied design-based statistical estimation (Olofsson accuracy assessment, stratified bootstrap) to convert raw map output into bias-corrected area and carbon-loss estimates with confidence intervals. |
| [API_Automation_Test](https://github.com/k-wheeler/API_Automation_Test) | An example API web scraper tool built with Claude Code |

See the full [portfolio](https://k-wheeler.github.io/portfolio/) for detailed write-ups, figures, and additional publications.

## Skills

- **Languages:** R, Python, MATLAB, Java, C++
- **Statistics & machine learning:** Bayesian statistics (MCMC, state-space, hierarchical models), generalized additive models, decision trees, tree ensembles (random forests), self-organizing maps, clustering, neural networks (RNNs, CNNs, MLPs), data fusion and assimilation (Kalman and particle filters)
- **Geospatial:** Google Earth Engine, ArcGIS Pro, R spatial packages (sf, terra, raster), Python spatial packages (geopandas)
- **Tools & workflows:** Git, Docker, Google Cloud Platform, high-performance/shared computing clusters, Slurm, shell scripting, Claude Code

## Publications

12 peer-reviewed papers spanning ecological forecasting, remote sensing of phenology, and forest ecophysiology. Full list with links on my [portfolio](https://k-wheeler.github.io/portfolio/) and [Google Scholar](https://scholar.google.com/citations?user=u70ni9sAAAAJ&hl=en).
