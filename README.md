# Madonnas and Miracles

[![DOI](https://zenodo.org/badge/405213416.svg)](https://zenodo.org/badge/latestdoi/405213416)

This repository holds the content from the 2017 Madonnas and Miracles exhibition
held at the Fitzwilliam Museum and curated by Vicky Avery and Mary Laven.

Content was extracted from static, code bound pages to a simple jekyll instance and is deployed to Github pages. A data.json file is used to create an indexed content link to the main website's Solr instance, which allows content to be reused. 

## To run locally

* Install Jekyll on your machine following these [instructions](https://jekyllrb.com/docs/installation/)
* Install Git on your machine following these [instructions](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
* Clone the code for this repository:
   `git clone https://github.com/FitzwilliamMuseum/fitz-madonnas-and-miracles.git reponame`
* Install the gems
   `bundle install`
* Change to the directory and then run this command in terminal `bundle exec jekyll serve`


## Credits

Code by [@portableant](https://github.com/portableant)

## License

GPL V3 for code, CC-BY-NC-SA-ND for content (text and images) unless stated otherwise.

## Contributing guidelines

If you want to contribute fixes to this site, you are very welcome to do so. To do this, either add a [bug report under issues](https://github.com/FitzwilliamMuseum/fitz-madonnas-and-miracles/issues) or fork the repository and create a new branch for proposed fixes and then submit a pull request.
