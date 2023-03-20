
[![Runboat](https://img.shields.io/badge/runboat-Try%20me-875A7B.png)](https://runboat.odoo-community.org/builds?repo=OCA/pos&target_branch=12.0)
[![Pre-commit Status](https://github.com/OCA/pos/actions/workflows/pre-commit.yml/badge.svg?branch=12.0)](https://github.com/OCA/pos/actions/workflows/pre-commit.yml?query=branch%3A12.0)
[![Build Status](https://github.com/OCA/pos/actions/workflows/test.yml/badge.svg?branch=12.0)](https://github.com/OCA/pos/actions/workflows/test.yml?query=branch%3A12.0)
[![codecov](https://codecov.io/gh/OCA/pos/branch/12.0/graph/badge.svg)](https://codecov.io/gh/OCA/pos)
[![Translation Status](https://translation.odoo-community.org/widgets/pos-12-0/-/svg-badge.svg)](https://translation.odoo-community.org/engage/pos-12-0/?utm_source=widget)

<!-- /!\ do not modify above this line -->

# Point of Sale

This project aims to deal with Odoo modules related to the Point of Sale.

<!-- /!\ do not modify below this line -->

<!-- prettier-ignore-start -->

[//]: # (addons)

Available addons
----------------
addon | version | maintainers | summary
--- | --- | --- | ---
[pos_accented_search](pos_accented_search/) | 12.0.1.0.1 | [![fkawala](https://github.com/fkawala.png?size=30px)](https://github.com/fkawala) | Point of Sale - Product search works regardless of accented characters
[pos_access_right](pos_access_right/) | 12.0.1.0.2 |  | Point of Sale - Extra Access Right for certain actions
[pos_cache_user_restriction](pos_cache_user_restriction/) | 12.0.1.0.0 | [![GSLabIt](https://github.com/GSLabIt.png?size=30px)](https://github.com/GSLabIt) | Allow access to pos cache to restricted users
[pos_cash_control_multiple_config](pos_cash_control_multiple_config/) | 12.0.1.0.2 |  | Handle correctly opening balance in a multi point of sale context with Cash control enabled.
[pos_cash_move_reason](pos_cash_move_reason/) | 12.0.3.2.1 |  | POS cash in-out reason
[pos_cash_move_reason_multiple_control](pos_cash_move_reason_multiple_control/) | 12.0.3.1.1 | [![legalsylvain](https://github.com/legalsylvain.png?size=30px)](https://github.com/legalsylvain) | Glue module between pos_cash_move_reason and pos_multiple_control
[pos_check_session_state](pos_check_session_state/) | 12.0.1.0.0 |  | Check if the session state is still opened
[pos_customer_display](pos_customer_display/) | 12.0.1.1.2 |  | Manage LED Customer Display device from POS front end
[pos_customer_required](pos_customer_required/) | 12.0.1.0.1 |  | Point of Sale Require Customer
[pos_customer_required_fields](pos_customer_required_fields/) | 12.0.1.0.1 | [![petrus-v](https://github.com/petrus-v.png?size=30px)](https://github.com/petrus-v) | Define customer required field used in PoS order.
[pos_default_empty_image](pos_default_empty_image/) | 12.0.1.1.1 |  | Optimize loading time for products without image
[pos_default_partner](pos_default_partner/) | 12.0.1.0.1 |  | Add a default customer in pos order
[pos_disable_change_cashier](pos_disable_change_cashier/) | 12.0.1.0.1 |  | Disable the feature that allow to change cashier in the PoS
[pos_empty_home](pos_empty_home/) | 12.0.1.0.0 |  | Point of Sale - Hide products at the start of the Point of Sale
[pos_fix_search_limit](pos_fix_search_limit/) | 12.0.1.0.1 |  | Increase search in the PoS
[pos_fixed_discount](pos_fixed_discount/) | 12.0.1.0.2 | [![eLBati](https://github.com/eLBati.png?size=30px)](https://github.com/eLBati) | Allow to apply discounts with fixed amount
[pos_hide_banknote_button](pos_hide_banknote_button/) | 12.0.1.0.1 | [![legalsylvain](https://github.com/legalsylvain.png?size=30px)](https://github.com/legalsylvain) | Hide useless Banknote buttons in the PoS (+10, +20, +50)
[pos_hide_empty_category](pos_hide_empty_category/) | 12.0.1.0.2 | [![legalsylvain](https://github.com/legalsylvain.png?size=30px)](https://github.com/legalsylvain) | Hide PoS categories that doesn't have any products
[pos_hide_partner_info](pos_hide_partner_info/) | 12.0.2.0.1 |  | Hides phone and address field in pos customer list.
[pos_invoice_send_mail](pos_invoice_send_mail/) | 12.0.1.0.0 | [![ivantodorovich](https://github.com/ivantodorovich.png?size=30px)](https://github.com/ivantodorovich) | Send invoices by email from the POS
[pos_invoicing](pos_invoicing/) | 12.0.3.1.0 | [![legalsylvain](https://github.com/legalsylvain.png?size=30px)](https://github.com/legalsylvain) | Handle invoicing from Point Of Sale
[pos_journal_image](pos_journal_image/) | 12.0.1.0.2 | [![legalsylvain](https://github.com/legalsylvain.png?size=30px)](https://github.com/legalsylvain) | Add images on Account Journals available in the PoS
[pos_mail_receipt](pos_mail_receipt/) | 12.0.1.0.0 |  | Pos Mail Receipt
[pos_margin](pos_margin/) | 12.0.2.0.2 | [![legalsylvain](https://github.com/legalsylvain.png?size=30px)](https://github.com/legalsylvain) | Margin on PoS Order
[pos_margin_account_invoice_margin](pos_margin_account_invoice_margin/) | 12.0.1.0.1 | [![legalsylvain](https://github.com/legalsylvain.png?size=30px)](https://github.com/legalsylvain) | Margin on Account invoices generated by PoS
[pos_meal_voucher](pos_meal_voucher/) | 12.0.1.0.7 | [![legalsylvain](https://github.com/legalsylvain.png?size=30px)](https://github.com/legalsylvain) | Handle meal vouchers in Point of Sale with eligible amount and max amount
[pos_multi_ean](pos_multi_ean/) | 12.0.1.0.1 | [![eLBati](https://github.com/eLBati.png?size=30px)](https://github.com/eLBati) | Search products by multiple EAN
[pos_multiple_control](pos_multiple_control/) | 12.0.1.3.1 |  | Allow user to control each statement and add extra checks
[pos_order_count_store](pos_order_count_store/) | 12.0.1.0.0 |  | Store pos_order_count to improve reporting.
[pos_order_line_no_unlink](pos_order_line_no_unlink/) | 12.0.1.0.3 | [![legalsylvain](https://github.com/legalsylvain.png?size=30px)](https://github.com/legalsylvain) | Prevent to unlink Confirmed or Invoiced Order Lines
[pos_order_line_note](pos_order_line_note/) | 12.0.1.0.4 | [![legalsylvain](https://github.com/legalsylvain.png?size=30px)](https://github.com/legalsylvain) | Store Order Line Note field in Database
[pos_order_mgmt](pos_order_mgmt/) | 12.0.1.1.4 |  | Manage old POS Orders from the frontend
[pos_order_picking_link](pos_order_picking_link/) | 12.0.1.0.1 | [![sadamo](https://github.com/sadamo.png?size=30px)](https://github.com/sadamo) [![mileo](https://github.com/mileo.png?size=30px)](https://github.com/mileo) | POS Order Picking Link
[pos_order_remove_line](pos_order_remove_line/) | 12.0.1.1.1 | [![robyf70](https://github.com/robyf70.png?size=30px)](https://github.com/robyf70) | Add button to remove POS order line.
[pos_order_return](pos_order_return/) | 12.0.1.1.0 |  | Point of Sale Order Return
[pos_order_return_traceability](pos_order_return_traceability/) | 12.0.1.0.1 |  | Adds full return traceability to POS frontend
[pos_order_to_sale_order](pos_order_to_sale_order/) | 12.0.1.0.4 | [![legalsylvain](https://github.com/legalsylvain.png?size=30px)](https://github.com/legalsylvain) | PoS Order To Sale Order
[pos_partner_firstname](pos_partner_firstname/) | 12.0.1.1.1 | [![robyf70](https://github.com/robyf70.png?size=30px)](https://github.com/robyf70) | POS Support of partner firstname
[pos_partner_no_create](pos_partner_no_create/) | 12.0.2.0.2 |  | Forbid customer creation from the POS
[pos_payment_change](pos_payment_change/) | 12.0.1.1.1 | [![legalsylvain](https://github.com/legalsylvain.png?size=30px)](https://github.com/legalsylvain) | Allow cashier to change order payments, as long as the session is not closed.
[pos_payment_method_cashdro](pos_payment_method_cashdro/) | 12.0.1.0.1 |  | Allows to pay with CashDro Terminals on the Point of Sale
[pos_payment_terminal](pos_payment_terminal/) | 12.0.0.1.6 |  | Manage Payment Terminal device from POS front end
[pos_picking_delayed](pos_picking_delayed/) | 12.0.2.0.2 | [![legalsylvain](https://github.com/legalsylvain.png?size=30px)](https://github.com/legalsylvain) | Delay the creation of the picking when PoS order is created
[pos_picking_load](pos_picking_load/) | 12.0.1.0.3 | [![legalsylvain](https://github.com/legalsylvain.png?size=30px)](https://github.com/legalsylvain) | Load and confirm stock pickings via Point Of Sale
[pos_picking_load_partner_name](pos_picking_load_partner_name/) | 12.0.1.0.2 | [![legalsylvain](https://github.com/legalsylvain.png?size=30px)](https://github.com/legalsylvain) | Improve load of picking in PoS by partner name
[pos_place](pos_place/) | 12.0.1.0.4 | [![legalsylvain](https://github.com/legalsylvain.png?size=30px)](https://github.com/legalsylvain) | Define places on PoS orders
[pos_prevent_double_closing](pos_prevent_double_closing/) | 12.0.1.0.2 |  | Prevent user to generate duplicates of accounting sale entries, when double closing sessions.
[pos_price_to_weight](pos_price_to_weight/) | 12.0.2.0.1 |  | Compute weight based on barcodes with prices
[pos_pricelist_technical](pos_pricelist_technical/) | 12.0.1.0.1 | [![legalsylvain](https://github.com/legalsylvain.png?size=30px)](https://github.com/legalsylvain) | Prevent technical pricelists from being displayed in the Point of Sale front-end UI
[pos_product_default_code](pos_product_default_code/) | 12.0.1.0.0 | [![eLBati](https://github.com/eLBati.png?size=30px)](https://github.com/eLBati) | Show Internal Reference in POS products list
[pos_product_sort](pos_product_sort/) | 12.0.1.0.2 | [![legalsylvain](https://github.com/legalsylvain.png?size=30px)](https://github.com/legalsylvain) | sort the products by name in the point of sale instead of sorting them by the sequence field.
[pos_product_template](pos_product_template/) | 12.0.1.0.2 |  | Manage Product Template in Front End Point Of Sale
[pos_quick_logout](pos_quick_logout/) | 12.0.1.0.1 |  | Allow PoS user to logout quickly after user changed
[pos_receipt_xml_header_footer](pos_receipt_xml_header_footer/) | 12.0.1.0.1 | [![carmenbianca](https://github.com/carmenbianca.png?size=30px)](https://github.com/carmenbianca) | Add the ability to use XML/HTML in the header and footer of a receipt
[pos_remove_pos_category](pos_remove_pos_category/) | 12.0.2.0.1 |  | POS Remove POS Category
[pos_report_order_payment](pos_report_order_payment/) | 12.0.1.0.1 |  | Analyze point of sale payments
[pos_report_session_summary](pos_report_session_summary/) | 12.0.1.0.0 |  | Adds a Session Summary PDF report on the POS session
[pos_require_product_quantity](pos_require_product_quantity/) | 12.0.0.2.1 |  | A popup is shown if product quantity is set to 0 for one or more order lines when clicking on "Payment" button.
[pos_reset_search](pos_reset_search/) | 12.0.1.0.0 | [![fkawala](https://github.com/fkawala.png?size=30px)](https://github.com/fkawala) | Point of Sale - Clear product search when user clicks on a product.
[pos_restaurant_user_restriction](pos_restaurant_user_restriction/) | 12.0.1.0.0 | [![GSLabIt](https://github.com/GSLabIt.png?size=30px)](https://github.com/GSLabIt) | Allow access pos restaurant to restricted users
[pos_session_closing_stock_error](pos_session_closing_stock_error/) | 12.0.1.0.1 | [![ivantodorovich](https://github.com/ivantodorovich.png?size=30px)](https://github.com/ivantodorovich) | Prevent closing PoS Sessions that have stock errors
[pos_session_pay_invoice](pos_session_pay_invoice/) | 12.0.1.0.1 |  | Pay and receive invoices from PoS Session
[pos_stock_picking_invoice_link](pos_stock_picking_invoice_link/) | 12.0.1.0.0 |  | POS Stock Picking Invoice Link
[pos_supplierinfo_barcode](pos_supplierinfo_barcode/) | 12.0.1.0.0 | [![eLBati](https://github.com/eLBati.png?size=30px)](https://github.com/eLBati) | Search products by supplier barcode
[pos_supplierinfo_search](pos_supplierinfo_search/) | 12.0.1.0.1 | [![eLBati](https://github.com/eLBati.png?size=30px)](https://github.com/eLBati) | Search products by supplier data
[pos_tare](pos_tare/) | 12.0.1.0.3 | [![fkawala](https://github.com/fkawala.png?size=30px)](https://github.com/fkawala) [![legalsylvain](https://github.com/legalsylvain.png?size=30px)](https://github.com/legalsylvain) | Manage Tare in Point Of Sale module
[pos_ticket_logo](pos_ticket_logo/) | 12.0.1.0.0 |  | Pos Ticket Logo
[pos_ticket_salesman_firstname](pos_ticket_salesman_firstname/) | 12.0.1.0.0 | [![ivantodorovich](https://github.com/ivantodorovich.png?size=30px)](https://github.com/ivantodorovich) | Pos Ticket Salesman Firstname
[pos_ticket_static_qrcode](pos_ticket_static_qrcode/) | 12.0.1.0.0 |  | PoS Ticket Static QrCode
[pos_ticket_without_price](pos_ticket_without_price/) | 12.0.1.0.1 |  | Adds receipt ticket without price or taxes
[pos_timeout](pos_timeout/) | 12.0.1.0.2 |  | Set the timeout of the point of sale
[pos_to_weight_by_product_uom](pos_to_weight_by_product_uom/) | 12.0.1.0.1 | [![legalsylvain](https://github.com/legalsylvain.png?size=30px)](https://github.com/legalsylvain) | Make 'To Weight' default value depending on product UoM settings
[pos_unavailable_product_friendly_error](pos_unavailable_product_friendly_error/) | 12.0.1.0.1 | [![legalsylvain](https://github.com/legalsylvain.png?size=30px)](https://github.com/legalsylvain) | Point of Sale - Friendly Error when product is not available
[pos_user_restriction](pos_user_restriction/) | 12.0.1.0.2 | [![eLBati](https://github.com/eLBati.png?size=30px)](https://github.com/eLBati) | Restrict some users to see and use only certain points of sale
[pos_warning_exiting](pos_warning_exiting/) | 12.0.1.0.2 | [![legalsylvain](https://github.com/legalsylvain.png?size=30px)](https://github.com/legalsylvain) | Add warning at exiting the PoS front office UI if there are pending draft orders


Unported addons
---------------
addon | version | maintainers | summary
--- | --- | --- | ---
[hw_telium_payment_terminal](hw_telium_payment_terminal/) | 12.0.1.0.0 (unported) |  | Adds support for Payment Terminals using Telium protocol

[//]: # (end addons)

<!-- prettier-ignore-end -->

## Licenses

This repository is licensed under [AGPL-3.0](LICENSE).

However, each module can have a totally different license, as long as they adhere to Odoo Community Association (OCA)
policy. Consult each module's `__manifest__.py` file, which contains a `license` key
that explains its license.

----
OCA, or the [Odoo Community Association](http://odoo-community.org/), is a nonprofit
organization whose mission is to support the collaborative development of Odoo features
and promote its widespread use.
