<h1 align="center">
  <a href="https://github.com/ykimdeveloper/charts-great-streets-survey-ykimdeveloper">
    <!-- Please provide path to your logo here -->
    <img src="docs/images/logo.svg" alt="Logo" width="100" height="100">
  </a>
</h1>

<div align="center">
  Charts_Great_Streets_Survey_ykimdeveloper
  <br />
  <a href="#about"><strong>Explore the screenshots »</strong></a>
  <br />
  <br />
  <a href="https://github.com/ykimdeveloper/charts-great-streets-survey-ykimdeveloper/issues/new?assignees=&labels=bug&template=01_BUG_REPORT.md&title=bug%3A+">Report a Bug</a>
  ·
  <a href="https://github.com/ykimdeveloper/charts-great-streets-survey-ykimdeveloper/issues/new?assignees=&labels=enhancement&template=02_FEATURE_REQUEST.md&title=feat%3A+">Request a Feature</a>
  .
  <a href="https://github.com/ykimdeveloper/charts-great-streets-survey-ykimdeveloper/issues/new?assignees=&labels=question&template=04_SUPPORT_QUESTION.md&title=support%3A+">Ask a Question</a>
</div>

<div align="center">
<br />

[![Project license](https://img.shields.io/github/license/ykimdeveloper/charts-great-streets-survey-ykimdeveloper.svg?style=flat-square)](LICENSE)

[![Pull Requests welcome](https://img.shields.io/badge/PRs-welcome-ff69b4.svg?style=flat-square)](https://github.com/ykimdeveloper/charts-great-streets-survey-ykimdeveloper/issues?q=is%3Aissue+is%3Aopen+label%3A%22help+wanted%22)
[![code with love by ykimdeveloper](https://img.shields.io/badge/%3C%2F%3E%20with%20%E2%99%A5%20by-ykimdeveloper-ff1414.svg?style=flat-square)](https://github.com/ykimdeveloper)

</div>

<details open="open">
<summary>Table of Contents</summary>

- [About](#about)
  - [Built With](#built-with)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Roadmap](#roadmap)
- [Support](#support)
- [Project assistance](#project-assistance)
- [Contributing](#contributing)
- [Authors & contributors](#authors--contributors)
- [Security](#security)
- [License](#license)
- [Acknowledgements](#acknowledgements)

</details>

---

## About

This is a continuation of the data analysis project using L.A. city's data 'Great Streets Pedestrian Survey 2015'.  
The data shown is already data wrangled and cleaned which is described on my other repo.
This project is to demonstrate how to use charts to unnderstand the data better.

<details>
<summary>Screenshots</summary>
<br>



|                              421 Pedestrian Bar Graph                          |   421 Pedestrian  Pie Graph Page                               |
| :-------------------------------------------------------------------: | :--------------------------------------------------------------------: |
| <img src="docs/images/bar-graph.png" title="Home Page" width="100%"> | <img src="docs/images/pie-graphy.png" title="Login Page" width="100%"> |

</details>

### Built With

* Plotly - a python browser-based graphing library

## Getting Started

### Prerequisites

* pip install plotly

### Installation

* Easier to use pandas and numpy to manipulate data for charts.

## Usage

```python
import plotly.express as px
pie_fig = px.pie(...)

pie_fig.update_layout(...)


```
Creating Chart extracted from a single string question from column 2
```python
chart_data = df.loc[:, new_cols].sum()
chart_data_df = pd.DataFrame({"Pedestrians": chart_data})
chart_data_sorted_df = pd.DataFrame()
chart_data_sorted_df = chart_data_df.sort_values(by=['Pedestrians'])
chart_data_sorted_df
```


## Roadmap

See the [open issues](https://github.com/ykimdeveloper/charts-great-streets-survey-ykimdeveloper/issues) for a list of proposed features (and known issues).

- [Top Feature Requests](https://github.com/ykimdeveloper/charts-great-streets-survey-ykimdeveloper/issues?q=label%3Aenhancement+is%3Aopen+sort%3Areactions-%2B1-desc) (Add your votes using the 👍 reaction)
- [Top Bugs](https://github.com/ykimdeveloper/charts-great-streets-survey-ykimdeveloper/issues?q=is%3Aissue+is%3Aopen+label%3Abug+sort%3Areactions-%2B1-desc) (Add your votes using the 👍 reaction)
- [Newest Bugs](https://github.com/ykimdeveloper/charts-great-streets-survey-ykimdeveloper/issues?q=is%3Aopen+is%3Aissue+label%3Abug)

## Support

* ykimdeveloper - message me for any questions

Reach out to the maintainer at one of the following places:

- [GitHub issues](https://github.com/ykimdeveloper/charts-great-streets-survey-ykimdeveloper/issues/new?assignees=&labels=question&template=04_SUPPORT_QUESTION.md&title=support%3A+)
- Contact options listed on [this GitHub profile](https://github.com/ykimdeveloper)

## Project assistance

If you want to say **thank you** or/and support active development of Charts_Great_Streets_Survey_ykimdeveloper:

- Add a [GitHub Star](https://github.com/ykimdeveloper/charts-great-streets-survey-ykimdeveloper) to the project.
- Tweet about the Charts_Great_Streets_Survey_ykimdeveloper.
- Write interesting articles about the project on [Dev.to](https://dev.to/), [Medium](https://medium.com/) or your personal blog.

Together, we can make Charts_Great_Streets_Survey_ykimdeveloper **better**!

## Contributing

First off, thanks for taking the time to contribute! Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make will benefit everybody else and are **greatly appreciated**.


Please read [our contribution guidelines](docs/CONTRIBUTING.md), and thank you for being involved!

## Authors & contributors

The original setup of this repository is by [Alexey Potapov](https://github.com/ykimdeveloper).

For a full list of all authors and contributors, see [the contributors page](https://github.com/ykimdeveloper/charts-great-streets-survey-ykimdeveloper/contributors).

## Security

Charts_Great_Streets_Survey_ykimdeveloper follows good practices of security, but 100% security cannot be assured.
Charts_Great_Streets_Survey_ykimdeveloper is provided **"as is"** without any **warranty**. Use at your own risk.

_For more information and to report security issues, please refer to our [security documentation](docs/SECURITY.md)._

## License

This project is licensed under the **MIT license**.

See [LICENSE](LICENSE) for more information.
