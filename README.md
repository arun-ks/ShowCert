# Redirection to Links for Certificates

The URL link for online Training Certificates are very long & look unsightly in resumes.

This is a simple to reuseable page which uses a JSON array to store the URL Link of the certificate, its description & an internal _Redirection short-name_ for certificates.

When the page is opened with a command line parameter("id"), it will search through the JSON array for matching _"Redirection short-name"_, find the corresponding URL Link & redirect to it.

In case the command line parameter is wrong or missing, the page will show the full list of Certificate Description with URL Links as a table.

Access the [Live version here](https://arun-ks.github.io/cert/)

<details>
  <summary>To Do Items</summary>
  
- [ ] Update default page to show resume or linkedIn page
- [ ] Find way to log access attempts
- [ ] Create category-based sections within the table
- [ ] Allow filtering/search on the table.
</details>
