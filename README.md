Code Analyzer [![Build Status](https://secure.travis-ci.org/Srokap/code_review.png?branch=master)](https://travis-ci.org/Srokap/code_review) [![Scrutinizer Quality Score](https://scrutinizer-ci.com/g/Srokap/code_review/badges/quality-score.png?s=ce62b248cb98472b0405ad4bf3bd1f597cb7947f)](https://scrutinizer-ci.com/g/Srokap/code_review/) [![Code Coverage](https://scrutinizer-ci.com/g/Srokap/code_review/badges/coverage.png?s=1704d109e8647dd362dd4476bb21d6bfe890ba2f)](https://scrutinizer-ci.com/g/Srokap/code_review/) [![Code Climate](https://codeclimate.com/github/Srokap/code_review.png)](https://codeclimate.com/github/Srokap/code_review)
==================

Plugin for PHP code analysis and refactoring of [Elgg](http://elgg.org/) plugins.

Requirements
-------------

- At the moment this plugin supports PHP >=5.2, but expect it to change in future.
- This plugin uses [PHP Reflection API](http://php.net/manual/en/book.reflection.php) and even though it's listed
explicitly in plugin requirements, it's a module that's bundled with all usual PHP deployments. If you're not doing
anything fancy, no worries.

Bugtracker
-------------

Please report all issues with this plugin itself on it's
[project page on github](https://github.com/Srokap/code_review/issues).

With issues found in analyzed plugins you should contact plugin author directly and give him all the details from
analysis results.

Screenshots
-------------

![Analysis](screenshots/analysis.png)

![Deprecated list](screenshots/analysis.png)

![Code fixing](screenshots/analysis.png)
