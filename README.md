# Perl Firi Crypto Trading API Package
 
Firi.com (previously MiraIex) is a Norwegian Crypto Exchange  

NOTE: This replaces the old Repo ktpx/perl-miraiex.

API Documentation: https://developers.firi.com/#/README  
API: https://api.firi.com   
URL: https://www.firi.com  


Examples:
```
my $api = Miraiex::API->new( apikey => <api_access_key>);
```
```
my $result = $api->market_trade_history( market => $market,
                                          count => $count );
                                            
my $result = get_balances();

```

All calls returns a reference to an array of hashes. See the [API](https://developers.miraiex.com/#/README) documentation for 
more detail.

### Perl Requirements

* LWP::UserAgent
* JSON::XS
* URI
* Switch
* Scalar::Util
* Config::General
* Digest::SHA
* Time::HiRes
* URI::Query

# API calls

```
 time()
 market()
 market_trade_history()
 ticker()
 balances()
 deposit_address()
 deposit_history()
 history_orders()
 history_trades()
 market_depth()
 active_orders()
 orders_history()
 orderid()
 create_order()
 delete_order()
 coin_withdrawal()
 coin_address()
 history_transactions()

```

Referal code @ firi.com:

https://firi.com/affiliate/?referral=2051eafd  

Tip Jar 


[![BTC Tip Jar](https://img.shields.io/badge/BTC-tip-yellow.svg?logo=bitcoin&style=flat)](https://www.blockchain.com/btc/address/bc1q4n6ny3qea3lg687n5dr92a607q4gxfvct4tl2v) `bc1q4n6ny3qea3lg687n5dr92a607q4gxfvct4tl2v`

[![ETH Tip Jar](https://img.shields.io/badge/ETH-tip-blue.svg?logo=ethereum&style=flat)](https://etherscan.io/address/0xA54cFB231Bf07dA327Deeba9c6fff04CE78dA571) `0xA54cFB231Bf07dA327Deeba9c6fff04CE78dA571`

Licence: GPLv3
