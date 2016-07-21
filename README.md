# babel-preset-es2015-webpack-patch

This is a forked version of [`babel-preset-es2015-webpack`](https://github.com/gajus/babel-preset-es2015-webpack) used to solve package dependency issues when using npm 3+ or when also including [`babel-preset-es2015`](https://www.npmjs.com/package/babel-preset-es2015) as a dependency.

The issue typically manifests with the following error:
>"Cannot remove 'babel-plugin-transform-es2015-modules-commonjs' from the plugin list."

Please see the [original repository](https://github.com/gajus/babel-preset-es2015-webpack) for install instructions.

## Copyright
Copyright (c) 2016, Gajus Kuizinas

All rights reserved.

## Disclaimer

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
