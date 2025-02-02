# Accessible pygments themes

[![conda version](https://img.shields.io/conda/vn/conda-forge/accessible-pygments?color=e27e8c&style=for-the-badge)](https://anaconda.org/conda-forge/accessible-pygments)
[![pip version](https://img.shields.io/pypi/v/accessible-pygments?color=63a6c8&style=for-the-badge)](https://pypi.org/project/accessible-pygments/)
[![conda-forge downloads](https://img.shields.io/conda/dn/conda-forge/accessible-pygments?label=conda-forge%20downloads&style=for-the-badge)](https://anaconda.org/conda-forge/accessible-pygments)
[![pip downloads](https://img.shields.io/pypi/dm/accessible-pygments?color=%23acc00d&label=PyPI%20downloads&style=for-the-badge)](https://pypi.org/project/accessible-pygments/)
[![demo](https://img.shields.io/badge/Demo-Click%20me!-blueviolet?style=for-the-badge)](https://quansight-labs.github.io/accessible-pygments/)

This package includes a collection of accessible themes for pygments based on different sources.

![Screenshot of all light themes side by side](./docs/light_themes.png)

![Screenshot of all dark themes side by side](./docs/dark_themes.png)

## WCAG 2.1 - AAA compliant

The following themes are AAA compliant with [WCAG 2.1 criteria for color contrast](https://www.w3.org/TR/UNDERSTANDING-WCAG20/visual-audio-contrast-contrast.html).

- [`a11y-dark`](https://github.com/Quansight-Labs/accessible-pygments/tree/main/a11y_pygments/a11y_dark)
- [`a11y-high-contrast-dark`](https://github.com/Quansight-Labs/accessible-pygments/tree/main/a11y_pygments/a11y_high_contrast_dark)
- [`pitaya-smoothie`](https://github.com/Quansight-Labs/accessible-pygments/tree/main/a11y_pygments/pitaya_smoothie) - Colorblindness friendly.
- [`github-light`](https://github.com/Quansight-Labs/accessible-pygments/tree/main/a11y_pygments/github_light) - Colorblindness friendly.
- [`github-dark`](https://github.com/Quansight-Labs/accessible-pygments/tree/main/a11y_pygments/github_dark) - Colorblindness friendly.
- [`github-light-colorblind`](https://github.com/Quansight-Labs/accessible-pygments/tree/main/a11y_pygments/github_light_colorblind) - Colorblindness friendly.
- [`github-dark-colorblind`](https://github.com/Quansight-Labs/accessible-pygments/tree/main/a11y_pygments/github_dark_colorblind) - Colorblindness friendly.
- [`github-light-high-contrast`](https://github.com/Quansight-Labs/accessible-pygments/tree/main/a11y_pygments/github_light_high_contrast) - Colorblindness friendly.
- [`github-dark-high-contrast`](https://github.com/Quansight-Labs/accessible-pygments/tree/main/a11y_pygments/github_dark_high_contrast) - Colorblindness friendly.
- [`gotthard-dark`](https://github.com/Quansight-Labs/accessible-pygments/tree/main/a11y_pygments/gotthard-dark) - Colorblindness friendly.

## WCAG 2.1 - AA compliant

The following themes are AA compliant with [WCAG 2.1 criteria for color contrast](https://www.w3.org/TR/UNDERSTANDING-WCAG20/visual-audio-contrast-contrast.html).

- [`a11y-light`](https://github.com/Quansight-Labs/accessible-pygments/tree/main/a11y_pygments/a11y_light)
- [`a11y-high-contrast-light`](https://github.com/Quansight-Labs/accessible-pygments/tree/main/a11y_pygments/a11y_high_contrast_light)
- [`gotthard-light`](https://github.com/Quansight-Labs/accessible-pygments/tree/main/a11y_pygments/gotthard-light) - Colorblindness friendly.
- [`blinds-light`](https://github.com/Quansight-Labs/accessible-pygments/tree/main/a11y_pygments/blinds-light) - Colorblindness friendly.
- [`blinds-dark`](https://github.com/Quansight-Labs/accessible-pygments/tree/main/a11y_pygments/blinds-dark) - Colorblindness friendly.
- [`greative`](https://github.com/Quansight-Labs/accessible-pygments/tree/main/a11y_pygments/greative) - Accessible to most forms of colorblindness and low light settings.

For a demo of all our themes please [click here!](https://quansight-labs.github.io/accessible-pygments/)

## Installation

Our package is available in both conda and pip via,

```
conda install -c conda-forge accessible-pygments
```

```
pip install accessible-pygments
```

If you want to install it directly from source,

```
git clone git@github.com:Quansight-Labs/accessible-pygments.git
cd accessible-pygments
pip install .
```

## Usage

Import it using the name identifier for the desired theme,

```
from pygments.formatters import HtmlFormatter
HtmlFormatter(style='a11y-light').style
<class 'accessible-pygments.A11yLight'>
```

## Tests

Just open a terminal and run,

```
python test/run_tests.py
```

You will see the results under `test/results` in html format for each supported theme.


## Acknowledgements

We want to thank the following sources for being the source of inspiration of one or more themes that are available in this repository,

- [a11y dark and light syntax highlighting](https://github.com/ericwbailey/a11y-syntax-highlighting).
- [pitaya smoothie vscode theme](https://github.com/trallard/pitaya_smoothie).
- [github vscode themes](https://github.com/primer/github-vscode-theme).
- [gotthard vscode themes](https://github.com/janbiasi/vscode-gotthard-theme/).
- [blinds vscode themes](https://github.com/orbulant/blinds-theme).
- [greative vscode theme](https://github.com/SumanKhdka/Greative-VSCode-Theme).
