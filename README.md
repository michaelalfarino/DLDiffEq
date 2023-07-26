# Studi Pemecahan Persamaan Difusi Menggunakan Metode Deep Learning

![Python](https://img.shields.io/badge/Python-black?logo=python)
![TensorFlow](https://img.shields.io/badge/TensorFlow-black?logo=tensorflow)
![scikit-learn](https://img.shields.io/badge/scikit--learn-black?logo=scikitlearn)
![pandas](https://img.shields.io/badge/pandas-black?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-black?logo=numpy)
![Matplotlib](https://img.shields.io/badge/matplotlib-black?logo=data:image/svg%2bxml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iVVRGLTgiPz4KPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxMjgiIGhlaWdodD0iMTI4IiBzdHJva2U9IiM3NzciIGZpbGwtb3BhY2l0eT0iLjgiPgo8cGF0aCBmaWxsPSIjRkZGIiBkPSJtNjMsMWE2Myw2MyAwIDEsMCAyLDB6bTAsMTRhNDksNDkgMCAxLDAgMiwwem0wLDE0YTM1LDM1IDAgMSwwCjIsMHptMCwxNGEyMSwyMSAwIDEsMCAyLDB6bTAsMTRhNyw3IDAgMSwwIDIsMHptNjQsN0gxbTEwOC00NS05MCw5MG05MCwwLTkwLTkwbTQ1LTE4djEyNiIvPgo8cGF0aCBmaWxsPSIjRjYwIiBkPSJtNTAsOC0yMCwxMCA2OCw5MiAxMC0xMEw2NCw2NHoiLz4KPHBhdGggZmlsbD0iI0ZDMCIgZD0ibTE3LDUwdjI4TDY0LDY0eiIvPgo8cGF0aCBmaWxsPSIjN0Y3IiBkPSJtNjQsNjQgNiwzNUg1OHoiLz4KPHBhdGggZmlsbD0iI0NGMyIgZD0ibTY0LDY0IDEzLTQwIDksNXoiLz4KPHBhdGggZmlsbD0iIzA0RiIgZD0ibTY0LDY0IDE0LTYgMSw0emwtMjYsMTMgMyw0eiIvPgo8L3N2Zz4=)

Proyek ini bertujuan untuk menyelesaikan persamaan difusi menggunakan *Deep Neural Network* (DNN) dengan *training data* yang diperoleh dari metode numerik beda hingga dengan skema FTCS. Hasil dari DNN beserta hasil metode numerik kemudian akan dibandingkan dengan solusi analitik.

Kesimpulan yang diperoleh adalah dalam penyelesaian persamaan diferensial, hasil dari DNN hanya bisa mencapai sebaik metode yang digunakan untuk pendekatan data *training* nya (dalam kasus ini metode beda hingga dengan skema FTCS). Kedua metode sama-sama mencapai *mean-squared error* yang bernilai pada orde $10^{-5}$.

- [File PDF lengkap](https://github.com/michaelalfarino/DLDiffEq/blob/main/Studi%20Pemecahan%20Persamaan%20Difusi%20Menggunakan%20Metode%20Deep%20Learning.pdf)

- Code :
  * [Deep learning](https://github.com/michaelalfarino/DLDiffEq/blob/main/Deep_Learning_to_Simulate_the_Diffusion_Equation.ipynb)
  * [Diffusion data generation using FDM with FTCS scheme](https://github.com/michaelalfarino/DLDiffEq/blob/main/Diffusion_data_generation_using_FDM_with_FTCS_scheme.ipynb)
