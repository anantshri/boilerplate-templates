# boilerplate-templates
Provides boilerplate vulnerability explanations and templates which can easily be used in real-world reports

## How to contribute

The **boilerplate-templates** `gh-pages` branch is essentially a [Jekyll](http://jekyllrb.com/) site.

For example, you want to add a new *template*: **Testing for SSI-Injection**

1. Clone the `gh-pages` branch: `git clone -b gh-pages https://github.com/owtf/boilerplate-templates.git` .
1. Make a new markdown file inside the `templates` directory, namely `ssi-injection.md`. See the examples given (`templates/<vuln>/index.md`) for how to write a template.
1. Once you added the template as `ssi-injection.md` inside the `templates/`, add a new entry in the `_data/vulns.yml` file. This essentially makes a new index for the vulnerability on the site.
For `ssi-injection` it would be: 

  ```
  - name: "SSI Injection"
    url: /templates/ssi-injection
    author: "<your name>"
  ```
1. All done, open a pull request!
