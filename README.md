[![Build Status](https://app.travis-ci.com/brain-score/language.svg?token=vqt7d2yhhpLGwHsiTZvT&branch=main)](https://app.travis-ci.com/brain-score/language)
[![Documentation Status](https://readthedocs.org/projects/brain-score_language/badge/?version=latest)](https://brain-score_language.readthedocs.io/en/latest/?badge=latest)
[![Website Status](https://img.shields.io/website.svg?down_color=red&down_message=offline&up_message=online&url=http%3A%2F%2Fbrain-score.org/language)](https://brain-score.org/language)

Brain-Score Language is a platform to evaluate computational models of language on their match to behavioral and neural
measurements in the domain of language processing. The intent of Brain-Score is to adopt many (ideally all) the
experimental benchmarks in the field for the purpose of model testing, falsification, and comparison. To that end,
Brain-Score operationalizes experimental data into quantitative benchmarks that any model candidate following
the `BrainModel` interface can be scored on.

See the [Documentation](https://brain-score_language.readthedocs.io) for more details.

Brain-Score is made by and for the community. To contribute,
please [send in a pull request](https://github.com/brain-score/language/pulls).

## Alpha status
This repository is under active development, and should be considered to be in an alpha status.
Code is likely to change substantially, without backwards compatibility.
Please let us know of any problems by [creating an issue](https://github.com/brain-score/language/issues/new).

## Usage

Score an existing model on an existing benchmark:

```bash
python brainscore_language score --model_identifier='distilgpt2' --benchmark_identifier='Futrell2018-pearsonr'
```

## License

MIT license
