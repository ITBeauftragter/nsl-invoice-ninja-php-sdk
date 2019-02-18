# Invoice Ninja SDK

### Installation

Add the Invoice Ninja SDK

    composer require itbeauftragter/nsl-invoice-ninja-php-sdk

### Setup

    require __DIR__ . '/vendor/autoload.php';

    use NSLInvoice\Config as NinjaConfig;
    use NSLInvoice\Models\Client;

    NSLInvoice::setURL('https://ninja.dev/api/v1');
    NSLInvoice::setToken('Your Token');
