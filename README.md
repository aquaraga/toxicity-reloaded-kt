# Toxicity reloaded - Kotlin

This tool is to analyze [toxicity][1] of Kotlin code-bases.
The [original tool][3] used [checkstyle][2] results to come up with file-wise toxicity, this version uses [detekt][4]

## Usage

* [Integrate detekt][6] to your Kotlin code-base, by using the detekt-config.yml in this repo as the config file 
* Generate detekt.xml report by running the detekt task
* Open **toxicity.html**
* Load **detekt.xml** generated by detekt


[1]: http://erik.doernenburg.com/2008/11/how-toxic-is-your-code/
[2]: https://github.com/checkstyle/checkstyle
[3]: https://github.com/softvis/toxicity-reloaded
[4]: https://arturbosch.github.io/detekt/