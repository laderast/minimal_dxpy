
# minimal_dxpy

<!-- badges: start -->
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/laderast/minimal_dxpy/HEAD?urlpath=lab)
<!-- badges: end -->

The goal of minimal_dxpy is to provide a minimal shell that has the dx-toolkit installed for those who cannot install it on their own machines. It also contains the following software:

- `git`
- `nano`
- `jq`
- `python`
- `pip`
- `dxpy` - the dx-toolkit for DNAnexus.

Launch the shell here: https://mybinder.org/v2/gh/laderast/minimal_dxpy/HEAD?urlpath=lab and open Terminal in the Launcher to get started. 

## Limitations

Note that this is running a shell off the mybinder servers. As such, it is made to try out the dx-toolkit commands, not as a permanent workspace.

Anything you generate on the mybinder server is ephemeral. So please transfer any files you want to keep into your DNAnexus project with `dx upload`.