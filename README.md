# cdQA-annotator

Fork of [cdqa-suite's cdQA-annotator](https://github.com/cdqa-suite/cdQA-annotator) with added support for SQuAD 2.0 datasets with `is_impossible` flag and missing `text` field support.

![GitHub](https://img.shields.io/github/license/cdqa-suite/cdQA-annotator.svg)

A web-based annotator for closed-domain question answering datasets with SQuAD format

![](https://cdqa-suite.github.io/cdQA-website/img/suite-3.5c84e524.png)

Clone the repository:

```shell
git clone https://github.com/vbankov/cdQA-annotator
```

Install dependencies

```shell
cd cdQA-annotator
npm install
```

Start development server

```shell
npm run serve
```

The app should be running at http://localhost:8080/