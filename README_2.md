# LCS_Practice

Here I am building a Latent Change Score model utilizing the approach described by Kievit et al (2018) (https://doi.org/10.1016/j.dcn.2017.11.007).
The model expands on the framework of their "Bivariate Latent Change Score" model (~ p. 108) in lavaan, but includes looks at five factors rather than just two. 
Issues that I've encountered thus far relate to translation of findings, missing data management, and tests of non-normality. 
  The R MVN package (seems) to only work with complete cases, so I utilized the MissMech package to assess for what type of missing data were present
  and utilize the Anderson-Darling test to determine the levels of multivariate non-normality of the data as this package can obtain the desired tests
  with missing data. 
