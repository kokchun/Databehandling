# Databehandling (2021)

## UNDER CONSTRUCTION!!

This is a course with focus of learning concepts in data analysis. All lecture codes and exercises can be found in the course [Github repo][ghr].

[ghr]: https://github.com/kokchun/Databehandling-21

## Contents

- [Schedule](#schedule)
- [Resources](#resources) <details> <summary> Weeks </summary>
  - [Week 42](#week1)
  - [Week 43](#week2)
  - [Week 44](#week3)
  - [Week 45](#week4)
  - [Week 46](#week5)

</details>

## Schedule

<details open>
  
<summary id="schedule">Click to see/hide schedule</summary>


|     Week     | Content                                                                    |
| :----------: | -------------------------------------------------------------------------- |
| [42](#week1) | pandas, series, dataframe, index, missing data, selection, aggregate       |
| [43](#week2) | merge, concatenate, join, groupby, filter, sort, apply, strings, **lab 1** |
| [44](#week3) | dates, regular expression, data formats, high performance, **project**     |
| [45](#week4) | PCA, GDPR, KPI, anonymize data, **project**                                |
| [46](#week5) | **project**                                                                |

</details>

## Resources

Many exercises and lecture materials are in form of Jupyter notebooks with **.ipynb** extensions. Sometimes GitHub may not load them correctly for preview, then you can use [Open in Colab][colab_addon], which is an addon in Chrome to open the notebook in Colab. Alternatively, you can go to [jupyter nbviewer][nbviewer], and paste the link to the notebook for previewing. When working with exercises it is important that you create your own notebooks (.ipynb) or script files (.py).

[nbviewer]: https://nbviewer.jupyter.org/
[colab_addon]: https://chrome.google.com/webstore/detail/open-in-colab/iogfkhleblhcpcekbiedikdehleodpjo?hl=sv

When installing softwares, unless anything else is stated below, just click next.

<details open>

<summary id = "week1"><b>Week 42</b></summary>

Setup :wrench:

1. Create a new folder for this course 
2. Create a new pipenvironment with 
   ```python 
   pipenv shell
   ```  
3. Install **numpy**, **pandas**, **matplotlib** and **seaborn** in this pipenv: 
   ```python 
   pipenv install numpy 
   pipenv install pandas
   pipenv install matplotlib
   pipenv install seaborn
   ``` 

Video guides :video_camera:

- [pipenv video - introduction][pipenv_vid]
- [pandas video - loading data][pandas_vid_load_data]
- [pandas video - DataFrame and Series][pandas_vid_df]
- [pandas video - indexes][pandas_vid_index]
- [pandas video - missing data][pandas_vid_nan]



[pipenv_vid]: https://www.youtube.com/watch?v=6Qmnh5C4Pmo
[pandas_vid_load_data]: https://www.youtube.com/watch?v=ZyhVh-qRZPA&t=450s
[pandas_vid_df]: https://www.youtube.com/watch?v=zmdjNSmRXF4
[pandas_vid_index]: https://www.youtube.com/watch?v=W9XjRYFkkyw&list=RDCMUCCezIgC97PvUuR4_gbFUs5g&index=3
[pandas_vid_nan]: https://www.youtube.com/watch?v=KdmPHEnPJPs&list=RDCMUCCezIgC97PvUuR4_gbFUs5g&index=9


Theory :book:

Exercises :running:

</details>

[if_else]: https://www.youtube.com/watch?v=AWek49wXGzI&t=155s

<details open>

<summary id = "week2"><b >Week 43</b></summary>

Setup :wrench:

Video guides :video_camera:
- [pandas video - filtering][pandas_vid_filter]
- [pandas video - update rows and columns][pandas_vid_update_rows]
- [pandas video - sorting][pandas_vid_sort]
- [pandas video - grouping and aggregating data][pandas_vid_group]

[pandas_vid_filter]: https://www.youtube.com/watch?v=Lw2rlcxScZY&list=RDCMUCCezIgC97PvUuR4_gbFUs5g&index=4
[pandas_vid_update_rows]: https://www.youtube.com/watch?v=DCDe29sIKcE&list=RDCMUCCezIgC97PvUuR4_gbFUs5g&index=5
[pandas_vid_sort]: https://www.youtube.com/watch?v=T11QYVfZoD0&list=RDCMUCCezIgC97PvUuR4_gbFUs5g&index=7
[pandas_vid_group]: https://www.youtube.com/watch?v=txMdrV1Ut64&list=RDCMUCCezIgC97PvUuR4_gbFUs5g&index=8

Theory :book:

Exercises :running:

</details>

<details open>

<summary id = "week3"><b >Week 44</b></summary>

Setup :wrench:

Video guides :video_camera:

- [pandas video - dates and time series][pandas_vid_dates]
- [pandas video - data formats][pandas_vid_formats]

[pandas_vid_dates]: https://www.youtube.com/watch?v=UFuo7EHI8zc&list=RDCMUCCezIgC97PvUuR4_gbFUs5g&index=10
[pandas_vid_formats]: https://www.youtube.com/watch?v=N6hyN6BW6ao&list=RDCMUCCezIgC97PvUuR4_gbFUs5g&index=11

Theory :book:

Exercises :running:

</details>

<details open>

<summary id = "week4"><b >Week 45</b></summary>

Video guides :video_camera:

Theory :book:
[PCA - Principal Components Analysis][pca_example]

[pca_example]: https://towardsdatascience.com/principal-component-analysis-pca-79d228eb9d24

Exercises :running:

</details>

<details open>

<summary id = "week5"><b >Week 46</b></summary>

Setup :wrench:

Video guides :video_camera:

Theory :book:

Exercises :running:

</details>
