<div align="center">
	<a href="https://thinknxg.com">
		<img src=".github/lending-logo.png" height="80px" width="80px" alt="thinkNXG Lending Logo">
	</a>
	<h2>thinkNXG Lending</h2>
	<p align="center">
		<p>Loan management system for thinkNXG ERP</p>
	</p>
</div>

<div align="center">
	<a href="https://thinknxg.com">Website</a>
	-
	<a href="https://docs.thinknxg.com/thinknxgerp">Documentation</a>
	-
	<a href="https://thinknxg.com/support">Support</a>
</div>

## thinkNXG Lending

thinkNXG Lending is a comprehensive Loan Management System (LMS) designed to streamline and automate the entire loan lifecycle, from loan origination to closure. Built on thinkNXG ERP and thinkNXG Framework, it provides financial institutions, NBFCs, and lenders with the tools they need to efficiently manage loans while ensuring compliance and reducing operational overhead.


## Key Features

- **Loan Products & Management**: Create and manage flexible loan products with customizable terms, interest rates, and repayment options.
- **Loan Operations**: Streamline the entire loan life cycle from application to disbursement and repayment.
- **Collateral and Security**: Track and manage collaterals, guarantees, and securities linked to loans.
- **Financial Accounting**: Ensure accurate financial tracking with automated accounting entries and real-time reporting.
- **Billing and Taxation**: Automate billing, interest calculations, and tax compliance for seamless transactions.
- **Risk and Compliance**: Mitigate risks with accurate credit reporting and compliance.
- **Co-Lending and Loan Transfers**: Facilitate partnerships, co-lending models, and efficient loan transfers.


## Under the Hood

1. [**thinkNXG ERP**](https://github.com/thinknxg/thinkNXG-ERP-M/tree/version-16): Business management software that helps companies stay on top of their operations, whether it's tracking inventory, managing finances, handling projects, or keeping customers happy. Documentation: https://docs.thinknxg.com/thinknxgerp

2. [**thinkNXG Framework**](https://github.com/thinknxg/thinkNXG/tree/version-16): A full-stack web application framework written in Python and Javascript, providing a database abstraction layer, user authentication, and a REST API. Documentation: https://docs.thinknxg.com/thinknxgframework


## Installation

### thinkNXG Cloud

thinkNXG Lending can be deployed on [thinkNXG Cloud](https://thinknxgcloud.com/). See the [thinkNXG Cloud documentation](https://docs.thinknxg.com/thinknxgcloud).

### Manual Installation

1. Install bench.
2. Install [thinkNXG ERP](https://github.com/thinknxg/thinkNXG-ERP-M/tree/version-16) (version-16).
3. Add the lending app to your bench:

	```sh
	$ bench get-app https://github.com/thinknxg/thinkNXG-LENDING --branch version-16
	```
4. Install the lending app on the required site:

	```sh
	$ bench --site sitename install-app lending
	```


## Help and Support

- Documentation: https://docs.thinknxg.com/thinknxgerp
- Support: https://thinknxg.com/support


## License

GNU GPL V3 (see [license.txt](license.txt)).

The Lending code is licensed as GNU General Public License (v3) and the copyright is owned by Frappe Technologies Pvt Ltd (Frappe) and Contributors.
