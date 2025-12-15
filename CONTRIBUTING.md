# Contributing to Eval Factsheets
We want to make contributing to this project as easy and transparent as
possible.

## Pull Requests
We actively welcome your pull requests.

1. Fork the repo and create your branch from `main`.
2. If you've added code that should be tested, add tests.
3. If you've changed APIs, update the documentation.
4. Ensure the test suite passes.
5. Make sure your code lints.
6. If you haven't already, complete the Contributor License Agreement ("CLA").

## Contributor License Agreement ("CLA")
In order to accept your pull request, we need you to submit a CLA. You only need
to do this once to work on any of Meta's open source projects.

Complete your CLA here: <https://code.facebook.com/cla>

## Contributing a New Factsheet

This repository is an auxiliary tool for the [Every Eval Ever (EEE)](https://github.com/evaleval/every_eval_ever) project. To contribute a factsheet for an evaluation:

1.  Use the [Eval Factsheets tool](https://facebookresearch.github.io/EvalFactsheets) to generate your factsheet (preferably in JSON format).
2.  Navigate to the [Every Eval Ever](https://github.com/evaleval/every_eval_ever) repository.
3.  Find the folder corresponding to your evaluation in `data/{eval_name}/`.
4.  Add your generated factsheet file to that folder.
5.  Submit a Pull Request to the EEE repository.

## Issues
We use GitHub issues to track public bugs. Please ensure your description is
clear and has sufficient instructions to be able to reproduce the issue.

Meta has a [bounty program](https://bugbounty.meta.com/) for the safe
disclosure of security bugs. In those cases, please go through the process
outlined on that page and do not file a public issue.

## License
By contributing to Eval Factsheets, you agree that your contributions will be licensed
under the LICENSE file in the root directory of this source tree.
