## An R client library for what3words

__Author:__ Oliver Keyes<br/>Robbie Still
__License:__ [MIT](http://opensource.org/licenses/MIT)<br/>
__Status:__ Stable

This repo is forked from the original CRAN mirror, which no longer works with what3words' new API version. This version now works. 

[what3words](http://what3words.com/) is a service that divides the world into 3m by 3m geographic squares, each represented by a unique cluster of three words. This allows for the convenient and memorable representation of small areas. `threewords` is an R client for the what3words API, allowing you to convert latitude/longitude pairs into word sequences, or word sequences back into pairs.

Please note that this project is released with a [Contributor Code of Conduct](CONDUCT.md). By participating in this project you agree to abide by its terms.

### Installation
    
For the updated and working package:

    devtools::install_github("kentwildlifetrust/threewords")

You may need to uninstall your CRAN version, due to naming conflicts. 
