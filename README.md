# Test262 Report - Issue Tracker

[Test262 Report](https://test262.report/) is developed and mantained by [Bocoup](https://bocoup.com/). It provides JavaScript developers with up-to-date information on the state of new and existing language features across implementations. Test262 Report checks for changes to [Test262](https://github.com/tc39/test262), the [ECMA-262 (“ECMAScript” or “JavaScript”)](https://tc39.github.io/ecma262/) test suite, and each engine every day. If Test262 changes, all engines are rerun through the new version of Test262. If one engine changes, only that engine is run through test262. If no engines change and Test262 does not change, no new runs are made.

We run Test262 test material via [Test262-harness](https://github.com/bterlson/test262-harness), which itself uses [eshost](https://github.com/bterlson/eshost) to normalize host runtime environment disparities. We use [jsvu](https://github.com/GoogleChromeLabs/jsvu) to install the latest engine binaries.

This repository is used as a public issue tracker to report bugs and feature requests for the report itself. Thank you for taking the time to visit this issue tracker and share your feedback. We really appreciate it! Before submitting a new issue to document a bug or request a feature, take a look over the open and closed issues in the [issue tracker](https://github.com/bocoup/test262-report-issue-tracker/issues), and see if there is an existing thread to contribute to. If not please [open a new issue](https://github.com/bocoup/test262-report-issue-tracker/issues/new) and follow the guidelines in our template. Thanks again :)!

### Further Reading

You can read more about this project on the [project about page](https://test262.report/about) or in our [Test262 Report announcement](https://bocoup.com/blog/announcing-test262-report) on the Bocoup Blog. 

### Licensing and Contact
The source code for the tools used to run Test262 test material across multiple engines is publicly available, free to use, and maintained by the Bocoup team. The systems for orchestrating these tools in CI for daily runs, the data produced by this system, and the Test262 Report website are internal to Bocoup. If you would like to incorporate the confromance data that we collect, or use these systems in some other way, please email [reports@bocoup.com](mailto:reports@bocoup.com).


### Code of Conduct

This project uses the [Bocoup Code of Conduct](https://bocoup.com/code-of-conduct). Please report behavior that violates the code of conduct directly to [hr@bocoup.com](mailto:hr@bocoup.com).
