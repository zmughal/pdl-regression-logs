Run the following in the regression VM

```shell
cd /vagrant
# ./download-pdl-from-backpan && ./install-pdl
git clone --branch=sf390 git://github.com/PDLPorters/pdl.git
./gather-test-result pdl/t/badvalue_scalar_cmp.t
```
