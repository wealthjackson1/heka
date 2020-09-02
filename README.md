你好！
很冒昧用这样的方式来和你沟通，如有打扰请忽略我的提交哈。我是光年实验室（gnlab.com）的HR，在招Golang开发工程师，我们是一个技术型团队，技术氛围非常好。全职和兼职都可以，不过最好是全职，工作地点杭州。
我们公司是做流量增长的，Golang负责开发SAAS平台的应用，我们做的很多应用是全新的，工作非常有挑战也很有意思，是国内很多大厂的顾问。
如果有兴趣的话加我微信：13515810775  ，也可以访问 https://gnlab.com/，联系客服转发给HR。
# Heka

Data Acquisition and Processing Made Easy

Heka is a tool for collecting and collating data from a number of different
sources, performing "in-flight" processing of collected data, and delivering
the results to any number of destinations for further analysis.

Heka is written in [Go](http://golang.org/), but Heka plugins can be written
in either Go or [Lua](http://lua.org). The easiest way to compile Heka is by
sourcing (see below) the build script in the root directory of the project,
which will set up a Go environment, verify the prerequisites, and install all
required dependencies. The build process also provides a mechanism for easily
integrating external plug-in packages into the generated `hekad`. For more
details and additional installation options see
[Installing](https://hekad.readthedocs.org/en/latest/installing.html).

WARNING: YOU MUST *SOURCE* THE BUILD SCRIPT (i.e. `source build.sh`) TO
         BUILD HEKA. Setting up the Go build environment requires changes to
         the shell environment, if you simply execute the script (i.e.
         `./build.sh`) these changes will not be made.
         
Resources:
* Heka project docs: http://hekad.readthedocs.org/
* GoDoc package docs: http://godoc.org/github.com/mozilla-services/heka
* Mailing list: https://mail.mozilla.org/listinfo/heka
* IRC: #heka on irc.mozilla.org
