# ZHU Zhongxin — Data Science Portfolio

MSc student at the University of Macau. This site collects the data-analysis projects
I build for **CISC7204 Data Science and Data Visualization** (2026-2027, Semester 1)
and beyond: each project pairs a public dataset with a research question and a
visualization that answers it.

## Technical skills

- **Languages & analysis:** Python (pandas, NumPy, SciPy, scikit-learn)
- **Visualization:** matplotlib, seaborn, geoplotlib (dot density, histograms, Voronoi,
  choropleths, custom layers), Bokeh, Plotly & Dash
- **Workflow:** Jupyter Notebook, Anaconda environments, Git & GitHub Pages,
  SQL basics (IBM Data Analysis course work)

## Project showcase

### Plotting Poaching Density in Tanzania

**Research question.** Poaching incidents are reported as isolated latitude/longitude
points. Where do these incidents concentrate, and which geoplotlib layer type — dot
density, histogram or Voronoi tessellation — makes the concentration pattern easiest
to read?

**Visualization.** The dot density map below plots all 268 incidents on a map of
central Tanzania; the histogram and Voronoi variants are in the project repository.

![Dot density of poaching incidents in Tanzania](dot_density.png)

**Findings.** The incidents cluster inside the Ruaha landscape: the dot map shows a
dense core inside the park boundaries, the histogram highlights the same hotspots and
the empty buffer zones around them, and the Voronoi tessellation exposes one large
dark-blue cell at the centre-right edge that the histogram understates. One
limitation: the table has no severity or species fields, so the maps show where
incidents happen, not how serious each one was.

**Repository:** [data-science-project](https://github.com/zhuzhongxin66272/data-science-project)
— notebook, dataset, pinned requirements and the three map images.

**Status:** completed.

## Contact

- Course: CISC7204-001-K, University of Macau
- Student ID: MC662722
- GitHub: [zhuzhongxin66272](https://github.com/zhuzhongxin66272)
