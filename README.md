# ShowCert
The URL link for Training Certificates are very long & look unsightly in resumes.

This is a simple to reuse pagw which uses a JSON array to store URL Link, Description & Code for certificates.

When the page is opened with a command line parameter, it will search through the JSON array for matching "Code", find the corresponding URL Link & redirect to it.
In case the command line parameter is not found, the page will show the fill list of Certificate Description with URL Links as a table 


### Delete ME
#### sample URL & Live page
- [Certificate X - goes to CNN](https://arun-ks.github.io/ShowCert/?certName=Cnn)

- [Certificate Y - goes to Google](https://arun-ks.github.io/ShowCert/?certName=Google)

- [Link with bad code](https://arun-ks.github.io/ShowCert/?certName=404Code)

