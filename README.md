<!--
  -- Copyright (c) 2019, Arm Limited, All Rights Reserved
  -- SPDX-License-Identifier: Apache-2.0
  --
  -- Licensed under the Apache License, Version 2.0 (the "License"); you may
  -- not use this file except in compliance with the License.
  -- You may obtain a copy of the License at
  --
  -- http://www.apache.org/licenses/LICENSE-2.0
  --
  -- Unless required by applicable law or agreed to in writing, software
  -- distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
  -- WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
  -- See the License for the specific language governing permissions and
  -- limitations under the License.
--->

# TSS 2.0 Enhanced System API Rust Wrapper 

[![CI tests](https://github.com/parallaxsecond/rust-tss-esapi/workflows/Continuous%20Integration/badge.svg)](https://github.com/parallaxsecond/rust-tss-esapi/actions?query=workflow%3A%22Continuous+Integration%22)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

The `tss-esapi` Rust crate provides an idiomatic interface to the TCG TSS 2.0 Enhanced System API. We expose both direct FFI bindings and abstracted versions, aimed at improved convenience of using the API.

## Disclaimer

The current version of the API does not offer any security or code safety guarantees.
The implementation that is provided is suitable for exploratory testing and experimentation only.
This test implementation does not offer any tangible security benefits and therefore is not
suitable for use in production. Documentation pages may be incomplete and are subject to change
without notice. Interfaces may change in such a way as to break compatibility with client code.
Contributions from the developer community are welcome. Please refer to the contribution guidelines.

## Community channel

Come and talk to us in [our Slack channel](https://app.slack.com/client/T0JK1PCN6/CPMQ9D4H1)!
[Here](http://dockr.ly/slack) is how to join the workspace.

## Contributing

We would be happy for you to contribute to the `tss-esapi` crate! Check the [**Contributing**](CONTRIBUTING.md)
file to know more about the contribution process.
Check the [open issues](https://github.com/orgs/parallaxsecond/projects/1) on the board if you
need any ideas 🙂!

## License

The software is provided under Apache-2.0. Contributions to this project are accepted under the same license.

This project uses the following third party crates:
* serde (MIT and Apache-2.0)
* bindgen (BSD-3-Clause)
* log (MIT and Apache-2.0)
* env\_logger (MIT and Apache-2.0)
* mbox (MIT)
* bitfield (MIT and Apache-2.0)
