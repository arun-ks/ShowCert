# ShowCert
The URL link for Training Certificates are very long & look unsightly in resumes.

This is a simple to reuseable page which uses a JSON array to store the URL Link of the certificate, its Description & an internal _Redirection Code_ for certificates.

When the page is opened with a command line parameter, it will search through the JSON array for matching _"Redirection Code"_, find the corresponding URL Link & redirect to it.

In case the command line parameter is wrong or missing, the page will show the [full list of Certificate Description with URL Links as a table](https://arun-ks.github.io/ShowCert/)

### Delete ME
#### sample URL & Live page
- [Certificate X - goes to CNN](https://arun-ks.github.io/ShowCert/?certName=BBC)

- [Link with bad code](https://arun-ks.github.io/ShowCert/?certName=404Code)

