#### Detach a payment method

Detaches the Payment Method from a Customer.

##### Arguments

<table>
    <thead>
        <th>Key</th>
        <th>Required</th>
        <th>Type</th>
        <th>Default</th>
        <th>Description</th>
    </thead>
    <tbody>
        <tr>
            <td>$paymentMethodId</td>
            <td>true</td>
            <td>string</td>
            <td>null</td>
            <td>The payment method unique identifier.</td>
        </tr>
    </tbody>
</table>

##### Usage

```php
$paymentMethod = $stripe->paymentMethods()->attach('pm_1FNPdU2eZvKYlo2C09r77g4w');
```